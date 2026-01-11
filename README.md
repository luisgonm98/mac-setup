# mac-setup
Infrastructure-as-code for my macOS development machine using Ansible. Enables fast, repeatable setup on a new laptop.

To run the ansible playbook on your host, use the following command:

```
ansible-playbook -i inventory/hosts playbooks/mac.yml --ask-become-pass
```
