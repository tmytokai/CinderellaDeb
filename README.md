# CinderellaDeb

deb package of [Cinderella](https://cinderella.de/tiki-index.php) for ubuntu 16.04 and 18.04

# Installation

Download the latest deb package from [releases](https://github.com/tmytokai/CinderellaDeb/releases).
Then,

    $ sudo apt update
    $ sudo apt upgrade
    $ sudo apt install gdebi
    $ sudo gdebi cinderella_<version>_amd64.deb

* Cinderella is installed in /opt/cinderella

# SYNOPSIS

    $ cinderella [<file>.cdy]

# Uninstallation

    $ sudo dpkg -r cinderella
