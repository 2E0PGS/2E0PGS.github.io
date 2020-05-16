---
title: Weather
description: My weather stations.
---

{% include main-template.md %}

# My weather stations

For a long time I had run a public website displaying my weather station data.

I ran this on a thinclient with [Cumulus](https://cumuluswiki.wxforum.net/a/Main_Page) software USB connected to the wireless display and FTP upload to my web server.

It generated static HTML pages with all the graphs as images and recent values as text.

It also generated a silverlight plugin for realtime wind speed, wind direction and outside temp.

The website was also useful because it allowed me to check the indoor temps. Useful when you have a few computers running in the middle of summer.

It also posted on [twitter.com/2E0PGSWX](https://twitter.com/2E0PGSWX) and ARPS aka CWOP however I don't know if the historical data is still around.

Recently using a Davis Weather Monitor II with serial to USB going into a PI 2B. Running [Weewx](http://weewx.com/) python and a custom driver called [wmII](https://github.com/jardiamj/wmII). Weewx also sends my 2E0PGS-WX APRS data.

Although I have some issues with noise getting into the serial line so it had to take it back offline as to avoid inaccurate data being posted.