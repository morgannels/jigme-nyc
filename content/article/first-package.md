+++
date = "2018-04-04"
draft = true
publishdate = "2018-04-04"
title = "First Package"
description = "Publishing my first open source software, a Dart library"
tags = []

[amp]
    elements = ["amp-social-share"]

[structured]
    type = "Article"

[author]
    name = "Morgan Sandquist"

[sitemap]
  changefreq = "monthly"
  priority = 0.5
  filename = "sitemap.xml"

+++

I created [my first open source software](https://pub.dartlang.org/packages/internet_beats) package. I'd like to build a [Flutter](https://flutter.io/) mobile app (Android and iOS) that displays the time in Internet Beats. [Internet Beats](https://www.timeanddate.com/time/internettime.html) were invented about twenty years ago by Swatch, and offer a location-independent, zone-less method of telling time. It's sort of like UTC, but it breaks the day into 1,000 "beats," rather than hours, minutes, seconds, etc. Unsurprisingly, there's no library the manages time in Internet Beats, so I decided to write one as a first step.

This is a bit of a hack, in that I haven't created anything that keeps time in a fundamnetally different way. It merely takes a local or UTC time and algorithmically converts it. It depends on the system its run on to have the time set correctly. For most mobile devices, this probably isn't a stretch. And the way it's written, an app using the library could call a time service before using the library to be certain the time's right.