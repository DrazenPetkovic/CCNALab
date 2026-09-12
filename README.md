# CCNALab
Comprehensive CCNA Exam Topics GNS3 Lab
The goal of this lab is to prepare for the CCNA certification. It covers many of the topics that 
can be tested on the CCNA exam. I recommend completing this exercise from start to finish on your own.
This repository contains my personal configuration to show how I approached and solved it.
Alongside this, you can complete another smaller lab to master the FHRP concept, which is not
included in this exercise.

The topics covered here include: static IP address configuration, VLANs, Trunking, EtherChannel,
SVIs, OSPF routing, DHCP, DNS, NAT, SSH and ACLs.

Troubleshooting Note:
During the lab configuration, I encountered a known bug specific to this Cisco IOS image in the
GNS3 environment. Upon restarting the devices, a duplex mismatch error occurs on the interfaces.
To mitigate this issue and maintain a stable topology state, the affected interfaces have been
temporarily put into an administratively down state (shutdown) on routers.
