# OSX Bootstrap

Ansible playbook for Mac OS X bootstrap for Python Full stack developers.

## Roles

* [0x4e3.osx-bootstrap-homebrew](https://galaxy.ansible.com/0x4e3/osx-bootstrap-homebrew/) -- install homebrew, required taps, packages and applications.
* [0x4e3.osx-bootstrap-user](https://galaxy.ansible.com/0x4e3/osx-bootstrap-user/) -- configure user environment (shell, path, etc.).
* [0x4e3.osx-bootstrap-npm](https://galaxy.ansible.com/0x4e3/osx-bootstrap-npm/) -- install node, npm and required global packages for frontend.

## General content

In my work, I use:
* Python 2, Python 3 and Go for backend development
* pipenv and pyenv for Python dependencies management
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

## Notes

This playbook and all roles had been created to automate my own workstation configuration and it's 100% prefect, IMHO.
