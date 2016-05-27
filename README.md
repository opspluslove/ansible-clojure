[![Build Status](https://travis-ci.org/opspluslove/ansible-clojure.svg?branch=master)](https://travis-ci.org/opspluslove/ansible-clojure)

clojure
=========

In your [requirements file](https://galaxy.ansible.com/intro):

```
- src: opspluslove.clojure
  version: v1.0.0
```

----

Ansible role to setup everything to run clojure projects

Example Playbook
----------------

```
- hosts: main-server
  remote_user: root

  roles:
    - opspluslove.clojure
```
