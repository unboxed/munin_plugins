
These are some munin plugins to monitor a Netgear ReadyNAS.  They have been developed against a ReadyNAS 1100, but they should work with other versions.

`raidar__readynas_temps`

This generates a graph of the system and disk temperatures in the device.  It follows the snmp paradigm, whereby the hostname to monitor should be inserted between the underscores when symlinking.

`snmp__readynas_df`

This generated a graph of the disk usage in percent.  It uses the standard SNMP MIB's, but only graphs filesystems with a type of 'hrStorageFixedDisk', and with a size greater than 0.
