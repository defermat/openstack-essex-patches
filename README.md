openstack-essex-patches
=======================

Various patches for Essex that is in between stable and trunk.

A lot of things are in the middle of changing in anticipation of the release of Folsom, however some bugs can be quickly hacked to be usable against Essex with little effort and significant gain.

The first patch in this repo will allow a current Essex build to launch multiple instances at the same time without them being spawned with the same instance name. See: https://bugs.launchpad.net/nova/+bug/1016200