# Vagrant templates

Vagrant templates for various distributions and options (proxy, volumes...etc.)

- [Debian strech](Vagrantfile_debian)
- [Debian strech using corporate proxy](Vagrantfile_proxy)
- [Port forwarding example](Vagrantfile_portforward)
- [Sync folder example (Windows)](Vagrantfile_syncfolderwindows)

## Share folder between host and VM, use vbguest plugin

On the host side:

```
vagrant plugin install vagrant-vbguest
```
