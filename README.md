# htpcpowermanager

Power manager script for shutdown and power up of htpc with videorecorder capacabilities.

A specialed daemon, build from the philosphy that power management is a dedicated task (e.g. should not be part of a package like kodi of tvheadend). The daemon monitors various activities on the system to decide whether the system can be powered off. Before poweroff the realtime clock is configured for the next startup. 
