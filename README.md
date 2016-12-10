# TruckIt Ansible Config

**Requirements:**

 - Ansible 2.x - `http://docs.ansible.com/ansible/intro_installation.html`
 - (optional) Vagrant v1.8.5+

**Before start**
 - Open `./envs/*/certificates`
 - Run `chmod 0400 *` to change permissions for certificates

**How you can update existing local (Vagrant) server?**

 - Open `./envs/local/inventory`
 - Check your ip or hostname  in `local` section
 - Run `ansible-playbook -i ./envs/local/inventory local-setup.yml` to update instance.
