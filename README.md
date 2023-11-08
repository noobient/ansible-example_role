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
| Fedora 38 | ✅ | [![Fedora 38](https://github.com/noobient/ansible-galaxy-example_role/actions/workflows/fedora-38.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-example_role/actions/workflows/fedora-38.yml) |
| Fedora 39 | ✅ | [![Fedora 39](https://github.com/noobient/ansible-galaxy-example_role/actions/workflows/fedora-39.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-example_role/actions/workflows/fedora-39.yml) |
| Ubuntu 18.04 | ✅ | [![Ubuntu 18.04](https://github.com/noobient/ansible-galaxy-example_role/actions/workflows/ubuntu-18.04.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-example_role/actions/workflows/ubuntu-18.04.yml) |
| Ubuntu 20.04 | ✅ | [![Ubuntu 20.04](https://github.com/noobient/ansible-galaxy-example_role/actions/workflows/ubuntu-20.04.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-example_role/actions/workflows/ubuntu-20.04.yml) |
| Ubuntu 22.04 | ✅ | [![Ubuntu 22.04](https://github.com/noobient/ansible-galaxy-example_role/actions/workflows/ubuntu-22.04.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-example_role/actions/workflows/ubuntu-22.04.yml) |
