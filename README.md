Ansible Role: Watcher
=========

Install Consul-Template on Amazon Linux servers.

Requirements
------------

Written in Ansible 2.3.*

Role Variables
--------------

Available variables are listed below, along with default values (see `defaults/main.yml`):

## watcher_command_dir

Directory for watcher.py.

Default is `/opt/bin`

## watcher_config_dir

Directory for watcher conf.

Default is `/etc/watcher`

Dependencies
------------

Nothing.

Example Playbook
----------------

    - hosts: servers
      roles:
         - jkkitakita.watcher

License
-------

MIT

Author Information
------------------

This role was created in 2017 by [jkkitakita](http://jkkitakita.com/).
