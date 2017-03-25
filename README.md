Ansible Role: Personal Dev
==========================

[![Build Status](https://travis-ci.org/ScorpionResponse/ansible-personal_dev.svg?branch=master)](https://travis-ci.org/ScorpionResponse/ansible-personal_dev)

Install/Configure my personal development stuff.

Requirements
------------

None.

Role Variables
--------------

* github_account: "scorpionresponse"

* dev_directory: "~/development"

Dependencies
------------

None.

Example Playbook
----------------

Example usage:

    - hosts: all
      roles:
         - { role: ScorpionResponse.personal_dev }

License
-------

BSD

Author Information
------------------

Github: https://github.com/ScorpionResponse
