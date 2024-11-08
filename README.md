# skimjob

Official README for the SkimJob project

<p align="center"> 
    <img src="https://github.com/WhiteOakSecurity/SkimJob/blob/main/Documentation/skimjob_photo.png?raw=true" alt="alternate text">
    <img src="https://github.com/WhiteOakSecurity/SkimJob/blob/main/Documentation/skimjob_photo2.png?raw=true" alt="alternate text">
</p> 

## Description & Purpose
This is the SkimJob project. An all-inclusive RFID skimming toolset.

The SkimJob toolset is to be used to skim RFID cards (specifically HID brand). This toolset allows the user to overlay building RFID readers without damaging the reader. 

## Features
 - Open Source (Python)
 - Non-damaging overlay
 - Battery operated
 - Publicly available components

 ## Documentation
 - [Schematic design](https://github.com/WhiteOakSecurity/SkimJob/blob/main/Documentation/skimjob_schematic.jpg?raw=true)
 - [Component list](https://github.com/WhiteOakSecurity/SkimJob/blob/main/Documentation/Component%20List.md)
 - [Slide deck](https://www.slideshare.net/BrettDeWall/skim-job-presentation)
 - [Video overview](https://youtube.com/watch?v=_tIybfiVPUA) 
 - Blog Post (Future link)
 - Recorded presentation (Future link)

## Requirements
- Python3
- [Proxmark3](https://github.com/Proxmark/proxmark3)
- Raspberry Pi Zero (configured to setup WiFi network on boot - refer [here](https://www.raspberryconnect.com/projects/65-raspberrypi-hotspot-accesspoints/168-raspberry-pi-hotspot-access-point-dhcpcd-method) for setup)
- Soldering skills (Need to solder various components together)

 ## Installation
`git clone <REPO>` <br>
`cd .\skimjob` <br>
`pip3 install -r requirements`

## Usage
`python3 skimjob.py`

## Future Updates
- SkimServer (Automated web server allowing for the creation, cloning, and replication of RFID cards from a simple web interface)
    - Application start
    - Log viewer
    - RFID simulate
    - RFID clone
- Add LED lights to simulate RFID read functionality

## Presentations
- 2021 Minnesota Secure360
- 2021 GrrCON

## Thanks
- @ech0bit
- @OctetStream
- @DonQuixote651
- Sleestakoverflow

## Credits
- Proxmark3 Community
- Fritzing Community
