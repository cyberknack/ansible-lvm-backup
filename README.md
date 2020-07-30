# ansible-lvm-backup
Create backup from lvm
# Requirements
None.

# Role Variables
`ansible_lvm (from gather-facts)`

# Dependencies
None.


# Example Playbook
```
- hosts: kvm
  gather_facts: yes
  roles:
   - ansible-lvm-backup
```
# License
MIT

# Author Information
This role was created in 2020 by Saeed Ghasempoor.
