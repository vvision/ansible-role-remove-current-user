# ansible-role-remove-current-user

[![CI](https://github.com/vvision/ansible-role-remove-current-user/workflows/CI/badge.svg?event=push)](https://github.com/vvision/ansible-role-remove-current-user/actions?query=workflow%3ACI)

Switch to another user before deleting user currently executing the ansible playbook.
This is a destructive operation. User to switch to should be available (role will not create it).

## Requirements

None.

## Role Variables

    user_to_switch_to: "root"

User to switch to before deleting current ``ansible_user``.

## Dependencies

None.

## License

MIT

## Author Information

This role was created in 2021 by Victor Voisin.
