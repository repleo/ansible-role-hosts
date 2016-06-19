Ansible role - Update /etc/hosts local domain lookup
=====
[![Build Status](https://travis-ci.org/repleo/ansible-role-hosts.svg?branch=master)](https://travis-ci.org/repleo/ansible-role-hosts)
[![Ansible Galaxy](http://img.shields.io/badge/galaxy-repleo.hosts-660198.svg?style=flat)](https://galaxy.ansible.com/repleo/hosts)


update /etc/hosts

Role Variables
--------------

- `hosts`

Example Playbook
-------------------------

    - hosts: servers
      roles:
         - { role: repleo.hosts,
             hosts:
               - { ip: 127.0.0.1, alias: localhost }
               - { ip: '::1', alias: localhosts }

License
-------

BSD - (c) 2016, Repleo, Amstelveen

Author Information
------------------

Repleo, Amstelveen, Holland -- www.repleo.nl
Jeroen Arnoldus (jeroen@repleo.nl)
