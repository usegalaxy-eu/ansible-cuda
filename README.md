ansible-cuda
=======

Ansible role to install the CUDA toolkit as described in the [NVIDIA CUDA Installation Guide](https://docs.nvidia.com/cuda/cuda-installation-guide-linux/index.html#abstract) in a Redhat/CentOS system.

Requirements
------------
Ansible >= 2.11



Usage
-----
Clone this repo into your roles directory:

```bash
$ ansible-galaxy install usegalaxy_eu.cuda
```

And add it to your playbook's roles:

```yaml
- hosts: yourhost

  roles:
    - role: usegalaxy_eu.cuda
      become: yes
```

This role comes preloaded with multiple available defaults. You can override each one in your hosts/group vars, in your inventory, or in your play. See the annotated defaults in defaults/main.yml for help in configuration.
      
License
-------

GPLv3

Author Information
------------------

[Gianmauro Cuccuru](https://github.com/gmauro)
