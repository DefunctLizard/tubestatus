# London Tube
Access the London Tube lines status in real-time right from your terminal.

![tube-gif](https://i.imgur.com/TnAclV0.gif)

## Installation
### Dependencies
To run this script you will need to install [jq](https://stedolan.github.io/jq/download) 
- MacOS           `brew install jq`
- Ubuntu / Debian `apt-get install jq`
- Fedora          `dnf install jq"`
- openSUSE        `zipper install jq`
- Arch            `sudo pacman -Sy jq`
- BSD             `pkg install jq`
- Windows         `chocolatey install jq`
- Other OS        `https://stedolan.github.io/jq/download/`

## Install

```
make install 
```
or
```
cp src/alltubes /usr/local/bin/alltubes
chmod 755 /usr/local/bin/alltubes
cp src/tubestatus /usr/local/bin/tubestatus
chmod 775 /usr/local/bin/tubestatus
cp man/alltubes.man /usr/share/man/man1/alltubes.1
cp man/tubestatus.man /usr/share/man/man1/tubestatus.1
```
## Usage

London Tube is easy to use, just type `alltubes` to see every tube line and their status, or `tubestatus <tube line>` to see what status an individual tube's status is.

more info is available in the man page.
