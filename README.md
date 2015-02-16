# Deauth
Simple script disconnecting all clients from network
## What you need
ifconfig
iwconfig
iwlist
aireplay-ng
## Usage
deauth [-a] <BSSID>...
Disconnects all clients from specified wifi networks
    -a --all
        Disconnects all clients from all networks
    -c --count <number>
        Number of deauth packets
    -h --help
        Prints help
