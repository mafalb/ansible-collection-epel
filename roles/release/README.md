# Ansible Role mafalb.epel.repo



## Basic Usage

```yaml
- name: install mafalb.epel.release
  hosts: localhost
  roles:
  - role: mafalb.epel.release
```

```yaml
- name: remove mafalb.epel.release
  hosts: localhost
  roles:
  - role: mafalb.epel.release
    epel_repo_state: absent
```

## Variables

### epel_repo_state

```yaml
epel_repo_state: present
```

```present``` is the default. you can remove epel-release with

```yaml
epel_repo_state: absent
```

---

## License

Copyright (c) 2021 Markus Falb <markus.falb@mafalb.at>

GPL-3.0-or-later
