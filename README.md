cookiecutter-molecule
=====================

A Molecule template for `cookiecutter`.

Molecule provides a native cookiecutter interface, so developers can
provide their own templates.

[cookiecutter](https://github.com/audreyr/cookiecutter)

Features
=====

- Circleci
- Semantic-release for github
- Pre-Commit hook (husky) for yamllint and ansible-lint
- Commit-Message hook (husky) for semantic-releases
- Goss Verifier
- Advanced yaml linting
- nodemon for continuous linting

Usage
=====

I love [pyenv](https://github.com/pyenv/pyenv).
I use it to version my environment and to test different versions of ansible.
You can either also use it or install via pip in your system.

This goes a little something like this:

```bash
$ pip install cookiecutter yamllint ansible-lint
$ cookiecutter gh:lxhunter/cookiecutter-molecule
$ cd role_name
$ git init
# install modules and hooks
$ npm install
```

Contribute
==========

[Tutorial](http://kbroman.github.io/github_tutorial/pages/fork.html)

License and Author
==================

Author:: [Alexander Jäger](https://github.com/lxhunter)

Brandfrisch Copyright 2018
