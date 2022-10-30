---
description: All in one IDS, Security Monitoring and Log Management.
---

# Security Onion Setup

NOTE:&#x20;

THIS WILL REQUIRE A VIRTUAL DRIVE OF 200GB

THE MORE MEMORY YOU CAN GIVE IT THE BETTER 4-32GB RAM

Add 2 adapters and assign them VMNet 4 and 5.

Download Security Onion here\
[https://github.com/Security-Onion-Solutions/securityonion/blob/master/VERIFY\_ISO.md](https://github.com/Security-Onion-Solutions/securityonion/blob/master/VERIFY\_ISO.md)

Enter the whole word yes when prompted,

Enter a username and password, don't forget them.

Q. Would you like to continue? Yes - Hit Enter.

Select Install, run the standard security onion installation

Select EVAL option

Type Agree

Select Standard.

Select OK.

Tap Space to select ens33 management NIC

Set the addressing to DHCP

Select YES

Select OK

Select Direct

Select ens35

Select Automatic

Accept default hone metwork IP

Accept all the defaults

Enter an email address and password for admin account, note it down.

Select IP - OK

Select Yes for NTP server, accept defaults

Take a screen shot.\
Most important setting is the IP address for web access.

Select Yes.

Now install Ubuntu Linux Desktop, this will be used as an external Desktop simulating a SOC/Security Analyst accessing a SIEM tool.

Run the Unbuntu setup open a terminal and run ip a (or ifconfig) and note down the ip address.

Back to Security Onion, open a terminal and type\
sudo so-allow, enter password.

Enter option a - Analyst.

Enter the Ubuntu ip address.

This allows you to access the internet from the Ubuntu VMachine.

Now navigate to Security Onion IP address on Ubuntu Desktop.

If all is well you should see the Security Onion Dashboard.

