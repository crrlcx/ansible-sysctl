# About

Ansible role `ansible-sysctl` create, update and apply settings with sysctl.

## Requirements

-

## Role variables

### Defaults

```yaml
sysctl_vars: {}
```

### Override

```yaml
sysctl_vars_override: {}
```

## Dependencies

-

## Example playbook

```yaml
- hosts: servers
  roles:
    - role: ansible-sysctl
```

## License

MIT
