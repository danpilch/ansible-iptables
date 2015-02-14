# ansible-iptables
A simple playbook for automation of iptable rules for a set of servers

## Supported platforms

```
CentOS 6 & 7
```

## Requirements

None

## Example Playbook

```
- hosts: example_servers
  vars_files:
   - group_vars/iptables/iptables_rules.yml
  roles:
    - role: anbsible-iptables
      ansible_iptables_system_role: "{{ example_rules }}"      
```

## License

MIT / BSD

## Author Information

Created by [Dan Pilch](https://github.com/danpilch) [@danpilch](https://twitter.com/danpilch)
