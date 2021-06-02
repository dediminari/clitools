# CLITools.tk
📦Useful scripts for CLI📦


[![License][license-shield]](LICENSE.md)

![Project Maintenance][maintenance-shield]
[![GitHub Activity][commits-shield]][commits]
[![Discord][discord-shield]][discord]
![Community Forum][forum-shield]

[![Github][github]][github]

<!-- 🎉 Release of CLITools 0.0.0 -->

### Features

-<--->-
<!-- also includes... -->


### Install Storjio-Storagenode on Debian/Ubuntu
Installs a Storjio-Storagenode on Debian/Ubuntu | Tested Ubuntu 20.04
* Download the [script](CLITools.tk/install-storjio)  
```wget -qO- CLITools.tk/install-storjio>install-storjio```
* Make the script executable and run it ```chmod +x install-storjio; ./install-storjio <email:characterstring> <LIVEPATCHTOKEN(optional)>```


### Install Speedtest.net CLI on Debian/Ubuntu/Fedora/CentOS/openSUSE Windows
Installs Speedtest.net CLI on Debian/Ubuntu/Fedora/CentOS Windows | Tested Ubuntu 20.04, Fedora, Windows 10
#### Linux:
```shell
wget -qO- https://raw.githubusercontent.com/marrobHD/clitools/master/install-speedtest-lnx>st.sh; chmod +x st.sh; ./st.sh
```
and
```shell
wget -qO- CLITools.tk/install-speedtest>st.sh; chmod +x st.sh; ./st.sh
```
or
```shell
wget -qO- CLITools.tk/install-speedtest-lnx | bash
```
#### Windows:
##### CMD:
```shell
powershell -C "start-process -verb runAs "powershell" -argumentlist ""/COMMAND set-executionpolicy remotesigned; wget https://raw.githubusercontent.com/marrobHD/clitools/master/install-speedtest -O speedtestcli.ps1; ./speedtestcli.ps1; set-executionpolicy default; echo exit"""
```
##### Admin PowerShell:
```shell
set-executionpolicy remotesigned; wget https://raw.githubusercontent.com/marrobHD/clitools/master/install-speedtest -O speedtestcli.ps1; ./speedtestcli.ps1; set-executionpolicy default
```
***Note:***
You may have to set the PowerShell execution-policy to remotesigned. Do it in admin PowerShell via:
```shell
set-executionpolicy remotesigned
```
After running the script you can go back to the default policy:
```shell
set-executionpolicy default
```


### Install Docker and Docker Compose on Debian/Ubuntu
Installs Docker Package CLI on Debian/Ubuntu | Tested Ubuntu 20.04
* Download the [script](CLITools.tk/install-docker) and run it  
```wget -qO- CLITools.tk/install-docker | bash```


### Fully uninstall Docker and Docker Compose on Debian/Ubuntu
Fully uninstalls Docker Package CLI on Debian/Ubuntu | Tested Ubuntu 20.04
* Download the [script](CLITools.tk/uninstall-docker) and run it  
```wget -qO- CLITools.tk/uninstall-docker | bash```


### Sources


Feel free to post issues and contribute!

## Authors & contributors

The original setup of this repository is by [Marlon][TechHome].

For a full list of all authors and contributors,
check [the contributor's page][contributors].



[Troubleshooting]()

[commits-shield]: https://img.shields.io/github/commit-activity/y/marrobHD/clitools.svg?style=for-the-badge
[commits]: https://github.com/marrobHD/clitools/commits/master
[discord]: https://discord.gg/ND4emRS
[discord-shield]: https://img.shields.io/discord/579704220970909717.svg?style=for-the-badge
[contributors]: https://github.com/marrobHD/clitools/graphs/contributors
[forum-shield]: https://img.shields.io/badge/community-forum-brightgreen.svg?style=for-the-badge
[license-shield]: https://img.shields.io/github/license/marrobHD/clitools.svg?style=for-the-badge
[maintenance-shield]: https://img.shields.io/badge/maintainer-TechHome-blue.svg?style=for-the-badge
[TechHome]: https://github.com/marrobHD
[releases-shield]: https://img.shields.io/github/release/marrobHD/clitools.svg?style=for-the-badge
[releases]: https://github.com/marrobHD/clitools/releases
[esphome]: https://esphome.io
[contributors]: https://github.com/hassio-addons/addon-ssh/graphs/contributors
[forum-shield]: https://img.shields.io/badge/community-forum-brightgreen.svg?style=for-the-badge
[license-shield]: https://img.shields.io/github/license/marrobHD/clitools.svg?style=for-the-badge
[maintenance-shield]: https://img.shields.io/badge/maintainer-Marlon-blue.svg?style=for-the-badge
[releases-shield]: https://img.shields.io/github/release/marrobHD/clitools.svg?style=for-the-badge
[releases]: https://github.com/marrobHD/clitools/releases
[github]: https://img.shields.io/github/followers/marrobHD.svg?style=social
