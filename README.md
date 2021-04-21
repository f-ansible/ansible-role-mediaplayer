# Ansible Role: Mediaplayer

Ansible role to install [Mediaplayer](https://github.com/PeteManchester/MediaPlayer)

## Requirements

## Role Variables

## Dependencies

## Example Playbook

```yaml
- hosts: servers
  roles:
    - role: fesaille.mediaplayer
      log_file_level: error
      log_file_name: /var/log/mediaplayer.log
      mediaplayer_enable_avTransport: false
      mediaplayer_friendly_name: Salon
      mediaplayer_startup_volume: 10
```

## License

BSD

## Author Information
