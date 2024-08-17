sets up a wireguard server

variables:
```yaml
# required
internal_ip: # set to set internal ip, if not set will be by role.

# optional
wireguard_port: 51820
wireguard_subnet: "192.168.42.0"
wireguard_subnet_mask: "24"
```