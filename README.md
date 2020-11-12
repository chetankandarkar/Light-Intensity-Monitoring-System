# Light-Intensity-Monitoring-System
Bolt Cloud Project

Aim : Visualize the data from the LDR in different graph format.

Hardware Required
- Bolt IoT Module
- Micro USB Cable
- LDR (2 legged devicewith a red wave pattern disk on top)
- 10k Ohm Resistor (brown black orange color code)

## Procedure 
1) Do the Circuit Connection :
- Insert one lead of the LDR into the Bolt Module's 3v3 Pin.
- Insert other lead of the LDR into the A0 pin.
- Insert one leg of the 10k Ohm resistor into the GND pin
- Insert the other leg of the resistor also into the A0 pin

Hardware Setup :

<img src="Images/Hardware%20Setup.png" width="400"/>

2) Link Product to the device :
- Go to [https://cloud.boltiot.com/](https://cloud.boltiot.com/)
- Click on link button and select your bolt device.
- Go to device tab and click on deploy configuration button.

![](Images/Link%20Product.png)

- Click on deploy configuration button after every 10 seconds than Cick on view device button you will see table with data.

![](Images/Data%20Table.png)

2) Product Setup :
- Go to Product tab 
- Give product name.
- Select input data and GPIO than click on done button.
- Now click on configuration button.
- In hardware tab select data rate 5 minutes.
- Select A0 pin and enter light in variable name.
- Then Click on save button.

![](Images/Product%20Setup.png)

3) Enter the code:
- Click on code tab.
- Give file name "light_monitor"
- Choose file type js extension.
- Now Enter the code for different graph format and visualize the graph in difftent format.

![](Images/Javascript%20Code.png)

## Output:

## Line Graph:
![](Images/Line%20Graph.png)

## Bar Graph:
![](Images/Bar%20Graph.png)

## Scatter Graph:
![](Images/Scatter%20Graph.png)

## Area Graph:
![](Images/Area%20Graph.png)

## Gauge Graph:
![](Images/Gauge%20Graph.png)

Conclusion : Hence we visualise LDR data in different graph format using javascript code .
