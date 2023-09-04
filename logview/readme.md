# LogView - Automatic logging and presentation of DataPoints
![Dashboard](custom-dashboard.png)

The LogView for proServ automatically log any datapoint tagged with '#l', and generates corresponding charts
This version of the LogView is a Proof-of-concept and only works with the proServ Gateway. 
PM dev@proknx.com if you're interested in other gateways.

## Explanations:
- In ETS, tag relevant datapoints with '#l' (that is add #l at the end of the name)
- Download and import the netdata.json flow (it will be added as NETDATA tab)
- Select the 'HARD reset' to recreat charts, wait a bit 
- Reboot
- Open dashboards from Aragon menu 'Extras'

![Screenshot Netdata flow](netdata-flow.png)
![Screenshot Netdata Dashboard fullscreen chart](chart-fullscreen.png)
