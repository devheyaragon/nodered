# LogView - Automatic logging and presentation of DataPoints
![Dashboard](custom-dashboard.png)

This flow is for Aragon Master (Aragon Maestro includes the LogView for proServ as standard application starting from flow version 2024-12-05).

The LogView for proServ automatically log any datapoint tagged with '#l', and generates corresponding charts

**Note that Netdata v2 is required. Update your system from Aragon About System update**

## Explanations:
- In ETS, tag relevant datapoints with '#l' (that is add #l at the end of the name)
- Download and import the netdata.json flow (it will be added as NETDATA tab)
- Select the 'HARD reset' to recreat charts, wait a bit 
- Open dashboards from Aragon menu 'Extras'

![Screenshot Netdata flow](netdata-flow.png)
![Screenshot Netdata Dashboard fullscreen chart](chart-fullscreen.png)
