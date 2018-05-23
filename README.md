sbog/graylog
============

Role to install and configure Graylog

#### Requirements

Ansible 2.4

#### Role Variables

```yaml
graylog_password_secret: somepasswordpepper
# admin
graylog_root_password_sha2: 8c6976e5b5410415bde908bd4dee15dfb167a9c873fc4bb8a81f6f2ab448a918
graylog_hostname: localhost
```

#### Dependencies

None

#### Example Playbook

```yaml
- name: Install and configure Graylog
  hosts: graylogs
  remote_user: root

  roles:
    - graylog
```

#### License

Apache 2.0

#### Author Information

Stanislaw Bogatkin (https://sbog.ru)
