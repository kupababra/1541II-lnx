Project: Copying C64 Floppy Disks on Linux OPenCBM + XUM1541

## Project Description

The project aims to enable the 1541 II floppy drive (compatible with Commodore 64 computers) to run on Linux.

This will allow users to read, write, and copy data from C64 floppy disks on Linux/BSD systems using tools such as OpenCBM and a dedicated program that works with OpenCBM.

According to the official OpenCBM website, this drive doesn't appear to be functional, so I had to create a program to help get it running. ;-)

## Requirements

- **Linux** (preferred distribution: Debian, Gentoo, Slackware)
- **OpenCBM** - a program for communicating with Commodore 64 computers
- **My Program** - an additional program that works with OpenCBM, allowing easy operation of the 1541 II disk drive on Linux
- **XUM 1541 Interface** + USB cable

### Required Dependencies:

- `openCBM` (in a version compatible with your system)
- `libusb` (if using a USB-connected device)
- `gcc` and other compilation tools (if you need to compile OpenCBM)
- `My Program` (an additional program that works with OpenCBM)

## Installation

### 1. Installing OpenCBM

To install OpenCBM on Linux, follow the steps below:

#### a. Installation From system repositories (if available)

On Debian/Ubuntu-based systems:

```bash
sudo apt update
sudo apt install opencbm

On RedHat/Fedora-based systems:

sudo dnf install opencbm

b. Installing from source code

If OpenCBM is not available in the repositories, you can download the source code and build it manually:

git clone https://github.com/Dirk-Matthies/OpenCBM.git
cd OpenCBM
make
sudo make install

The rest will be here soon. Best regards, bofh@retro cdn ...
