# Juniper Network Connect

A bash / applescript to automatically connect to a VPN via Juniper's Network Connect client.

## Installation:

    git clone git@github.com:justinleveck/network-connect.git ~/
    chmod u+x ~/network-connect/network
    ln -s ~/network-connect/network ~/bin/network
    ln -s ~/network-connect/network/network.plist ~/network.plist

## Upgrade:

    cd ~/network-connect

    git pull

## Quick Guide

Edit the network.plist file with your values.

    vim ~/network.plist

Run the following in your terminal

    network

## Configuration File

    <?xml version="1.0" encoding="UTF-8"?>
    <!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN"
    "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
    <plist version="1.0">
    <dict>
      <key>username</key>
        <string>User Name</string>
        <key>pw</key>
        <string>Password</string
        <key>gatewayHostName</key>
        <string>Gateway Host Name</string>
    </dict>
    </plist>
