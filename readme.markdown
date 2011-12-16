# Veewee Boxes

A collection (ok, only one at this time) of [veewee](https://github.com/jedi4ever/veewee) boxes.  

## Definitions

#### debian/debian-6.0.3-amd64

Ruby 1.8.7 is installed via packages instead of source. Rubygems is install
via source to get the latest stable version 1.8.12.  A newer version of
ruby wasn't installed because puppet will be used to setup rvm for each
user that requires ruby and gems. 

The VBoxGuestServices installed via the iso image are removed, and an
more udpate VBoxGuestServices is installed based on the current
VirtualBox version.

**Usage:**

    cd debian
    vagrant basebox build debian-6.0.3-amd64

This will download an iso image into the iso folder, if you haven't already
downloaded one.  After the basebox is built, you will receive
instructions to validate and export the box.  The validation will never
pass since Chef support has been removed.  The export process will
export the box into vagrant.  





