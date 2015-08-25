# padevswitch

A small bash script for automatically switching between audio devices (not just ports) when headphones are plugged in/out in pulseaudio.

Configuration:
* headphones: Device to switch to when headphones are plugged in. List all devices by running `pacmd list-sinks | grep "name:"`.
* speakers: Device to switch to when headphones are plugged out.
