# Portefaix Vault

* Master :
[![Circle CI](https://circleci.com/gh/portefaix/docker-vault/tree/master.svg?style=svg)](https://circleci.com/gh/portefaix/docker-vault/tree/master)

* Develop :
[![Circle CI](https://circleci.com/gh/portefaix/docker-vault/tree/develop.svg?style=svg)](https://circleci.com/gh/portefaix/docker-vault/tree/develop)

![logo](https://raw.githubusercontent.com/1science/docker-alpine/latest/logo.png)

[Alpine Linux][] is a Linux distribution built around musl libc and BusyBox.
This image is based on the official Alpine Linux.

[Vault][] is an open-source tool for securely accessing secrets.

Ports exported is : `8200`.

Volume exported is : `/etc/vault.hcl`.

## Usage

    $ docker run --rm=true -it -p 8083:8083 -p 8086:8086 portefaix/vault:0.9.4

## Supported tags

- `0.4.0` [![](https://badge.imagelayers.io/portefaix/vault:0.4.0.svg)](https://imagelayers.io/?images=portefaix/vault:0.4.0 'imagelayers.io')

## License

See [LICENSE](LICENSE) for the complete license.


## Changelog

A [ChangeLog.md](ChangeLog.md) is available.


## Contact

Nicolas Lamirault <nicolas.lamirault@gmail.com>


[Alpine Linux]: http://www.alpinelinux.org

[Vault]: https://github.com/hashicorp/vault/
