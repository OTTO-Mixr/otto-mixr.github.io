---
layout: post
title: "It pours! Part 2 (What we've been up to)"
date: 2014-04-27 22:24:50 -0700
comments: true
categories: 
---

This update will be brief, but exciting. We've recently shifted our focus to the software side of OTTO. We're running a [MEAN stack](http://mean.io) server with [Johnny-five](https://github.com/rwaldron/johnny-five) controlling the Arduino. To make a long story short, OTTO is now at the point where we can press a button on the website to fire off the solenoids and the pump.
<!--more-->
Now, the really exciting part about all of this is that two weeks ago none of us knew anything about MEAN stack. Hell, I don't even think that we knew what those initials stand for (Mongo, Express, Angular, and Node in case you were wondering). We divided the project into frontend, backend, and database and had each person learn a part. Then, we shared what we learned amongst each other. This did the trick and now we have a working website. We still have a ways to go until it's totally polished, but we've got a solid foundation.

Finally, we've had some minor setbacks. As it turns out, the Raspberry Pi is not fast enough to run our server and communicate with the Arduino with the precise timing we need. After some searching we found the [BeagleBone Black](http://beagleboard.org/Products/BeagleBone+Black) which gave us a collective, massive BeagleBoner. The BBB is faster, has more GPIO slots than we know what to do with, and has recently been made compatible with johnny-five. Unfortunately that shit is so dial toned that we could not order it from a single goddamn place no matter how hard we looked. For now, we're just running the server from our laptops. This certainly works, but we hope to acquire a BBB to reduce the overall project size. We implore you to stay tuned as we'll be having a build weekend soon!
