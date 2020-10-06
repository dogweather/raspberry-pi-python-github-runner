# A Python self-hosted GitHub Runner for the Raspberry Pi

![Python application on self-hosted Raspberry Pi](https://github.com/dogweather/raspberry-pi-python-github-runner/workflows/Python%20application%20on%20self-hosted/badge.svg)

This repo solves the problem: GitHub's default Python setup installs
X86 binaries and doesn't work on ARM (Raspberry Pi). So, in the 
process of setting up a new Python app, I extracted this configuration.

This is a minimal Python template application which runs several workflows:

* One which runs on a self-hosted Raspberry Pi
* One which runs on GitHub's cloud servers
* One, a Hello World shell script which also runs self-hosted

It's also still compatible with MacOS and GitHub's cloud servers.

## Compatible Pi's

These were tested on a Raspberry Pi 4B 4G RAM, running Raspberry Pi OS.

For some reason, GitHub's runner client won't run on a Pi Zero. I'm
not sure exactly what the problem is.
