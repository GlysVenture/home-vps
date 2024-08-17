configures sshd to use pubkey auth (only)

variables:
```yaml
# required
sshd_allowed_ssh_keys: # list of allowed ssh keys to be stored in authorized_keys file
    - <ssh pub key>

# optional
sshd_key_only: true
sshd_port: 22
```