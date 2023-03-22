# Heater control

This project could be interesting for everyone, who is looking for an alternative/replacement heater control unit for any oil or gas burner.
The system controls the general heating time per day, e.g. Monday from 06:00 to 20:00. Hysteresis via start and the stop temp, e.g. 35 degrees burner start and 60 degrees burner stop temp, when them is back to 35 degrees the burner switches on again...
The circulation pump is controlled as well, it starts with the daily start time and ends with the daily stop time + 15 min, in order to give the oven a bit time to cool down.


## Software images

<pre><img src="images/controlcenter.png" width="190px">&#9;<img src="images/timer.png" width="190x">&#9;<img src="images/setup.png" width="190px">&#9;<img src="images/network.png" width="190px"></pre>

## Device images

<pre><img src="images/device_mounted.png" width="800px"></pre>
<pre><img src="images/dev1.jpeg" width="300px">&#9;&#9;<img src="images/dev2.jpeg" width="300px"></pre>

## Features

- Intuitive web frontend
- System works without any cloud service, but need ntp connection for current time
- Standard hardware

## Communication

- Standard wireless LAN connection based on 802.11
- Simple wifi setup via web frontend (DHCP or fixed IP)

## Functions

- Easy setup for all functions
- Everything is controlable via integrated web frontend
- Start / Stop timer for every weekday
- Start / Stop temp control

## Control


## Whats needed?

- For each blind a ESP-32 micro controler board, a 28BYJ-48 5vdc stepper motor with controller, some dupond cables and a 5v power supply with micro usb connector are needed

- ESP-32: https://amzn.to/3uuozcW
- Stepper motor with controller: https://amzn.to/3FgGmcW
- OPTIONAL - Mini stepper motor controller: https://amzn.to/3Bu9mfZ
- Any 5v power supply with micro usb connector

**You can also buy plug&play solution which includes a 3d printed drive enclosure, mini stepper driver inclusive ESP-32 adapter.**
[Drive enclosure with stepper driver and ESP-32 adapter](https://www.etsy.com/de/listing/1120088196/wifi-wlan-rollo-innenrollo-doppelrollo?ga_order=most_relevant&ga_search_type=all&ga_view_type=gallery&ga_search_query=rollo+antrieb&ref=sr_gallery-1-1&edd=1&organic_search_click=1)

## Connection schematic

The following pictures shows the wireing diagram for the basic controller, which mostly comes with the stepper motor.

<pre><img src="schematics/schematic.png" width="400px"></pre>

## Installation and setup

[Installation guide](https://github.com/danieldownload/mysmartrollo/wiki/Installation-guide)





## Donate
If you would like to support the developer with a cup of coffee you can do that via [Paypal](https://www.paypal.com/donate/?hosted_button_id=XN85B8YSH7KBL)
