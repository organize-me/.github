# Server Setup

## Operating System

Ubuntu Server 22.04 LTS

## mDNS

To referernce our server within the local network, we need to set the hostname and setup mDNS. This allows us to reference our server using the domain organize-me.local without needing to configure the DNS server.

*Set the hostname*
```
sudo hostnamectl set-hostname organize-me
```

*Setup mDNS*
```
sudo apt update
sudo apt install avahi-daemon
sudo reboot
```

## Software:
  * Docker (Latest)
  * Terraform (1.0+)
  * Java 11+
  
