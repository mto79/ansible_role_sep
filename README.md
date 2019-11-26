Symantec Endpoint Protection client for Linux and Windows
=========

Ansible Role - Symantec Endpoint Protection client for Linux and Windows

Requirements
------------


Role Variables
--------------

Redhat

sep_rh_repo
sep_rh_dir_install
sep_rh_file_install

Windows

sep_win_repo
sep_win_dir_install
sep_win_file_install
sep_win_file_ps1


Dependencies
------------


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ansible_role_sep }

License
-------

MIT

Author Information
------------------

Developed by [MTO](https://www.mto.nu/).
