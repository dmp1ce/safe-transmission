Create a (hopefully) safe torrenting system which does not leak, IPv6 or DNS information to a peer who wants to determine your identity.

This uses the containers created and maintained by [dperson](https://github.com/dperson).

This project an example project from what [decompose-safe-transmission[(https://github.com/dmp1ce/decompose-safe-transmission.git) will generate. Better to start there if using decompose.

# Requirements

- [Decompose](https://github.com/dmp1ce/decompose)
- [Docker](http://www.docker.com/)
- [Docker Compose](http://docs.docker.com/compose/)

# Usage

``` bash
# Add your configuration into vpn/vpn.conf OR modify docker-compose.yml.mo openvpn configuraiton

# Modify default settings
vim .decompose/elements

# Build configuration
decompose --build

# Start containers.
docker-compose up -d

# Open transmission-remote-gtk or another remote client and access port 11180 with user//pass admin//admin
```
