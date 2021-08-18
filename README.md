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

## Local Testing

The preferred way of locally testing the role is to use Docker and [molecule](https://github.com/ansible-community/molecule) (v3.x). You will have to install Docker on your system. See "Get started" for a Docker package suitable to for your system. Running your tests is as simple as executing `molecule test`.

## Continuous Intergation

Combining molecule and circle CI allows us to test how new PRs will behave when used with multiple ansible versions and multiple operating systems. This also allows use to create test scenarios for different role configurations. As a result we have a quite large test matrix which can take more time than local testing, so please be patient.

## Contributing

See [contributor guideline](CONTRIBUTING.md).

## Troubleshooting

See [troubleshooting](TROUBLESHOOTING.md).

## License

This project is licensed under MIT License. See [LICENSE](/LICENSE) for more details.
