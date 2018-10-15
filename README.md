# js.graylog3/README.md
This role installs and configure graylog3 single server.   
It has no depencies and is easy to handle.   
Use files in test directory to get started with this role.   


## Execution Requirements
- Tested on CentOS 7

## Role Variables
* check `defaults/main.yml`

## Features
* Automatic restart of graylog service if config file has changed

## First Graylog Login:
When you first login, define Inputs:
System/Inputs > Inputs > Syslog UDP   
  "launch new input"   
    [x] Global   
    Title: Unix Syslog   
    Port: 1514   
    "Save"   

Now you can send syslog via UDP to Port 1514.   

# example playbooks for this role are located in `test` folder:
* `playbook_graylog3.yml`: Real life example with firewalld configuration

# Upgrade Graylog to v3 from v2
* https://github.com/Graylog2/graylog2-server/blob/master/UPGRADING.rst

# License
https://opensource.org/licenses/GPL-3.0    
Copyright (c) Chris Ruettimann <chris@bitbull.ch>  

