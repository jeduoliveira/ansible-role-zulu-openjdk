Zulu OpenJDK
=========
[![Build Status](https://travis-ci.org/jeduoliveira/ansible-role-zulu-openjdk.svg?branch=master)](https://travis-ci.org/jeduoliveira/ansible-role-zulu-openjdk)


Installs Zulu JDK for RedHat/CentOS linux servers.

Supports the following Operating Systems:

CentOS 7
RedHat 7
Fedora 24
Fedora 23
Fedora 26
Fedora 27
Fedora 29
OracleLinux 7
Ubuntu 14.04
Ubuntu 16.04

Requirements
------------

None.

Role Variables
--------------
Available variables are listed below, along with default values:

    zulu_version: "11.33.15"
    jdk_version: jdk11.0.4

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
        - role: jeduoliveira.zulu_openjdk
          zulu_jdk_version: 11.31.11
          zulu_open_jdk_version: 11.0.3

License
-------

BSD

Author Information
------------------

This role was created in 2019 by [Jorge Eduardo](https://www.linkedin.com/in/jorgeeduardo/)
