# ZenPacks.daviswr.UCD.HardDisk

ZenPack to monitor activity on HardDisk components modeled by zenoss.snmp.UCDHardDiskMap using UCD-DISKIO-MIB

The block device load average OIDs (diskIOLA*n*) require Net-SNMP 5.5 or newer on the target host, and Linux distributions based on Debian 8 and Enterprise Linux 6 (or newer) are known to work.

Activity and throughput metrics will still work on older releases.

Requires [ZenPackLib](https://help.zenoss.com/in/zenpack-catalog/open-source/zenpacklib)

## Usage

This doesn't (yet) modify modeler plugins on any device class like /Server/Linux, so it's up to you to apply the `zenoss.snmp.UCDHardDiskMap` modeler on the appropriate class or device.
