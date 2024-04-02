# bpimon
This project utilizes a Raspberry Pi and an E-ink display to show near real-time simple internet bandwidth information using the Speedtest CLI Libary.


## Overview
This Bandwidth monitor will fetch internet speed metrics including download/upload speed, ping/latency and displays it on an E-ink display using a Python script and the Speedtest CLI libary.


## Image
![Image](https://github.com/zangaby/bpimon/blob/main/bpimon.png?raw=true)


## Requirements:
 - Raspberry Pi Zero W (You may choose an alternate compatable RaspberryPi model)
 - 40 Pin GPIO Solderless Hammer in Header for Raspberry Pi Zero (If not included with your RaspberryPi)
 - 8 GB Micro SD (Minimum: Samsung Evo Plus or Recomended: SanDisk Extreme Pro)
 - 250x122, 2.13inch E-Ink display HAT for Raspberry Pi (SKU: 12915)
 - Internet Connection
 - Python 3.x 


## Installation

#Clone This Repository
git clone https://github.com/SilentPSLLC/bpimon.git
cd bpimon

#Install required dependancies
pip install -r requirements.txt (COMING SOON)


## Usage
python bpimon.py


## Notes
- This project was originally designed for use with a 2.13 inch E-Ink display (Version 2). Adjustments may be necessary for other display sizes or versions.
- The modifications in this code are developed with a 2.13 inch E-Ink display (Version 3). Compatibility with other hardware configurations may vary.


## Contributors
- @zangaby (OriginalDeveloper...share some love to this guy. Withouthim this fork would not exist)
- @SilentPSLLC


## License
MIT License
