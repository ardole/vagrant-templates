# Vagrant templates

Vagrant templates for various usages.

|Template|Description|
|---|---|
|[Docker](./docker)|For playing with docker|
|[Kubernetes](./kubernetes)|For playing with kubectl|
|[Ansible](./ansible)|For playing with Ansible|
|[Ansible cluster](./ansible-cluster)|For playing with Ansible|
|[VM cluster](./vmcluster)|Sample for creating VM clusters|

## If you need to share folder between host and VM, use vbguest plugin

On the host side:

```
vagrant plugin install vagrant-vbguest
```
