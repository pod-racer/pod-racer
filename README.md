# pod-racer

A containerized, single-node [OKD cluster](https://github.com/openshift/origin/) for development, based on a CentOS 7 instance.

## Preparation

Make a copy of `hosts.example` and modify it.

## Installation

Execute the `install` playbook:

```shell
ansible-playbook -i inventory/hosts playbook/install.yaml
```

Done !