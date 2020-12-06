# Ansible "cluster"

## Servers

|Server|IP|OS|Detail|
|---|---|---|---|
|ansible-control-machine|192.168.48.140|CentOS 7|Ansible master|
|ansible-node-1|192.168.48.141|CentOS 7|Node|
|ansible-node-2|192.168.48.142|CentOS 7|Node|
|ansible-node-3|192.168.48.143|Debian 9|Node|

## Test it

- Login to `ansible-control-machine`

`vagrant ssh ansible-control-machine`

- Build new `inventory`

```
[all]
ansible-control-machine ansible_host=192.168.48.140
ansible-node-1 ansible_host=192.168.48.141
ansible-node-2 ansible_host=192.168.48.142
ansible-node-3 ansible_host=192.168.48.143
```
