
This role installs wal-g binary from github releases

Requirements
------------

none

Role Variables
--------------

### wal-g version to fetch
walg_version: v0.2.11

### default wal-g releases repository url
walg_url: "https://github.com/wal-g/wal-g/releases/download/{{walg_version}}/wal-g.linux-amd64.tar.gz"

### wal-g install path
walg_binary_path: /usr/local/sbin

Dependencies
------------
none

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables
passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: wal-g.role, walg_version: v0.2.11 }

License
-------

GPLv2

Author Information
------------------

Ilya Rubinchik (aka Citius)
