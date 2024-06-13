# Ansible Project to Create VirtualBox VMs and Configure Kubernetes Cluster

This project contains Ansible playbooks to create VirtualBox VMs and set up a Kubernetes cluster.

## Structure

- `ansible.cfg`: Configuration file for Ansible.
- `inventory/hosts`: Inventory file listing the hosts.
- `playbooks/create_vms.yml`: Playbook to create VMs.
- `playbooks/configure_k8s.yml`: Playbook to configure Kubernetes on the VMs.
- `playbooks/roles/virtualbox/`: Role to handle VirtualBox installation and VM creation.
- `playbooks/roles/kubernetes/`: Role to handle Kubernetes installation and configuration.

## Usage

1. Ensure VirtualBox is installed on your machine.
2. Place the Ubuntu ISO in the specified path (`~/Downloads/ubuntu-20.04-live-server-amd64.iso`).
3. Run the playbook to create VMs:
   ```sh
   ansible-playbook playbooks/create_vms.yml

4. Run the playbook to configure Kubernetes:
   ```sh
   ansible-playbook playbooks/configure_k8s.yml

5. Run the playbook to deploy Nginx:
   ```sh
   ansible-playbook playbooks/deploy_nginx.yml


   
