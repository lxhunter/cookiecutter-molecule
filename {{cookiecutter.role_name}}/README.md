{{ cookiecutter.role_name }}
=========

This is a rule to setup {{ cookiecutter.role_name }} on a unix system

Requirements
------------

All python requirements are in `requirements.txt`

Role Variables
--------------

All role variables can be found in `defaults/main.yml`

Role Dependencies
------------

All role dependencies can be found in `meta/main.yml`

Test Playbook
----------------

If you want to know what is tested through [molecule](https://molecule.readthedocs.io/en/master/) see:

- `molecule/default/molecule.yml` for OSes we test against
- `molecule/default/playbook.yml` for what is being run in the test
- `molecule/default/tests/test_default.yml` for the [goss](https://goss.rocks) verfier


Quote
========
In the words of Steven Covey:

> "Man kann sich entscheiden nicht nur einen guten Tag zu haben, sondern einen Großen!"

Contribute
==========

[Tutorial](http://kbroman.github.io/github_tutorial/pages/fork.html)

Author 
==================

:: Author {{ cookiecutter.author }}

See LICENSE file

{{ cookiecutter.company }} Copyright 2018
