
An Ansible role which installs and configures Prometheus ssl_exporter on Linux

Role Variables

You can see all vars in defaults/main.yml vars file.

Example Playbook

- name: Ensure prometheus_ssl_exporter
  hosts: prometheus_ssl_exporters
  remote_user: root

  roles:
    - prometheus_ssl_exporter