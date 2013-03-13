Raspberry Pi internet radio project
===================================

An Internet radio built around a Raspberry Pi, using Last.Fm for users who cannot access Pandora
due to not living in the US.

The project currently uses shell-fm (https://github.com/jkramer/shell-fm) to serve music, and GPIO
button control is enabled by the daemon pikeyd (https://github.com/mmoller2k/pikeyd). 

Currently the script runs on boot and gpio button control enables play/pause, skip , 'loving' tracks and
spoken information about the currently playing track via espeak.
