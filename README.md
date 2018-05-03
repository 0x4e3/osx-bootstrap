# OSX Bootstrap

Ansible playbook for Mac OS X bootstrap for Python Full stack developers.

[![GitHub license](https://img.shields.io/github/license/0x4e3/osx-bootstrap.svg)](https://github.com/0x4e3/osx-bootstrap/blob/master/LICENSE)

## Roles

* [0x4e3.osx-bootstrap-defaults](https://galaxy.ansible.com/0x4e3/osx-bootstrap-defaults/) -- configure Mac OS X defaults.
* [0x4e3.osx-bootstrap-homebrew](https://galaxy.ansible.com/0x4e3/osx-bootstrap-homebrew/) -- install homebrew, required taps, packages and applications.
* [0x4e3.osx-bootstrap-user](https://galaxy.ansible.com/0x4e3/osx-bootstrap-user/) -- configure user environment (shell, path, etc.).
* [0x4e3.osx-bootstrap-npm](https://galaxy.ansible.com/0x4e3/osx-bootstrap-npm/) -- install node, npm and required global packages for frontend.

## General content

In my work, I use:
* zsh with oh-my-zsh
* Python 2, Python 3 and Go for backend development
* pipenv and pyenv to install Python versions and packages
* Ember.js for frontend development
* PostgreSQL, MySQL databases
* MongoDB
* Redis and RabbitMQ as a message brokers

## Variables

Repository contains my own preferred settings and lists of packages and applications.

## Installation

Install all required roles:

```bash
ansible-galaxy install -r requirements.yml
```

Play:

```bash
ansible-playbook playbook.yml
```

## Credits

* [macOS Defaults](https://github.com/kevinSuttle/macOS-Defaults) -- wonderful collection of Mac OS X defaults by [Mathias Bynens](https://github.com/mathiasbynens) and [Kevin Suttle](https://github.com/kevinSuttle)
