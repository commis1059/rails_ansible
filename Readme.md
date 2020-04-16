# README

This project can create a rails project that looks like the following by Ansible.

* DB: MySQL on Docker
* Job: Sidekiq
* Front: Vue CLI
* Unit Test: RSpec

## Dependence
* Ansible
* rbenv
* nodenv
* docker-compose

## Usage
1. Edit ansible/host_vars/127.0.0.1/personal.yml to suit your Environment.
1. Execute `ansile-playbook site.yml` in ansible directory.
1. Edit .env to suit your Environment.
1. Execute `bin/setup` in project root directory.
