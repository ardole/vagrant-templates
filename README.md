# Vagrant templates

Vagrant templates for various distributions and options (proxy, volumes...etc.)

## Simple VM

- [Debian strech](Vagrantfile_debian)
- [Debian strech using corporate proxy](Vagrantfile_proxy)
- [Port forwarding example](Vagrantfile_portforward)
- [Cluster](Vagrantfile_cluster)

## Share folder between host and VM, use vbguest plugin

- [Sync folder example (Windows)](Vagrantfile_syncfolderwindows)

On the host side:

```
vagrant plugin install vagrant-vbguest
```

## Cluster

- [Cluster provisioning from JSON](provisioning/Vagrantfile_cluster)