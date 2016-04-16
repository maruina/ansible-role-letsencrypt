# Ansible Role: Let's Encrypt 0.1
[![Build Status](https://travis-ci.org/maruina/ansible-role-letsencrypt.svg?branch=master)](https://travis-ci.org/maruina/ansible-role-letsencrypt)
An Ansible role that convert install [letsencrypt](https://letsencrypt.org/)

## Note
Only the `webroot` plugin is supported.

## Download from Ansible Galaxy
```bash
ansible-galaxy install maruina.letsencrypt
```

## Example Playbook
```yaml
    - hosts: all
      roles:
        - { role: maruina.letsencrypt }
```

## License

MIT
