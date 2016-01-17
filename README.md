Porter
=========

<img src="https://github.com/lanewinfield/porter/blob/master/porter.png" width="400px" />

*(See it in action [here](http://gfycat.com/SpeedyAlertDrake))*

**A dashboard meant for raspberry pi + touchscreen to have an at-a-glance view of data for the home.**

Features
---------

* Upcoming (24 hour) weather, scrollable and inspired by the wonderful design of [Weather Line](http://weatherlineapp.com/).
* Alerts when precipitation is forecast within the hour (à la Dark Sky)
* Light control (using my own API... hope to set this up soon)
* Nearest Uber-X status
* Nearest Car2Go status with toggleable map
* NYC subway alerts
* "Should I bring my umbrella?" alert
* The current time


Prerequisites
---------

This was all built exactly to the spec of the [Official Raspberry Pi Display](https://www.raspberrypi.org/blog/the-eagerly-awaited-raspberry-pi-display/). I'm hardcoding a lot of the resolutions in here just for that, so be warned.

I run it on a RPI2.


Installation
---------

Run `sudo git clone https://github.com/Shugabuga/PorterInstall.git && sudo sh porter.sh` with a full Raspbian install to install.

Warnings
---------

* *This code sucks.* I'm pretty rusty when it comes to JS (or any language at that matter) and have been so busy adding that I haven't even considered refactoring.

* *Some things only work for me.* Light control is using my own API (I hope to OS that soon, too) and the subway information is currently NYC only.
