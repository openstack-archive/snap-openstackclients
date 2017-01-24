# OpenStack Clients Snap

This repository contains the source code of the snap for all OpenStack Client
tools.

## Installing this snap

The openstackclients snap can be installed directly from the snap store:

    sudo snap install --edge --classic openstackclients

then setup the aliases for all client tools (this will automatically happen at
some point in the future):

    ls -1 /snap/bin/openstackclients.* | cut -f 2 -d . | xargs sudo snap alias openstackclients

## Support

Please report any bugs related to this snap on
[Launchpad](https://bugs.launchpad.net/snap-openstackclients/+filebug).

Alternatively you can find the OpenStack Snap team in `#openstack-snaps`
on Freenode IRC.
