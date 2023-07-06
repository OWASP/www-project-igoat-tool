---

layout: col-sidebar
title: OWASP iGoat Tool
tags: igoat
level: 2
type: tool

---
## OWASP iGoat - A Learning Tool for iOS App Pentesting and Security [![Twitter Follow](https://img.shields.io/twitter/follow/espadrine.svg?style=social&label=Follow)](https://twitter.com/OWASPiGoat/)

iGoat is a learning tool for iOS developers (iPhone, iPad, etc.) and mobile app pentesters. It was inspired by the WebGoat project, and has a similar conceptual flow to it.

As such, iGoat is a safe environment where iOS developers can learn about the major security pitfalls they face as well as how to avoid them. It is made up of a series of lessons that each teach a single (but vital) security lesson.

### The lessons are laid out in the following steps: ###

1. Brief introduction to the problem.
1. Verify the problem by exploiting it.
1. Brief description of available remediations to the problem.
1. Fix the problem by correcting and rebuilding the iGoat program.

Step 4 is optional, but highly recommended for all iOS developers. Assistance is available within iGoat if you don't know how to fix a specific problem.

## OWASP iGoat (Swift) - A Damn Vulnerable Swift Application for iOS [![Twitter Follow](https://img.shields.io/twitter/follow/espadrine.svg?style=social&label=Follow)](https://twitter.com/OWASPiGoat/)

__Vulnerabilities Covered (version 1.0):__ [![Download iGoat](https://img.shields.io/badge/Download-iGoat-orange.svg)](https://codeload.github.com/OWASP/iGoat-Swift/zip/master) Documentation: https://docs.igoatapp.com/

<img src="https://github.com/swaroopsy/test/blob/master/h1.gif?raw=true" width="256" title="iGoat App">

__Documentation:__ <a href="https://github.com/OWASP/iGoat-Swift/wiki">iGoat Wiki</a>

__iGoat Quick Setup__ `git clone https://github.com/OWASP/iGoat-Swift.git`and open iGoat-Swift.xcodeproj with xcode.
__Setup iGoat Server__ Navigate to server > docker_packaging and then use command `docker compose up` <br>
__Using Cydia Repo__ - Open Cydia -> Sources -> Edit and add source http://swiftigoat.yourepo.com/ and then search for iGoat and install it.

__Project Lead__ - Swaroop Yermalkar [![Twitter Follow](https://img.shields.io/twitter/follow/espadrine.svg?style=social&label=Follow)](https://twitter.com/swaroopsy)

## Architecture
![Architecture](https://github.com/swaroopsy/test/blob/master/Architecture.png?raw=true)


