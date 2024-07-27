# Getting started
## Device Assembly
After acquiring (or milling and soldering) the Edgeberry Hardware, and 3D printing the Edgeberry enclosure, you're ready to assemble your device.

<p float="left">
  <img src="documentation/Edgeberry_assembly_1.png" width="32%" />
  <img src="documentation/Edgeberry_assembly_2.png" width="32%" />
  <img src="documentation/Edgeberry_assembly_3.png" width="32%" />
</p>
<p float="left">
</p>
<p float="left">
  <img src="documentation/Edgeberry_assembly_4.png" width="32%" />
  <img src="documentation/Edgeberry_assembly_5.png" width="32%" />
  <img src="documentation/Edgeberry_assembly_6.png" width="32%" />
</p>

## Raspberry Pi SD-card
We'll run Raspberry Pi's 'lite' version of Linux/Debian on the device. We'll download the image from Raspberry Pi's website, and use the Raspberry Pi Imager tool for writing the image to the SD-card.

```
1) Download the most recent Raspberry Pi OS Lite image from Raspberry Pi's website
https://www.raspberrypi.com/software/operating-systems/
2) Download the Raspberry Pi Imager tool
https://www.raspberrypi.com/software/
```

Use the Raspberry Pi Imager tool to configure the settings:
```
1) Setup your wireless network
2) Change the username and password
3) Enable SSH (for remote access using SSH)
4) Change the hostname (e.g. 'Edgeberry')
```
And write the image to the SD-card. When this process is ready, put the SD-card in the Raspberry Pi and power up the device.

## Access using SSH
When your device has booted, you can now access your Edgeberry device by opening a command line and running:
```
ssh <your username>@<your device IP address>
```
