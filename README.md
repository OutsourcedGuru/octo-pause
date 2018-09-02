# octo-pause
A Node.js-based service for pausing an OctoPrint printer locally

> **Node.js** is an open-source, cross-platform JavaScript run-time environment that executes JavaScript code server-side.
>
> **OctoPrint** is the leading web software for controlling 3D printers, created/maintained by Gina Häußge
>
> **OctoPi** is a Raspberry-specific distro of OctoPrint, maintained by Guy Sheffer

## Overview
This service runs in conjunction with the IFTTT-Dash-Button project. It's a simple GET endpoint which makes the call to the OctoPrint printer's REST interface.

## Installation
1. On the Raspberry Pi where the OctoPrint installation is located, install Node.js
2. `mkdir ~/sites && cd ~/sites`
3. `git clone https://github.com/OutsourcedGuru/octo-pause.git`
4. `cd octo-pause && npm install`
5. `chmod a+x octo-pause`
5. `./octo-pause`

You will likely want to make this startup persistently on bootup by adding it to rc.boot, for example.

--

|Description|Version|Author|Last Update|
|:---|:---|:---|:---|
|octo-pause|v1.0.1|OutsourcedGuru|September 2, 2018|

|Donate||Cryptocurrency|
|:-----:|---|:--------:|
| ![eth-receive](https://user-images.githubusercontent.com/15971213/40564950-932d4d10-601f-11e8-90f0-459f8b32f01c.png) || ![btc-receive](https://user-images.githubusercontent.com/15971213/40564971-a2826002-601f-11e8-8d5e-eeb35ab53300.png) |
|Ethereum||Bitcoin|
