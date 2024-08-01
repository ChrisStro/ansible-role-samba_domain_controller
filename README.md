# Ansible Role: samba_domain_controller

## WARNING
This role does not support multible hosts atm!!!! You end up with multible primary domain controllers hosting the same domain. Support for multible hosts will be added in the future if needed.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):
```yaml
# This is only for quick labs
samba_netbios_domainname: SAMBA
samba_domainname: SAMBA.LOCAL
samba_adminpwd: Start1234
```