# <!-- Home -->

[![DockSTARTer App Configurator](https://raw.githubusercontent.com/GhostWriters/DSAC.DockSTARTer.com/master/docs/img/logo.png)](https://dsac.dockstarter.com)

The main goal of DockSTARTer App Configurator (aka DSAC) is to make it quick and easy to get you running with some basic configurations.

You may choose to rely on DSAC for various changes to your Docker system, or use it as a stepping stone and learn to do more advanced configurations and connecting applications together.

## Getting Started

### System Requirements

- We maintain the same system requirement as [DockSTARTer](https://dockstarter.com/). You can find the [DockSTARTer System Requirements here](https://dockstarter.com/introduction/#system-requirements)

TL;DR:

- You must be running a [Supported platform](https://docs.docker.com/install/#supported-platforms) or an operating system based on a supported platform. Platforms named below will link to documentation listing compatible versions.
- You must be logged in as a non-root user with sudo permissions.

### One Time Setup (required)

- APT Systems ([Debian](https://docs.docker.com/install/linux/docker-ce/debian/#os-requirements), [Ubuntu](https://docs.docker.com/install/linux/docker-ce/ubuntu/#os-requirements), etc)

```bash
sudo apt-get install curl git
bash -c "$(curl -fsSL https://ghostwriters.github.io/DSAC/main.sh)"
sudo reboot
```

> Raspbian requires a few extra commands

```bash
sudo apt-get update
sudo apt-get dist-upgrade
sudo apt-get install curl git
bash -c "$(curl -fsSL https://get.docker.com)"
bash -c "$(curl -fsSL https://ghostwriters.github.io/DSAC/main.sh)"
sudo reboot
```

- DNF Systems ([Fedora](https://docs.docker.com/install/linux/docker-ce/fedora/#os-requirements))

```bash
sudo dnf install curl git
bash -c "$(curl -fsSL https://ghostwriters.github.io/DSAC/main.sh)"
sudo reboot
```

- YUM Systems ([CentOS](https://docs.docker.com/install/linux/docker-ce/centos/#os-requirements))

```bash
sudo yum install curl git
bash -c "$(curl -fsSL https://ghostwriters.github.io/DSAC/main.sh)"
sudo reboot
```

<details>
  <summary>Alternate install (any system)</summary>

The standard install above downloads the initial script using a method with some known risks. For those concerned with the security of the above method here is an alternative:

```bash
## NOTE: Run the appropriate command for your distro
sudo apt-get install curl git
sudo dnf install curl git
sudo yum install curl git

## NOTE: Do not sudo the next line.
git clone https://github.com/GhostWriters/DSAC.git "/home/${USER}/.dsac"
sudo bash /home/${USER}/.dsac/main.sh -vi
sudo reboot
```

</details>

### Running DSAC

```bash
sudo dsac
```

To run DSAC use the command above. You should now see the main menu.

See our [documentation](https://dsac.dockstarter.com/introduction/) for more detailed information.

## Support

[![Discord chat](https://img.shields.io/discord/477959324183035936.svg?style=flat-square&color=607D8B&logo=discord)](https://discord.gg/YFyJpmH)

Click the chat badge to join us on Discord for support!

[[Feature Request](https://github.com/GhostWriters/DSAC/issues/new?template=feature_request.md)] [[Bug Report](https://github.com/GhostWriters/DSAC/issues/new?template=bug_report.md)]

## Contributors

[![GitHub contributors](https://img.shields.io/github/contributors/GhostWriters/DSAC.svg?style=flat-square&color=607D8B)](https://github.com/GhostWriters/DSAC/graphs/contributors)

This project exists thanks to all the people who contribute!

## Special Thanks

- [[DockSTARTer](https://dockstarter.com/)] for providing a clean and simple way to get setup with Docker and a stepping stone for this project.
