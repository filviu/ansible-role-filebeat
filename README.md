# Ansible Role: Filebeat

[![CI](https://github.com/filviu/ansible-role-filebeat/workflows/CI/badge.svg?event=push)](https://github.com/filviu/ansible-role-filebeat/actions?query=workflow%3ACI)

Sets up Filebeat. Doesn't deploy a configuration, this is for use together with the Graylog Sidecar.

## Requirements

None.

## Role Variables

See `defaults/main.yml`:

    filebeat_version

The filebeat version to deploy.

## Dependencies

None.

## Example Playbook

```yaml
---
- hosts: all

  roles:
    - role: filviu.filebeat
```

## License

MIT / BSD


## Author Information

This role was created by Silviu Vulcan to scratch his own itch.
