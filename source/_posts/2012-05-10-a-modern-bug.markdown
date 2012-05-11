---
layout: post
title: "A Modern Bug"
date: 2012-05-10 18:34
comments: false
categories: [Etymology, Engineering, Storytime]
---

A few weeks ago, my mother-in-law made a terrifying discovery. Someone had been in her new point-of-sale system overnight. Several new screens had been opened since the day before. Fortunately, nothing appeared to have been changed, and no new charges inserted. Still -- pretty worrisome.

Maybe it was an intruder? She reviewed the security camera footage. It was blurry and a bit dark, but the computer was visible across the room. At around 8pm, the monitor suddenly brightened, and you could make out onscreen activity, but there was definitely no one present.

Perhaps it was a remote attack? She confirmed that the firewall was up and running, ran several different virus scans, and looked around for a Windows version of [Little Snitch](http://www.obdev.at/products/littlesnitch/index.html). The network looked pretty secure.

And yet, the next day, she found another slew of windows opened; the security footage was just as mysterious as before. The speculations got wilder. A ghost in the machine? Miniature earthquakes moving the mouse? A poltergeist? A software glitch?

It turned out to be a bug, but not a software bug. It was a teeny, tiny gnat.

Her new POS came with a very sensitive touch screen. Some time after dark, a gnat would fly near enough to the monitor to trigger a touch, waking the system up. The monitor brightened, drawing the gnat (and friends!) into a light-induced frenzy. They beat themselves against the glass, merrily opening windows and tapping buttons. And every culprit was smaller than a pixel in the security camera.

There may be debate about [the origin of the term bug in software engineering](http://en.wikipedia.org/wiki/Software_bug#Etymology), but the proud tradition of converting buggy atoms to buggy bits continues.

And now she turns off the system at night.
