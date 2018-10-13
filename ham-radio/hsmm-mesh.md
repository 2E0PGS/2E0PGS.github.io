---
title: HSMM-MESH
description: Ham Radio Mesh Networking
---

{% include main-template.md %}

# HSMM-MESH

## Sub pages

* [HSMM-MESH Help](/ham-radio/hsmm-mesh-help.html)

Bristol-Hamnet is a WI-FI mesh network for hamradio operators. The primary focus being experimentation, emergency communications and decentralisation.

The Bristol-Hamnet is based on the "Broadband-Hamnet" aka "HSMM-MESH" which was brought about by Americans. Some people in the UK have set up nodes for HSMM-MESH but there were none in Bristol, so we plan to change that.

We are using the [broadband-hamnet firmware](http://www.broadband-hamnet.org/) on Linksys devices and we are using the [Arden firmware](https://www.aredn.org/content/software) for our Ubiquiti devices.

We have a Bristol-Hamnet Facebook group: [​Facebook Group](​​https://www.facebook.com/groups/BristolHAMNET)

I highly suggest visiting the [broadband-hamnet website](http://www.broadband-hamnet.org/) for more info and reading up on what HSMM-MESH is all about in more detail. However here is a brief summary:

## What is HSMM-MESH?

>​​Broadband-Hamnet™ (formerly called HSMM-Mesh™) is a high speed, self discovering, self configuring, fault tolerant, wireless computer network that can run for days from a fully charged car battery, or indefinitely with the addition of a modest solar array or other supplemental power source. The focus is on emergency communications.

>In its current form it is built using the Linksys WRT54G/GL/GS wireless routers and operates on channels 1-6 of the 2.4GHz ISM band, which overlaps with the upper portion of the 13cm amateur radio band. Other platforms and bands include several types of Ubiquiti equipment in the 900MHz, 2.4GHz and 5.7GHz band. Additional features let signals come in on one band and leave on another without additional configuration. All mesh nodes on all bands exchange data so long as they are within range.

## Mesh status page archives

* [Mesh archive repository](https://bitbucket.org/2E0PGS/ham-radio-hsmm-mesh-archive)

## Node locations

### 2E0PGS-BULLET

* Status: ONLINE (24-7)
* Device: Ubiquiti Bullet M2
* Firmware: Arden
* Antenna: Beam vertical polarization pointing to G8KUW-1
* Services:
	* Overham_IRC: OFFLINE
	* IRC: OFFLINE
	* Chat Server with video: OFFLINE
	* IP Cam: OFFLINE
	* SIP Phone: 2011, 2013

### G7NSY-BULLET

* Status: OFFLINE
* Device: Ubiquiti Bullet M2
* Firmware: Arden
* Antenna: Beam vertical polarization pointing to MX0NBC-BULLET
* Services:
	* Weather Station: OFFLINE
	* OpenWebSDR: OFFLINE
	* GB3ZZ DATV Stream: OFFLINE
	* SIP Phone: 2021

### G8KUW-1

* Status: OFFLINE
* Device: Linksys WRT54G
* Firmware: ?
* Antenna: Beam vertical polarization pointing to 2E0PGS-BULLET
* Services:
	* MeshChat: ONLINE

### MX0NBC-BULLET

* Status: ONLINE (Fridays 7pm-11pm)
* Device: Ubiquiti Bullet M2
* Firmware: Arden
* Antenna: Beam vertical polarization pointing to G7NSY-BULLET
* Services:
	* IP Cam1: OFFLINE
	* IP Cam2: OFFLINE
	* SIP Phone: TBA
