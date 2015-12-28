ansible-oracle-host
=========

This will configure the host specific Oracle stuff.  Currently single instance only.

Add a user & group
Create directory structures
Install required packages
Change kernel paramemeters
Set up pam.d/limits config
Disables transparent hugepages
Disables NUMA (if needed)

Based on oravirt/ansible-oracle (https://github.com/oravirt/ansible-oracle)

Role Variables
--------------


Dependencies
------------


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
        - role: common
        - role: orahost
