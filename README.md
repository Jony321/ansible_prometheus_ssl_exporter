 # MikeCher/ansible_prometheus_ssl_exporter 
============

An Ansible role which installs and configures Prometheus ssl_exporter on Linux

============

## Requirements

Ansible 2.8+

============

## Role Variables

You can see all vars in defaults/main.yml vars file.

## Example Playbook

```yaml
- name: Ensure prometheus_ssl_exporter
  hosts: prometheus_ssl_exporters
  remote_user: root

  roles:
    - prometheus_ssl_exporter
  
```