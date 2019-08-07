# ansible-windowslogconfig

Ansible role for configuring Windows security logs

## Windows Security Log Configuration

The log configuration is based on the scripts from [Marlware Archeology](https://www.malwarearchaeology.com/logging)

## OS Platforms

This role has been tested on the following operating systems:

- Ubuntu 18.04

## Usage

To use this role in your playbook, add the code below:

```
- name: Configure Windows Security Logs
  import_role:
    name: ansible-windowslogconfig
```

## Disclaimer

This role is meant for use in the SANS 699 course and is provided as is.

## License

[MIT](LICENSE)