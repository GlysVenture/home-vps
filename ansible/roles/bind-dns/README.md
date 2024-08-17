variables:
```yaml
# required
domain:
internal_ip:
internal_subnet:

# optional
bind_subdomains: # sets basic A records. example:
    www: "{{ internal_ip }}"
    app: <other_ip>
internal_iface: # if different than wg0
bind_ns_subdomain: ns1
```