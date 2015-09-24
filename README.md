Turn it Down!
=============

This is a _really basic_ OS X (Automator) app + Python script for @sarahmonster. It allows you to launch an App that enables/disables AirFoil + SONOS Line-in to emulator AirPlay in one action.

This works, but has no flexibility right now. I'd love for it to become a bit more robust.

## Installation

Right now you need ZSH installed. This is Automator's fault and I'll fix it.

```bash
pip install soco

# Run this from wherever you want to install turn-it-down... I put it in my
# ~/Projects folder.
git clone https://github.com/tofumatt/turn-it-down.git
cd turn-it-down

# Assumes you have a `/usr/local/bin`
ln -s $PWD/bin/turnitdown /usr/local/bin/turnitdown
```

Then run `AirPlay.app`. You can copy it to your /Applications folder if you like.

## Usage

Run `AirPlay.app`. If AirFoil is active it will disable it. Same goes for SONOS.

When you want to start your Spotify -> AirPlay -> SONOS session launch the Automator app. Once you're done, run it again and everything is back to normal. Nice!
