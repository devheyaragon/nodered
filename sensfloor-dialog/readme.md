# Future-Shape's SensFloor technology with Aragon Voice Dialog
![sensfloor-dialog](sensfloor-dialog.png)

This documentation explains how to configure voice dialog with the SensFloor and its corresponding actions. 

# Overview
Install required nodes and import flow to Aragon Master.
The code snippet provided is written in JavaScript and is used to configure voice dialog and actions for different events from the SensFloor. The code uses the flow object to set the actions, dialog, and say messages for each room. Additionally it defines the mapping of SensFloor Area ID to Room/siteId.

# Installation
1. Aragon Main UI About: Install/confirm Aragon Master v1.5.14 or better
1. Aragon Main UI  `Menu | Set Node-RED password` **MANDATORY**
1. Install the SensFloor SE10 room controller and the Aragon Master in the same network.
1. Install `node-red-contrib-socketio-client-wildcard` from Node-RED Menu | Palette
1. Download and import the sensfloor-dialog-socketio.json flow from [https://raw.githubusercontent.com/devheyaragon/nodered/main/sensfloor-dialog/sensfloor-dialog-socketio.json](https://raw.githubusercontent.com/devheyaragon/nodered/main/sensfloor-dialog/sensfloor-dialog-socketio.json)
1. Edit the config node of the Socket.IO Client node and set the URI to `${sensfloor_api}`
-> The SendFloor room controller will be found automatically (the Socket.IO client node indicates a green dot and 'connected')

# Configuration 
Open the `ID->ROOM, ACTIONS & DIALOG` node to set how the SensFloor Area ID maps to Aragon siteId/room.
Once the Aragon room namemapping to Sensfloor Area ID's is set, you're ready to test.
You can then continue to customize the default configuration (e.g. disable room_in, modify the actions, etc)


