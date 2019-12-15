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

I use APRSDroid on my Android phone which is a great tool for reporting my location, speed and altitude to [ARPS.FI](ARPS.FI) I normally use APRS when mobile in the car, on the bike or walking.

I also operate a APRS I-Gate which runs on a Raspberry PI B+ with a SDR dongle. This allows for a compact 24/7 local or portable setup.

I used to have my WX (Weather) Station on APRS but currently my Weather Station is broken.

## SSIDs

I try to follow the recommended [guidelines](http://www.aprs.org/aprs11/SSIDs.txt) for SSID assignment.

### Main callsign

| SSID      | Static? | TX type | Message capability? | Description                    |
|-----------|---------|---------|---------------------|--------------------------------|
| 2E0PGS    | Yes     | DPRS    | Unknown             | Main home base station radio   |
| 2E0PGS-5  | No      | TCPIP   | Send and recieve    | Mobile with my backup phone    |
| 2E0PGS-7  | No      | DPRS    | Unknown             | Mobile with a hand held        |
| 2E0PGS-8  | No      | FM      | None                | Mobile with AVRT5              |
| 2E0PGS-9  | No      | TCPIP   | Send and recieve    | Mobile with my main phone      |
| 2E0PGS-10 | Yes     | TCPIP   | Passthrough         | APRS I-Gate                    |
| 2E0PGS-B  | Yes     | TCPIP   | Passthrough         | D-Star hotspot and DPRS I-Gate |
| 2E0PGS-WX | Yes     | TCPIP   | None                | Home weather station           |

### Secondary callsign

| SSID     | Static? | TX type | Message capability? | Description            |
|----------|---------|---------|---------------------|------------------------|
| M3PGS-10 | Yes     | TCPIP   | Passthrough         | APRS I-Gate            |
| M3PGS-WX | Yes     | TCPIP   | None                | Second weather station |

### Other

| SSID  | Static? | TX type | Message capability? | Description                                        |
|-------|---------|---------|---------------------|----------------------------------------------------|
| GB3AC | Yes     | TCPIP   | None                | UHF FM voice repeater http://www.sgrepeaters.co.uk |

You can see my nodes on this map view of Bristol via [aprs.fi](https://aprs.fi/#!mt=roadmap&z=11&lat=51.4829&lng=-2.6549&timerange=3600) or via the below embedded map:

{% include aprs-fi-map.html %}
