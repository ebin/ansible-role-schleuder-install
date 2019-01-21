Role Name
=========

This role is to install Schleuder.org on debian stretch.
Schleuder.org can used to implement an encrypted emailing list, where subscribers can exchange encrypted emails among themselves using open pgp encryption.

Requirements
------------
This is role can used to install schleuder on debian stretch

Role Variables
--------------

postfix version you want to use can be define in,

vars\main.yml

postfix_version: "postfix"



Dependencies
------------

Most of the dependent installation files are in the folder,

files\


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:
       
        ---
        - hosts: servers
          become: yes
          become_user: root
          roles:
               - schleuder-install

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
