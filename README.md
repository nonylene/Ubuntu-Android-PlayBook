Run on Ubuntu 14.04

# Example

Dry run

```sh
$ ansible-playbook -i hosts unyaunya.yml --tags="nginx" -K --check
```

run

```sh
$ ansible-playbook -i hosts unyaunya.yml --tags="nginx" -K
```
