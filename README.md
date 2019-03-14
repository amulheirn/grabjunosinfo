# grabjunosinfo
This is an ansible script to pull Junos versions, serials and models from a list of Junos hosts for audit purposes.

There are two YAML files - one uses the Ansible core modules, maintained by Ansible.  The other uses the Juniper-provided modules.  This is to show the differences between the two.

The result should be a CSV file stored in the ./logs subdirectory that contains the hostname, serial, model and version of Junos in use.
