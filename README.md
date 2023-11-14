Role Name
=========

Clickhouse-role

Requirements
------------

Installs clickhouse server and creates database logs if it did not exist. Contains server and client of clickhouse.

Role Variables
--------------

| Variable name | Variable description |
|-------------|---------------------|
| clickhouse_version | Version of clickhouse server and client |
 
How to use role
----------------
 
  - hosts: servers
    roles:
        - { role: clickhouse-role }

How to install in subfolder **roles** of current project folder
---------------

ansible-galaxy role install --roles-path ./roles git+https://github.com/grigoryevpavel/roles-clickhouse.git

License
-------

MIT

Author Information
------------------

Pavel Grigoryev

