# RPi for David Tudor's Rainforest

## References
* [supercolliderStandaloneRPI2](https://github.com/redFrik/supercolliderStandaloneRPI2)
* [Writing, Backing Up, and Cloning Raspbian (RPi) Images](https://gist.github.com/caseyanderson/31b615045332a6ab3f4028c696920f57#write-img-from-rpi-foundation)


## Materials
* Raspberry Pi
* MicroSD Card (class 10, 8GB or larger)
* Power Supply
* (Optional) USB Audio Adapter ([this](https://www.adafruit.com/product/1475) one is fine)


## Installation Procedure
1. Download `Raspbian Stretch Lite` from the Raspberry Pi Foundation [here](https://downloads.raspberrypi.org/raspbian_lite/images/raspbian_lite-2019-04-09/2019-04-08-raspbian-stretch-lite.zip) (**note**: `Raspbian Buster Lite` **does not currently work with this standalone**, it will be fixed when SC `3.10.3` is released (soon))
2. Follow the instructions [here](https://gist.github.com/caseyanderson/31b615045332a6ab3f4028c696920f57#pre-flight) to write the `.img` to your `Micro SD` card
3. Insert Micro SD card into RPi, boot it up, and run the `raspi-config` tool. At a minimum one should:
    1. change the password
    2. enter WIFI credentials
    3. enable `ssh`
4. Build SC Standalone for `Raspbian Stretch Lite` following Fredrik's instructions [here](https://github.com/redFrik/supercolliderStandaloneRPI2) (in two parts):
    1. general installation instructions [here](https://github.com/redFrik/supercolliderStandaloneRPI2#installation) **note**: you will need to also install `git` to clone the standalone repo: `sudo apt-get install git`
    2. lite-specific installation instructions [here](https://github.com/redFrik/supercolliderStandaloneRPI2#stretch-lite)
5.
