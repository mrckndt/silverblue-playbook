# silverblue-playbook

Ansible playbook for managing my Fedora Silverblue workstations

```
sudo rpm-ostree usroverlay
sudo microdnf install ansible
ansible-galaxy collection install ansible.posix community.general
ansible-playbook -K silverblue.yml -l chapek9
```
