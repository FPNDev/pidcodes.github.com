---
layout: pid
title: WPods Virtual Microphone
owner: fpndev
license: GPL-3.0
site: https://github.com/FPNDev/wpods
source: https://github.com/FPNDev/wpods
---
A virtual USB Audio Class 1 microphone (mono, 48 kHz, 16-bit) presented by WPods, an open-source Windows app for Apple AirPods. The device exists only in software: the WPods background service serves it over USB/IP on the local machine to the usbip-win2 virtual host controller, and Windows runs it with its in-box USB audio driver. It carries the AirPods microphone audio that WPods receives over Bluetooth, so apps can record it while Windows keeps stereo (A2DP) playback.
