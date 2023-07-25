# LogView - Automatic logging and presentation of DataPoints
![Dashboard](custom-dashboard.png)

**Note:** Requires minimum flow version '2023-07-17'

The LogView for proServ automatically log any datapoint tagged with '#l', and generates corresponding charts
This version of the LogView is a Proof-of-concept and only works with the proServ Gateway. 
PM dev@proknx.com if you're interested in other gateways.

## Explanations:
- in ETS, tag relevant datapoints with '#l' (that is add #l at the end of the name)
- download and import the netdata.json flow (it will be added as NETDATA tab)
- install Netdata from Node-RED (see the read square in the sreenshot of the flow)
- Wait a few minutes
- Open dashboard, two views are available:
   1.  <code>http://IP-MASTER:19999//:19999/spaces/aragon2master/rooms/local/overview#metrics_correlation=false&after=-900&before=0&modal=&modalTab=&local--chartName=menu_sensors</code> System & Sensors in Netdata dashboard
   2.  <code>http://IP-MASTER:19999/sensors.html</code> Sensors Netdata dashboard (sensors only)

![Screenshot Netdata flow](netdata-flow.png)
![Screenshot Netdata Dashboard fullscreen chart](chart-fullscreen.png)
