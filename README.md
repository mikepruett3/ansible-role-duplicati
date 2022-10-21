Ansible Role: Duplicati Backup
=========

Ansible role to install/uninstall Duplicati Backup client on Linux servers.

Requirements
------------

The role does not require anything to run on Ubuntu, Debian or RHEL and its derivatives. This role assumes that you have the software package located on a web server somewhere in your environment.

Role Variables
--------------

The role does not require any specific variables, as the role will need to be updated when the package version is changed.

Dependencies
------------

None.

Example Playbook
----------------

``` yaml
    - hosts: servers
      roles:
         - role: mikepruett3.duplicati
```

License
-------

MIT

Author Information
------------------

Role created by [mikepruett3](https://github.com/mikepruett3) on [Github.com](https://github.com/mikepruett3/ansible-role-duplicati)
