Ambari-presto
=========

Ansible role for setting up Presto using Ambari servies.

Requirements
------------

- Red Hat Enterprise Linux 6.x (64-bit) or CentOS equivalent.
- You must have Ambari installed.
- Oracle’s JDK 1.8
- Disable requiretty. On RHEL 6.x this can be done by editing the /etc/sudoers file and commenting out Defaults requiretty.


Role Variables
--------------

- presto_ambari_path
- presto_ambari_url
- presto_ambari_tar

You can edit this in the tasks-main yaml file.

Setup Playbook
----------------

    - hosts: servers
      roles:
         - { role: vishnudxb.ambari-presto }

License
-------

MIT

Author Information
------------------

Some useful stuff at:

- https://github.com/vishnudxb
- Any issues, pull-request are welcome
