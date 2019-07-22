ansible-cuda
=======

Ansible role to install the CUDA toolkit as described in the [NVIDIA CUDA Installation Guide](https://docs.nvidia.com/cuda/cuda-installation-guide-linux/index.html#abstract) in a Redhat/CentOS system.

Requirements
------------
Ansible >= 2.4



Usage
-----
Clone this repo into your roles directory:

```bash
$ git clone https://github.com/usegalaxy-eu/ansible-cuda.git roles/cuda
```

And add it to your playbook's roles:

```yaml
- hosts: yourhost

  roles:
    - role: cuda
      become: yes
```
      
License
-------

GPLv3

Author Information
------------------

[Gianmauro Cuccuru](https://github.com/gmauro)
