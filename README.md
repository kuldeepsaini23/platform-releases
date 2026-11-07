# Platform releases

Release files and issue tracking for the Platform deployment service. The source code isn't here.

## Install

On a fresh Ubuntu 22.04, 24.04 or 26.04 x86 server with at least 4 GB of RAM and a public IPv4 address:

```sh
curl -fsSL https://github.com/kuldeepsaini23/platform-releases/releases/latest/download/install.sh | sudo bash
```

The installer ends by printing a one-time setup link. Keep it private.

## Releases

Each [release](https://github.com/kuldeepsaini23/platform-releases/releases) holds:

- `install.sh`: installs or upgrades the platform
- `platformd-linux-amd64.tar.gz`: the release itself
- `release.json` and `release.json.sig`: what the dashboard's update button reads, signed

## Issues

Report bugs in [Issues](https://github.com/kuldeepsaini23/platform-releases/issues). Issues are public: never paste passwords, API keys, tokens, setup links or a master key.
