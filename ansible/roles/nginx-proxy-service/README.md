variables:
```yaml
# required

internal_ip: # listen on this one if not external
internal_subnet: # restricts acl to sources from here if not external
domain:
nginx_service_subdomain: # like 'www' or 'app'
nginx_service_location: "http://localhost:8080" #where to forward requests

# optional
nginx_service_external: false
```