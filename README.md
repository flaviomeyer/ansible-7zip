Role Name
=========

This install 7zip with ansible role in version 16.04.

Requirements
------------

It doesn't need any requirements.
Currently only tested on Windows Server 2016. But it is compatible with all Windows Version because it install .msi package.

Role Variables
--------------

sevenzip_uninstall: no # default is the variable no. When it is yes or true, then uninstall 7zip.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: meyerf99.7zip, sevenzip_uninstall: no }

License
-------

BSD

Author Information
------------------

Flavio Meyer, https://flavio-meyer.ch
