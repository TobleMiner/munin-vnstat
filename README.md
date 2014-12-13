munin-vnstat
============

A small munin vnstat plugin designed to work on OpenWrt devices with ash and a minimal vnstat installation.

At the time being it only shows the total accumulated traffic for a network interface. Might add some more functionality in the future though.

##Installation

You will need vnstat and sh/ash/bash both installed and configured to use this plugin.

Other than that there is not a whole lot of installation to do. Just rename the vnstat_ to vnstat_[interface] and copy it to your munin plugin folder. Upon the next munin graph update there should be a new graph in the network section of the munin interface.
