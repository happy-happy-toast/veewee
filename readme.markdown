# Veewee Boxes

A collection (ok, only one at this time) of [Veewee](https://github.com/jedi4ever/veewee) boxes.  

## Definitions

#### debian/debian-6.0.3-amd64

Ruby is installed via packages instead of source. Rubygems is install
via source to get the latest stable version 1.8.12.

The VBoxGuestServices installed via the iso image are removed, and an
more udpate VBoxGuestServices is installed based on the current
VirtualBox version.

Usage:
    cd debian
    vagrant basebox build debian-6.0.3-amd64





