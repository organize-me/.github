## Organize Me

In today's digital age, data privacy and security are more important than ever. With the increasing number of data breaches and privacy violations, it's crucial to be proactive and protect sensitive information and be less dependent on others. This project represents my self-hosting effort. Other than maintaining some off-site backups, a domain name, and application parameters on AWS, all of my servers are hosted on a small x86 in my closet.

These services are routed through a nginx reverse proxy, encrypted using Let's Encrypt.

### Services:
 * wikijs (wiki)
 * nextcloud (cloud services: photo backups, files, calendar, notes, etc..)
 * snipe-it (inventory)
 * vaultwarden (password manager)
 
### Infastructure
 * Nginx (reverse proxy)
 * Keycloak (single sign on)
 * MySQL (database persistance)
 * Pi-hole (DNS [and ad-blocking])
