# Sony Bravia TV

This flow demonstrates how to integrate a Smart TV Sony Bravia and control it by offline voice.

These steps show how to integrate  Smart TV Sony Bravia with Aragon. 

- switch on/off TV
- control the volume
- next/previous
- pause/play
- change/choose channels

## Step 1 : Install Bravia node

At the top right menu, go to manage palette and install node-red-contrib-bravia nodes.


## Step 2 : Download the flow via URL below

Download the flow (sony-bravia-tv.json) and import it.


## Step 3 : Assign the IP address and the Pre-Shared Key (PSK)

At the top right menu, go to configuration nodes and select Sony Bravia TV.

NOTE : It is advised to set a static IP, see the network settings of the TV.

Enter the IP address of your TV and the PSK that you have defined in the set-up. The PSK is defined in the TV Settings | Network menu. You can find the IP of the TV in the Settings under Network Status.


##Step 4 : Define siteId of the TV

When a hotword is detected, the Aragon will mute the TV, but only if the siteId is set. By default, the site id of the TV is “Living room”.



