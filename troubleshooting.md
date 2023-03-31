# troubleshooting
Things happen. The server will experence issues. This file contains a list of common issues.

1. Did the server shutdown? Turn the server back on.
2. Are requests being routed to your server? Verify your server's internal IP address didn't change. If it did, requests probably aren't being routed to your server. Update your routing configuration.
3. Did the IP address change? In terraform-aws run `terraform plan`. If it looks like your IP address changed, run `terraform apply`
