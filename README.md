# Ansible Role: Ansible-monitoring-deployment repo 

[![Build Status](https://travis-ci.com/cloudalchemy/ansible-Ansible-monitoring-deployment.svg?branch=master)](https://travis-ci.com/cloudalchemy/ansible-Ansible-monitoring-deployment)
[![License](https://img.shields.io/badge/license-MIT%20License-brightgreen.svg)](https://opensource.org/licenses/MIT)
[![Ansible Role](https://img.shields.io/badge/ansible%20role-cloudalchemy.Ansible-monitoring-deployment-blue.svg)](https://galaxy.ansible.com/cloudalchemy/Ansible-monitoring-deployment/)
[![GitHub tag](https://img.shields.io/github/tag/cloudalchemy/ansible-Ansible-monitoring-deployment.svg)](https://github.com/cloudalchemy/ansible-Ansible-monitoring-deployment/tags)

## Description

Deploy Ansible-monitoring-deployment using ansible.

## Requirements

- Ansible >= 2.7 (It might work on previous versions, but we cannot guarantee it)

## Role Variables

All variables which can be overridden are stored in [defaults/main.yml](defaults/main.yml) file as well as in table below.

| Name           | Default Value | Description                        |
| -------------- | ------------- | -----------------------------------|
| `Ansible-monitoring-deployment_web_listen_address` | "0.0.0.0:80" | Address on which Ansible-monitoring-deployment will listen |

## Example

### Playbook

Use it in a playbook as follows:
```yaml
- hosts: all
  roles:
    - allaboutopensource.Ansible-monitoring-deployment
```


## Troubleshooting

See [troubleshooting](TROUBLESHOOTING.md).
