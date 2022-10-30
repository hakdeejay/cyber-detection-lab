# pfSense setup

Download pfSense community editon from \
[https://www.pfsense.org/download/](https://www.pfsense.org/download/)

Setup a VMachine as per Kali Setup.

pfSense will be used and configured as a firewall in a DMZ (De-militarized zone).

Once installed, start the VMachine and accept all defaults. pfSense will restart.

<figure><img src=".gitbook/assets/5 vmnet adapters.webp" alt=""><figcaption><p>Add 5 VMNet adapters to pfSense</p></figcaption></figure>

After reboot, setup pfSense as follows;\
Enter option 1.\
Q. Should VLAN's be set up now? A: N\
Q. Enter the WAN interface name or 'a' for auto-detection. A: em0\
Q. NOTE: this enables full Firewall/NAT Mode. A: em1

Q. Enter the optional 1 interface name or 'a' for auto-detection: A: em2\
Also repeat for em3, em4, em5.

Should now be setup as follows:\
WAN -> em0\
LAN -> em1\
OPT1 -> em2\
OPT2 -> em3\
OPT3 -> em4\
OPT4 -> em5

Q. Do you want to proceed. A: Y
