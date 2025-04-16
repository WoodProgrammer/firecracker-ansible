# firecracker-ansible
This is a repository contains ansible playbook for firecracker setup; You can easily  use this template for firecracker setup on your KVM supported instances.

## The content is ;
* Install dependencies
* Generate config files
* Build rootfs on target images

## Simple Usage;

```sh
$ ansible-playbook playbooks/site.yaml -u root -i inventories/hosts
```