# Ansible role `common`

The `common` role contains general tasks that are common to all managed machines. Specifically, the responsibilities of this role are to:

* Install external repositories (we assume through RPM packages), and packages not in the default minimal installation,
* Create users and groups,
* Set up an administrator account with an SSH key,
* Apply basic security settings, like turning on the firewall

## Assumptions

* The managed systems are RedHat-based, i.e. RedHat/CentOS or Fedora
