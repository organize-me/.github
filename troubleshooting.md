# Troubleshooting
Mishaps can occur, and sometimes the server may experience issues. To help you get back on track, we have compiled a list of common issues and their solutions:

1. Server Shutdown: If the server has shut down, simply turn it back on to resume normal operation.
1. Routing Issues: If requests are not being routed to your server, ensure that your server's internal IP address has not changed. If it has, update your routing configuration to allow requests to reach your server.
1. IP Address Changes: In the case of IP address changes, run `terraform plan` in [terraform-aws](https://github.com/organize-me/terraform-aws) to check if the IP address has indeed changed. If it has, run `terraform apply` to apply the new changes.
