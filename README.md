ircd-hybrid
=========

This role installs and configures an [ircd-hybrid](http://www.ircd-hybrid.org/) IRC server using a minimal set of configuration options.

Requirements
------------

* Must run as root (Note: Role creates new non-root user, installs / runs server under new user)
* Only Ubuntu systems supported at this time

Role Variables
--------------

Repo defaults are found in [defaults/main.yml](defaults/main.yml)

Configuration information for the server address and oper user
should be overloaded in [vars/main.yml](vars/main.yml)

Dependencies
------------
None

Example Playbook
----------------

```yaml
    - hosts: ircd_servers
      roles: fatred.ircd-hybrid
```

License
-------

BSD

Author Information
------------------

John Howard (based on work done by James Ladd, Jr.)
