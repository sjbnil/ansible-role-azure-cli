# Install Azure CLI

Ansible role to install the Azure CLI for either Ubuntu 16.04 (xenial) and 18.04 (bionic).

## Installation

`ansible-galaxy install sjbnil.azure_cli`

## Example Playbook

```yaml
- hosts: all
  roles:
    - sjbnil.azure_cli
```

## Requirements

None.

## Dependencies

None.