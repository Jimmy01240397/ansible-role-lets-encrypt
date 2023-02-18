# Ansible Role: let's encrypt

Ansible role for let's encrypt:

* basic, opinionated install

## Requirements

None.

## Role variables

[main.yml](defaults/main.yml)

## Dependencies

None.

## Example Playbook

```yaml
- hosts: all
  become: true
  roles:
    - role: jimmy01240397.letsencrypt
      emails:
      - aaa@example.com
      certs:
      - cn: example.com
        domains: 
        - example.com
        - aaa.example.com
```

## License

MIT

## Author Information

None
