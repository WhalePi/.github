# WhalePi

## Introduction

WhalePi is a series of repositories containing [PAMGuard](www.pamguard.org) plugins that are used with [RaspberryPi](https://www.raspberrypi.com/) devices to run PAMGuard in real time as a data collection and real-time analysis system. While PAMGuard can run on a Raspberry Pi 4/5 as a full desktop program with almost all functionality in both real-time and post-processing mode, it can also be run headless on much lower-powered RPi devices, such as the Raspberry Pi Zero 2 W. This allows PAMGuard to form the basis of an autonomous data collection device which can record sound files and/or perform real-time data analysis and summary tasks.

## Capabilities 

The repositories are mostly individual plugins that add RaspberryPi (sometimes just Linux) specific functionaility. These include 

- Ability to record processor temperature.
- Add Bluetooth connectivity so PAMGuard can be controlled from a phone/tablet/comnputer.
- Ability to read 12C data from ADC boards (e.g. to read depth sensor data).
- A phone app for passing PAMGuard commands to the RaspberryPi

## WhalePi autonomous recorder

The WhalePi autonomous recorder uses a Raspberry Pi Zero running PAMGuard and connected to a COSMOS soundcard. It has a high dynamic range (24-bit recordings) and records on two channels at a 384 kHz sample rate. The Raspberry Pi Zero is supplied with a 1TB SD card, and data are compressed to .sud files (effectively providing 4TB of storage, or ~20 days). Because PAMGuard is modular and highly flexible, it can also be run in different configurations—for example, running a click detector and long-term spectral average instead of saving sound files, meaning storage would last years.

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->

## Getting started
The first port of call is the [install_whalepi](https://github.com/WhalePi/install_whalepi) repository. It provides releases of the firmware and comprehensive instructions on how to get started. 
