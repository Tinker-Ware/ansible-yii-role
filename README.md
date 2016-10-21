# Ansible Yii Framework role

This role is the first version to install and run a very basic Yii server for PHP.

### Variables
`cookie_validation_key:` Defines a validation key for the framework.

## Usage

Playbook file:

```
- hosts: myserver
  roles:
      - yii
```
