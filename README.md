# Ansible Role: PHP Mirror

Installs the PHP mirroring role

## Requirements

None.

## Role Variables

See `defaults/main.yml`.

## Dependencies

nexcess.mirror

## Add to Requirements

    - src: https://github.com/nexcess/ansible-role-php-mirror.git
      name: nexcess.php-mirror

## Example Playbook

    - hosts: servers
      roles:
        - nexcess.php-mirror

## License

MIT / BSD
