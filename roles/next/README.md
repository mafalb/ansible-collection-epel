# Ansible Role mafalb.epel.repo



## Basic Usage

```yaml
- name: install mafalb.epel.next
  hosts: localhost
  roles:
  - role: mafalb.epel.next
```

```yaml
- name: remove mafalb.epel.next
  hosts: localhost
  roles:
  - role: mafalb.epel.next
    epel_repo_state: absent
  - role: mafalb.epel.release
    epel_repo_state: absent
```

## Variables

### epel_repo_state

```yaml
epel_repo_state: present
```

```present``` is the default. you can remove epel-next-release with

```yaml
epel_repo_state: absent
```

---

## License

Copyright (c) 2021 Markus Falb <markus.falb@mafalb.at>

GPL-3.0-or-later
