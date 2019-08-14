# ror-100
Ruby on Rails dev environment

Vagrant box with
- ruby 2.6.3
- rails 5.2.3

# Pre-requirements

- Vagrant
- git

# Usage

```bash
vagrant up
cd /vagrant
rails new app-name
cd app-name
bundle install
rails server -b 0.0.0.0
```
