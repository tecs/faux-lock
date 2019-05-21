# faux-lock
Catch people who try to mess with your "unlocked" computer

When executed, keeps your screen unlocked until someone tries to use your computer. When any user input is detected
(mouse movement, keyboard presses, etc.) the screen locks instantaneously and a picture of the culprit is taken using
the webcam. This picture is then set as your lock screen background for the whole office to marvel at.

## Requirements
* Gnome desktop environment (libglib2.0-bin)
* gnome-screensaver
* xprintidle
* ffmpeg
* imagemagick

## Usage
```
./faux-lock [debug] [bait]
    debug - writes the log to the screen instead of stdout
    bait  - disables system from locking until activated
```
