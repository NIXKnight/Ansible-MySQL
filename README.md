# **Ansible-MySQL**

Ansible-MySQL is an Ansible role for installing and configuring MySQL on Debian/Ubuntu.

## **Requirements**

At the moment this role is being written for Debian based distributions e.g. Debian/Ubuntu. It will evolve to include other major distributions.

## **Example Playbook**

Facts gathering must be enabled.

An example of running the role is as follows:
```yml
- hosts: servers
  gather_facts: True
  roles:
      - Ansible-MySQL
```
## **License**

This playbook is licensed under MIT License (See the LICENSE file).

## **Author**

[Saad Ali](https://github.com/nixknight)
