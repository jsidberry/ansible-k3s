This playbook will build an HA Kubernetes cluster with `k3s`, `kube-vip` and MetalLB via `ansible`.

## System requirements

- Control Node (the machine you are running `ansible` commands) must have Ansible 2.11+.

- You will also need to install collections that this playbook uses by running `ansible-galaxy collection install -r ./collections/requirements.yml` (important❗)

- [`netaddr` package](https://pypi.org/project/netaddr/) must be available to Ansible. If you have installed Ansible via apt, this is already taken care of. If you have installed Ansible via `pip`, make sure to install `netaddr` into the respective virtual environment.

- `server` and `agent` nodes should have passwordless SSH access, if not you can supply arguments to provide credentials `--ask-pass --ask-become-pass` to each command. <- typical Ansible thang, yo.


## Getting Started

### Preparation

### Create Cluster

### Remove k3s cluster


## Kube Config

### Testing your cluster

### Variables

### Troubleshooting


## References

- [k3s-io/k3s-ansible](https://github.com/k3s-io/k3s-ansible)
- [geerlingguy/turing-pi-cluster](https://github.com/geerlingguy/turing-pi-cluster)
- [212850a/k3s-ansible](https://github.com/212850a/k3s-ansible)
