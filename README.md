# GKRControl

Control suite for GonKiRin's lighting

includes max patches, touchOSC iphone layout

# Software

It's recommended to use Windows 10. In theory macOS should work if you get a license for dmxusbpro.

## Max
Use a 32-bit version of Max MSP. Version 7.2.5 is known to work:

https://cycling74.com/downloads
https://akiaj5esl75o5wbdcv2a-maxmspjitter.s3.amazonaws.com/Max725_x86_160915.zip

## Dmxusbpro

Use version 1.4.1:

http://www.nullmedium.de/dev/dmxusbpro/

It's EUR10 to download it, so find the local copy that is on the show laptop

## FTDI drivers

Dmxusbpro needs the VCP driver, in order to communicate with the Enttec DMX USB Pro:

http://www.ftdichip.com/Drivers/VCP.htm

## (optional) Enttec Pro Manager

This tool is not needed for the show, but can help in testing that the DMX system is working properly:

https://www.enttec.com/us/products/controls/dmx-usb/pro-manager/

# Setup

## DMX components

- First, install the software. Note that you'll need a network connection to authorize Max- plan ahead.
- Connect the enttec device to the PC using an available USB port
- Open max and run the patch 'elpasohost'.
- If this is a new computer, or the Enttec configuration has changed, you may need to adjust the serial port. Go into edit mode (ctrl+e) and then patching mode (ctrl+alt+e), and find the textbox that says 'loadmess open COM4'. Use the Windows Device Manager to find the correct COM port for the Enttec, and update it's value in the text box. You may need to restart Max to apply the changes.
- At this point the software should work

## iPad/iPhone Control

- Download touchOSC Editor to load the layout onto the device: https://hexler.net/software/touchosc
- Also, get touchOSC from the app store or google play store (paid)
- Connect the PC and the mobile device to the same network
- Next you'll need to install java.. good luck from there.

## Digital LEDs

- Coming soon!
