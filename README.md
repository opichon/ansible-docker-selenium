# ansible-docker-selenium

An ansible role to deploy  selenium server as a docker container

## Requirements

This role requires Ansible 1.2 or higher.

## Role variables

Ansible variables are listed below with their default values.

```
selenium_hostname
selenium_network
```

## Example playbook

```
---
- hosts: webservers
  roles:
  	- opichon.docker-selenium
```

## License

MIT
