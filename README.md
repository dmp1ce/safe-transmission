Create a (hopefully) safe torrenting system which does not leak, IPv6 or DNS information to a peer who wants to determine your identity.

This uses the containers created and maintained by [dperson](https://github.com/dperson).

# Usage

``` bash
# (Optional) Add your configuration into vpn/vpn.conf OR mondify docker-compose.yml openvpn configuraiton

# Start containers.
docker-compose up -d

# Open transmission-remote-gtk or another remote client and access port 11180 with user//pass admin//admin
```
