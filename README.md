# opscenter-agent aka datastax-agent

# Variables

## Required

- ```{{ opscenter_inventory_hostname }}``` has to be set to the inventory name of host with [opscenter role](https://github.com/gitinsky/ansible-role-opscenter) applied

## Optional

- ```{{ opscenter_int }}``` interface on the opscenter host, by default ```{{ ansible_default_ipv4.interface }}``` will be used
