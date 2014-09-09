foreman-plugin-autobmc
======================

A Foreman plugin to make forman automatically detect BMC interfaces for servers
that have them.

## Requirements ##

This plugin relies on Facter to do the actual detection of the BMC interfaces,
you will need the [bmclib](https://github.com/logicminds/bmclib) Puppet module.

