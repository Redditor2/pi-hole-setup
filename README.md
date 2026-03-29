@author cotton
@version 29/03/2026

# pi-hole-setup

Network-wide DNS ad and tracker blocker running on raspberry pi 4, installed and configured from scratch.

## what it does
- blocks ads and trackers at the DNS level for every device on the network
- logs all DNS queries in real time
- serves a web dashboard showing blocked/allowed traffic

## what i learned
- how DNS filtering works at a network level
- how to set up and run a headless Raspberry Pi
- how to configure a Pi as a network DNS server

## what went wrong and how i fixed it
- enterprise WiFi blocking Pi from connecting (solved using phone hotspot)
- USB stick needed reformatting before flasing OS
- SSH host key changed when switching networks (cleared with ssh-keygen -R)

## screenshot
<img width="2599" height="1519" alt="image" src="https://github.com/user-attachments/assets/c72e7844-4083-4a2a-8dcd-251352669a12" />

## tech/tools
Raspberry Pi 4, Raspberry Pi OS Lite, Pi-hole

## build log
- March 2026: initial setup and installation
