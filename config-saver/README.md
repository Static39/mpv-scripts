# config-saver

A simple script to save the current audio track, sub track, sub position, etc to the current folder.

## Usage

* In your `mpv.conf` file add the line `osc=no`.
* Keep all the video files you want the configuration to persist on in a single folder.
* Adjust audio/subtitles to the desired settings.
* Click the floppy disk icon on the overlay to save configuration (or press F1).
  A `.conf` file will be written to the folder with the configuration details.

## Notes

This script currently saves:
* Audio track
* Subtitle track
* Subtitle postition
* Subtitle size
* Subtitle ASS override

On account of the fact that this adds elements to the OSC the entire OSC is contained within this script.
If you have other OSC scripts you would have to move the code for saving the configuration and put it in your scripts.
