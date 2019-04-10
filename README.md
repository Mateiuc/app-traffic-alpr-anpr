# Sensorable Open Source Camera
### Road Traffic Analysis App with ALPR/ANPR

This repository contains files for a road traffic-specific app running on Sensorable cams. The app is an extension to [Sensorable Core App](https://github.com/sensorable/app-core). It is intended for OEM applications like embedding a Sensorable cam into a speed sign or a VMS as well as standalone use for traffic analysis.

## Main features

* vehicle detection
* interfacing with an external radar
* recording vehicle speed
* recording still images of vehicles
* recording videos of moving vehicles
* direction of movement
* lane isolation
* number plate detection and OCR
* ALPR/ANPR
* BLE link with a LED/VMS board

**[Demo video 1](https://sensorable.wistia.com/medias/vxbsbdorx8)**

**[Demo video 2](https://sensorable.wistia.com/medias/jino5ay4e3)**

The app is designed to run on extremely lower power (<4W, including the radar) and limited cellular bandwidth.

*Limitations:*

* No IR illumination is supported

*Supported radars*

The app can be modified to support any radar with an RS232 or USB interface. We have tested it with the following units:

* Houston-Radar DR1500, DR600, SS400
* AGD 331
* Chinese noname OEM


## Installation

The app is normally baked into the ROM and doesn't need to be installed separately. Once installed it gets updated to a required version from a cloud server.

---

**This repo is a placeholder.** No code has been committed yet.
We are in a process of cleaning it up and preparing for a public release. Check back soon or contact us on info@sensorable.io.
