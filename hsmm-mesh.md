---
title: HSMM-MESH
description: Ham Radio Mesh Networking
---

{% include main-template.md %}

# HSMM-MESH

### Sub Pages

* [HSMM-MESH Help](/hsmm-mesh-help.html)

Bristol-Hamnet is a WI-FI mesh network for hamradio operators.

The Bristol-Hamnet is based on the "Broadband-Hamnet" aka "HSMM-MESH" which was brought about by Americans. Some people in the UK have setup nodes for HSMM-MESH but there is none in Bristol, so we plan to change that.

We are using the firmware developed by the guys over at: [http://www.broadband-hamnet.org/](http://www.broadband-hamnet.org/)

I highly suggest visiting their website for more info and reading up on what HSMM-MESH is all about in more detail.

[​Facebook Group](​​https://www.facebook.com/groups/BristolHAMNET)

### What is HSMM-MESH?

>​​Broadband-Hamnet™ (formerly called HSMM-Mesh™) is a high speed, self discovering, self configuring, fault tolerant, wireless computer network that can run for days from a fully charged car battery, or indefinitely with the addition of a modest solar array or other supplemental power source. The focus is on emergency communications.

>In its current form it is built using the Linksys WRT54G/GL/GS wireless routers and operates on channels 1-6 of the 2.4GHz ISM band, which overlaps with the upper portion of the 13cm amateur radio band. Other platforms and bands include several types of Ubiquiti equipment in the 900MHz, 2.4GHz and 5.7GHz band. Additional features let signals come in on one band and leave on another without additional configuration. All mesh nodes on all bands exchange data so long as they are within range.

### Node locations

#### 2E0PGS-BULLET

* Status: ONLINE
* Device: Ubiquiti Bullet M2
* Antenna: Beam vertical polarization pointing to G8KUW-1
* Services:
	* Overham_IRC: OFFLINE
	* IRC: OFFLINE
	* Chat Server with video: OFFLINE
	* IP Cam: OFFLINE
	* SIP Phone: 2011, 2013

#### G7NSY-BULLET

* Status: ONLINE
* Device: Ubiquiti Bullet M2
* Antenna: Beam vertical polarization pointing to MX0NBC-BULLET
* Services:
	* Weather Station: OFFLINE
	* OpenWebSDR: OFFLINE
	* GB3ZZ DATV Stream: OFFLINE
	* SIP Phone: 2021

#### G8KUW-1

* Status: ONLINE
* Device: Linksys WRT54G
* Antenna: Beam vertical polarization pointing to 2E0PGS-BULLET
* Services:
	* MeshChat: ONLINE

#### MX0NBC-BULLET

* Status: ONLINE
* Device: Ubiquiti Bullet M2
* Antenna: Beam vertical polarization pointing to G7NSY-BULLET
* Services:
	* IP Cam1: OFFLINE
	* IP Cam2: OFFLINE
	* SIP Phone: TBA
