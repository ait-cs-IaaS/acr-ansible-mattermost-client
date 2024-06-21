# Ansible-Role:  acr-ansible-mattermost-client

AIT-CyberRange: Installs mattermost client.


## Requirements

- Debian or Ubuntu 

## Role Variables

```yaml
username: placeholder
mattermost_url: mattermost.com
```

## Example Playbook

```yaml
- hosts: localhost
  roles:
    -  acr-ansible-mattermost-client
      vars:
        username: placeholder
        mattermost_url: mattermost.com
```

## License

GPL-3.0

## Author

- Lenhard Reuter