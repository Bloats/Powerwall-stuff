# Powerwall-stuff

This is a monitoring Node Red flow that listens on UDP port 18542 IPv4 for the Batrium broadcasts

Copy the contents of the flow file and import from the clipboard into node red - it should create a new flow.

Tested with a Watchmon4

HW ver 4.2

FW ver 4.8

Sw ver 2.0.12

Credit for the bulk of the parsers to Daniel Römer from his grafpi project:
http://diytechandrepairs.nu/raspberry-solar/
and
https://github.com/Batrium/WatchMonUdpListener

Gaps filled and clarifications from the Batrium datasheet:
Watchmon SW 1.0.30 UDP Outbound protocol

The machine running node red must be able to access port 18542 UDP IPv4
