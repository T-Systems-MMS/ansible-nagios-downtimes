ansible-nagios-downtimes
=========

This role manages nagios downtimes with Ansible.

Requirements
------------

...

Role Variables
--------------

- nagios_uri
- PROJECT_PREFIX
- ENV
- type
- affected_hosts_and_services
- nagios_user
- nagios_pw

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - name: Manage Nagios downtimes
      hosts: all
      gather_facts: false
        roles:
        - roles/nagios

License
-------

Apache

Author Information
------------------

This role was created by Filip Krahl
