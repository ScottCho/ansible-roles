# Ansible Role: Compile Python3

Fetches a specified Python source tarball, installs it into a specified build directory,
installs required dependencies, configures, makes and installs the resulting python3.
Currently it defaults to Python 3.8.0 if none is specified.


## Requirements

None.

## Role Variables

See [defaults/main.yml](defaults/main.yml)

## Dependencies

None.

## Example Playbook

    - hosts: servers
      roles:
         - { role: scott.compile-python3 }

## License