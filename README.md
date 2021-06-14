Duo Authpropxy
=========

Deploys the Duo authentocation proxy  and configures using Ansible for Linux Debian and RHEL based hosts.

Requirements
------------

Debian or RHEL based Linux host server 

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in
defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables
that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as
well.

defaults/main.yml - contains the authproxy  configuration file variables to configure the authproxy.cfg file as required.
Change the variables contained here as needed to configure thre proxy for your environment

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for
users too:

- name: "apply authproxy role"
  hosts: all 
  become: true
  roles:
   - duo_authentication_proxy


License
-------

 GNU GENERAL PUBLIC LICENSE
 Version 3, 29 June 2007

Author Information
------------------

Marcus Lavender. - mlavender@duosecurity.com.
