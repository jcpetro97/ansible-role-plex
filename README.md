plex
====

Ansible role to install and manage [Plex Media Server](https://www.plex.tv/).


Requirements
------------
debian/ubuntu based system

Role Variables
--------------

``` yaml
# Application config
#
# Note that if you intend on using these directories, you will need to manually
# point to them from within your plex (GUI) config.
plex_app_transcode_directory: '/opt/plex_transcode'
plex_app_library_directory: '/opt/plex_library'
```


Examples
--------

```yaml
- hosts: 'localhost'
  roles:
    - role: Plex
```

Development
-----------
