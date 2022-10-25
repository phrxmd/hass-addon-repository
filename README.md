# phrxmd's fork of Nicholas' Home Assistant Addon Repository

## CUPS Addon

A CUPS server with a variety of included drivers, USB support, support for the Home Assistant installation's TLS certificate, and mDNS broadcasting enabled.

Logins are disabled from the local network, but the web UI from within Home Assistant is automatically authenticated

cupsd.conf and Dockerfile modified from https://github.com/lemariva/wifi-cups-server

Some of the Avahi and D-Bus code is modified from https://github.com/marthoc/docker-homeseer

Added packages over Nicholas' own version:

- [this driver](https://github.com/philpem/printer-driver-ptouch) for the Brother PTouch series of label printer
