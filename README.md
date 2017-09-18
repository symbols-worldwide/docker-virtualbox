# Virtualbox for Docker

This is a simple Debian container with Virtalbox installed.

Virtualbox modules and services need to be installed and running on your host.

VT-x will be required if using this image on a VM. In order to use Virtualbox
this container must be run with the `--privileged` and `--net=host` parameters.
Please be aware of the security implications of this.

# TODO:

Find a way to make this installer by not having to install X.

