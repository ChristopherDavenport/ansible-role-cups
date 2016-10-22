# Cups Ansible Role

[![Build Status](https://travis-ci.org/ChristopherDavenport/ansible-role-cups.svg?branch=master)](https://travis-ci.org/ChristopherDavenport/ansible-role-cups)

Installs Cups for Printing on RHEL/CentOS or Debian/Ubuntu. With a more complete package list for other distros this can easily be extended and I would be happy to do so.

## Requirements

None, the point is to install basic building blocks for a more complex service in this case the components for printing.

## Dependencies

-   None

## Example Playbook

```
- hosts: serversthatprint
  roles:
    - ChristopherDavenport.cups
```

### License

MIT

### Author Information

This role was created in 2016 by Christopher Davenport
