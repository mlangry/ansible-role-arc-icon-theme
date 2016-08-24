mlangry.arc-icon-theme
=========

An ansible role to install the arc-icon-theme.

Requirements
------------

Git 1.7.1 must be installed.

Role Variables
--------------

````yaml
arc_icon_theme_install_path:  /usr/share/arc-icon-theme
````

Dependencies
------------

None

Example Playbook
----------------

````yaml
- hosts: desktop
  roles:
     - mlangry.arc-icon-theme
````
License
-------

MIT
