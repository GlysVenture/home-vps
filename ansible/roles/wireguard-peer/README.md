creates a new wireguard config and adds the peer to the server.

if needed generates new keypair

variables:
```yaml
# required
wireguard_peer_ip: "192.168.42.2"
public_ip: "127.0.0.1"

# optional
wireguard_peer_state: present # can be absent to remove
wireguard_peer_name: #optional unique tag in server config
wireguard_client_pubkey: #mandatory (or peer_name) for removing, optional for adding
wireguard_dns: "{{ internal_ip }},1.1.1.1,8.8.8.8"
```