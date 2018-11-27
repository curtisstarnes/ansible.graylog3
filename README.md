[![Build Status](https://travis-ci.org/uniQconsulting-ag/ansible.os-basic.svg?branch=master)](https://travis-ci.org/uniQconsulting-ag/ansible.graylog3)

[![Alt text](https://www.uniqconsulting.ch/images/logo.png)](https://www.uniqconsulting.ch/)

Graylog3 Setup with Ansible
===========================

This Ansible Role install, configure and update a Linux Graylog3 server. The following tasks will be configured:
* `Install and configure MongoDB`
* `Install and configure Elasticsearch`
* `Install and configure Java`
* `Install and configure Graylog3`

Requirements
------------

* Currently only tested with CentOS 7
* Ansible 2.4 or higher is required for this Ansible Role

Role Variables
--------------

Variables are self speaking or documented in:   
* `defaults/main.yml`
* `vars/main.yml`

Dependencies
------------

This Ansilbe Role has no dependencies to other Ansilbe Roles

Example Playbook
----------------

Example playbooks for this role are located in ´test´ folder:
* `tests/playbook_graylog.yml`

uniQconsulting ag
-----------------

uniQconsulting ag is a company in Switzerland with Offices in Bassersdorf, Basel and St. Gallen

License
-------
https://opensource.org/licenses/LGPL-3.0    
Copyright (c) uniQconsulting ag - Chris Ruettimann cruettimann@uniqconsulting.ch
