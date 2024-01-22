
# Ansible Role:  `ansible`

Ansible role to install and configure ansible on various linux systems.

[![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/bodsch/ansible-ansible/main.yml?branch=main)][ci]
[![GitHub issues](https://img.shields.io/github/issues/bodsch/ansible-ansible)][issues]
[![GitHub release (latest by date)](https://img.shields.io/github/v/release/bodsch/ansible-ansible)][releases]
[![Ansible Downloads](https://img.shields.io/ansible/role/d/bodsch/ansible?logo=ansible)][galaxy]

[ci]: https://github.com/bodsch/ansible-ansible/actions
[issues]: https://github.com/bodsch/ansible-ansible/issues?q=is%3Aopen+is%3Aissue
[releases]: https://github.com/bodsch/ansible-ansible/releases
[galaxy]: https://galaxy.ansible.com/ui/standalone/roles/bodsch/ansible/

## Requirements & Dependencies


### Operating systems

Tested on

* Arch Linux
* Debian based
    - Debian 10 / 11 / 12
    - Ubuntu 20.10 / 22.04

> **RedHat-based systems are no longer officially supported! May work, but does not have to.**


## Configuration

```yaml
ansible_config:
  system:
    defaults: {}
    privilege_escalation: {}
    persistent_connection: {}
    connection: {}
    colors: {}
    selinux: {}
    diff: {}
    galaxy: {}
    inventory: {}
    netconf_connection: {}
    paramiko_connection: {}
    jinja2: {}
    tags: {}
    runas_become_plugin: {}
    su_become_plugin: {}
    sudo_become_plugin: {}
    callback_tree: {}
    ssh_connection: {}
    winrm: {}
    inventory_plugins: {}
    inventory_plugin_script: {}
    inventory_plugin_yaml: {}
    url_lookup: {}
    powershell: {}
    vars_host_group_vars: {}
  users: 
    - name: foo
      defaults: {}
      privilege_escalation: {}
      persistent_connection: {}
      connection: {}
      colors: {}
      selinux: {}
      diff: {}
      galaxy: {}
      inventory: {}
      netconf_connection: {}
      paramiko_connection: {}
      jinja2: {}
      tags: {}
      runas_become_plugin: {}
      su_become_plugin: {}
      sudo_become_plugin: {}
      callback_tree: {}
      ssh_connection: {}
      winrm: {}
      inventory_plugins: {}
      inventory_plugin_script: {}
      inventory_plugin_yaml: {}
      url_lookup: {}
      powershell: {}
      vars_host_group_vars: {}
```

---
    
## Contribution

Please read [Contribution](CONTRIBUTING.md)

## Development,  Branches (Git Tags)

The `master` Branch is my *Working Horse* includes the "latest, hot shit" and can be complete broken!

If you want to use something stable, please use a [Tagged Version](https://github.com/bodsch/ansible-ansible/tags)!


## Author

- Bodo Schulz

## License

[Apache](LICENSE)

**FREE SOFTWARE, HELL YEAH!**

