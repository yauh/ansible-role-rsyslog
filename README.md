# yauh.rsyslog
Ansible role for setting up rsyslog

**Work in progress**

## Requirements
SSH access to the remote machine

## Role Variables

```
...
```

By default all hosts are considered rsyslog clients. If a host has the `is_rsyslog_server` variable defined it will also execute tasks to make it the rsyslog server.

## Dependencies
none

## Example Playbook
Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```
- hosts: all
  roles:
     - { role: yauh.rsyslog }
```

## License
BSD

## Author Information
Stephan Hochhaus stephan@yauh.de

[https://github.com/yauh](https://github.com/yauh)
