---
description: Setup interface rules
---

# pfSense Interface Rules

Click Interfaces.

Select LAN.

Change description to Kali.

Scroll Down and click save.

Now repeat for all interfaces;

WAN -> em0.\
Kali ->   em1.\
VictimNetwork -> em2.\
SecOnion -> em3.\
SpanPort -> em4.\
Splunk -> em5.

OPT3 (remeber we left it) tick Enable interface.

Select Bridges.

Click Add.

Select VictimNetwork for Member Interfaces.

Select Advanced Config for SpanPort and for Span Port select Span Port.

Select Menu Option Firewall -> Rules.

Select add

Select 'edit firewall rule' for protocol select any.

scroll all the way down and save.
