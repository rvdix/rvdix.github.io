---
layout: post
title: Macro Keypad Build
---

A friend the other day told me about a keypad that he wanted to use to setup macros for his Blender projects that he was working on. I told him that I would be able to build him one to his specifications if he wanted me to. He said that sounded go and so I went ahead with the build. 

For this build I was able to find someone who had already designed a [similar project](https://github.com/KikiHobbyRepair/Macro-Keyboard). After looking it over, I decided that this was the design that I would go with. I took to printing out the .STLs that were provided on my Anycubic Mega S. A quick print and it all came together relatively easy. 

[<img src="{{ site.baseurl }}/images/3d_printer.jpg" style="width: 400px;"/>]({{ site.baseurl }}/)

For the keys, I decided to go with Kailh Black Keys which were very economical. After fitting everything together, I wired it up to my microcontroller and was all set to go. Only issue was that the original creator of the macro keypad used an arduino to run his keypad. All I had laying around was an Raspberry Pi Pico, but that should've been easy to fix. 

Using Adafruit's HID library for CircuitPython, I was able to write my own code to set-up the device for my friend. And with that the device is ready to go for use with Blender!