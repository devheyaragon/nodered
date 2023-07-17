# LogView - Atomatic logging and presentation of DataPoints
![Dashboard](custom-dashboard.png)

The LogView automatically log any datapoint tagged with '#l', and generates corresponding charts
This version of the LogView is a Proof-of-concept and only works with the proServ Gateway. 
PM dev@proknx.com if you're interested in other gateways.

## Explanations:
- in ETS, tag relevant datapoints with '#l' (that is add #l at the end of the name)
- download and import the netdata.json flow (it will be added as NETDATA tab)
- install Netdata from Node-RED
- Wait a few minutes
- Open dashboard, two views are available:
   1.  [http://<IP>:19999/#menu_sensors](http://<IP>:19999//#menu_sensors) System & Sensors in Netdata dashboard
   2.  [http://<IP>:19999/sensors.html](http://<IP>:19999/sensors.html) Sensors Netdata dashboard (sensors only)
