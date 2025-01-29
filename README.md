# Ansible Demo for Quantiq

If you wish to try this on a local system, update `ansible_host` in `/host_vars/fedora_target.yml` to a target host, and run

`ansible-playbook -K -i inventory.yml demo.yml`

The current users ssh key must be on the target system, and the user must be able to elevate via sudo with password.
