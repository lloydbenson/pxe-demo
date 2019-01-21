# pxe-demo instructions

## In order to setup the pxe server do the following.

1.  Install Fedora 29 server

1.  Setup a static IP for your network (e.g. 192.168.1.2 with router/gw 192.168.1.1)

1.  Setup an admin user that has sudo privs

1.  ssh as admin user

1.  sudo dnf install git ansible sshpass python

1.  git clone http://github.com/lloydbenson/pxe-demo

1.  ./setup.sh
