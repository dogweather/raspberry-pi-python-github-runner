# A Python self-hosted GitHub Runner for the Raspberry Pi

This is a minimal Python application with several workflow files:

* One which runs on GitHub's cloud servers
* One which runs on a self-hosted computer
* One, a Hello World shell script which also runs self-hosted

These were tested on a Raspberry Pi 4B, Raspberry Pi OS.

This repo solves the problem: GitHub's default Python setup installs
X86 binaries and doesn't work on ARM (Raspberry Pi). So, in the 
process of setting up Pi runners, I made this configuration.

For some reason, GitHub's runner client won't run on a Pi Zero. I'm
not sure exactly what the problem is.
