# Ubuntu-20.10-no-audio-Dummy-output-
How I fixed   no audio "Dummy output" on Ubuntu 20.10 - Lenovo P14s
On Ubuntu 20.10 minimal install. I noticed no-audio and output was set to Dummy output. 
Fortunately the fix was straight forward:

$ sudo apt-get install --reinstall alsa-base pulseaudio

$ sudo alsa force-reload
