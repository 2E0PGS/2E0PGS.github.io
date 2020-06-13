---
title: APRS
description: Amateur Radio Packet Reporting System
---

{% include main-template.md %}

# APRS

Automatic Packet Reporting System (APRS) is an amateur radio based system for real time data communication of location reporting and messaging.

More info at:

* [APRS.FI](APRS.FI)
* [APRS.ORG](APRS.ORG)
* [APRSDROID.ORG](APRSDROID.ORG)

~~I use APRSDroid on my Android phone which is a great tool for reporting my location, speed and altitude to [ARPS.FI](ARPS.FI) I normally use APRS when mobile in the car, on the bike or walking.~~

I use [aprs-cli](https://bitbucket.org/2E0PGS/aprs-cli) written by me on my Android phone almost 24/7.

~~I also operate a APRS iGate which runs on a Raspberry PI B+ with a SDR dongle. This allows for a compact 24/7 local or portable setup.~~

I operate a 24/7 local APRS iGate on a VMWare virtual machine with usb pass-through of a RTL SDR dongle. See: [2020/06/13/pymultimonaprs-sdr](https://2e0pgs.github.io/blog/hamradio/2020/06/13/pymultimonaprs-sdr/)

I used to have my WX (Weather Station) on APRS see: [Weather](../extra/weather.html)

## SSIDs

I try to follow the recommended [guidelines](http://www.aprs.org/aprs11/SSIDs.txt) for SSID assignment.

### Main callsign

| SSID                                          | Static? | RX type | TX type | Message capability? | Description                                                     |
|-----------------------------------------------|---------|---------|---------|---------------------|-----------------------------------------------------------------|
| [2E0PGS](https://aprs.fi/info/a/2E0PGS)       | Yes     | Unknown | DPRS    | Unknown             | IC-7100                                                         |
| [2E0PGS-1](https://aprs.fi/info/a/2E0PGS-1)   | No      | None    | TCPIP   | None                | [aprs-cli](https://bitbucket.org/2E0PGS/aprs-cli) on main phone |
| [2E0PGS-6](http://www.ariss.net/)             | Yes     | FM      | FM      | Unknown             | Satellite DX                                                    |
| [2E0PGS-7](https://aprs.fi/info/a/2E0PGS-7)   | No      | Unknown | DPRS    | Unknown             | ID-51A Plus 2                                                   |
| [2E0PGS-8](https://aprs.fi/info/a/2E0PGS-8)   | No      | None    | FM      | None                | AVRT5                                                           |
| [2E0PGS-9](https://aprs.fi/info/a/2E0PGS-9)   | No      | TCPIP   | TCPIP   | Send and receive    | [APRSdroid](https://aprsdroid.org/) on second phone             |
| [2E0PGS-10](https://aprs.fi/info/a/2E0PGS-10) | Yes     | FM      | TCPIP   | Passthrough         | APRS iGate                                                      |
| [2E0PGS-B](https://aprs.fi/info/a/2E0PGS-B)   | Yes     | DPRS    | TCPIP   | Passthrough         | D-Star hotspot and DPRS iGate                                   |
| [2E0PGS-WX](https://aprs.fi/info/a/2E0PGS-WX) | Yes     | None    | TCPIP   | None                | Home weather station                                            |

### Secondary callsign

| SSID     | Static? | TX type | Message capability? | Description            |
|----------|---------|---------|---------------------|------------------------|
| M3PGS-10 | Yes     | TCPIP   | Passthrough         | APRS iGate             |
| M3PGS-WX | Yes     | TCPIP   | None                | Second weather station |

### Other

| SSID  | Static? | TX type | Message capability? | Description                                        |
|-------|---------|---------|---------------------|----------------------------------------------------|
| GB3AC | Yes     | TCPIP   | None                | UHF FM voice repeater http://www.sgrepeaters.co.uk |

You can see my nodes on this map view of Bristol via [aprs.fi](https://aprs.fi/#!mt=roadmap&z=11&lat=51.4829&lng=-2.6549&timerange=3600) or via the below embedded map:

{% include aprs-fi-map.html %}
