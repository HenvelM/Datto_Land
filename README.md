# Datto Land

Collection of scripts made to automate repetitive tasks we get at work.

# Projects

- BSS Scan
- Auto Firmware Flash

## BSS Scan

Cleans up the scan done by iw dev on the APs, the list presented is followed by unecessary information and as well repeating MAC addresses. This script gets rid of repeating MACs and Interfaces that appear for the AP so that the outputted list is much more manageable and presentable for the partners.

To utilize this script just run curl -s (link)| sh -s --

## Auto Firmware Flash

This script can be used to automatically update the current AP to the desire version, reflash the current firmware, and as well perform a firmware reflash from another AP. The only required input depends on the tool being utilized, if performing a sysupgrade you have to input sysupgrade and the desired version. If performing a reflash to another AP you will input reflash, the desired version, the model of the AP, and the interface this is being done over.

 To utilize this script just run curl -s (link) | sh -s -- (sysupgrade or reflash) (7.X.XX or 6.X.XX) (AP Model*) (Interface*) 

* Used only with reflash

