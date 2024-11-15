# noobient.example_role

## Synopsys

This role serves as a skeleton for other Ansible Galaxy roles.

## Parameters

| Name | Required | Example | Description |
|---|---|---|---|
| `msg` | yes | `Hello world!` | Message to be displayed. |

## Examples

```yml
- include_role:
    name: noobient.example_role
  vars:
    msg: 'Hello world!'
```

## Return Values

N/A

## Support

| Platform | Support | Status |
|---|---|---|
| Linter | ✅ | [![Lint](https://github.com/noobient/ansible-galaxy-example_role/actions/workflows/lint.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-example_role/actions/workflows/lint.yml) |
| AlmaLinux 8 | ✅ | [![AlmaLinux 8](https://github.com/noobient/ansible-galaxy-example_role/actions/workflows/almalinux-8.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-example_role/actions/workflows/almalinux-8.yml) |
| AlmaLinux 9 | ✅ | [![AlmaLinux 9](https://github.com/noobient/ansible-galaxy-example_role/actions/workflows/almalinux-9.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-example_role/actions/workflows/almalinux-9.yml) |
| Fedora 40 | ✅ | [![Fedora 40](https://github.com/noobient/ansible-galaxy-example_role/actions/workflows/fedora-40.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-example_role/actions/workflows/fedora-40.yml) |
| Fedora 41 | ✅ | [![Fedora 41](https://github.com/noobient/ansible-galaxy-example_role/actions/workflows/fedora-41.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-example_role/actions/workflows/fedora-41.yml) |
| Ubuntu 20.04 | ✅ | [![Ubuntu 20.04](https://github.com/noobient/ansible-galaxy-example_role/actions/workflows/ubuntu-20.04.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-example_role/actions/workflows/ubuntu-20.04.yml) |
| Ubuntu 22.04 | ✅ | [![Ubuntu 22.04](https://github.com/noobient/ansible-galaxy-example_role/actions/workflows/ubuntu-22.04.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-example_role/actions/workflows/ubuntu-22.04.yml) |
| Ubuntu 24.04 | ✅ | [![Ubuntu 24.04](https://github.com/noobient/ansible-galaxy-example_role/actions/workflows/ubuntu-24.04.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-example_role/actions/workflows/ubuntu-24.04.yml) |
