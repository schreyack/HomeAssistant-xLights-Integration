# HomeAssistant-xLights-Integration
Example code to allow xLights to control things in Home Assistant via the Node-RED addon

Assumptions:
You are familiar with Home Assistant and installing Addons

Installation:

Install Node-RED Home Assistant Addon

In Node-RED install the following pallettes:
node-red-contrib-sacn
node-red-contrib-sacn-in

The examples contain your Node-RED flows along with example code to use for each domain.  In my case, I have HA set to xlights universe 600.  Set that to whatever you prefer in your case.

In the event you have trouble - add a debug node in the flow and watch the debug output to see what is going wrong.

On the xLights side, you will add you HA instance IP address just like any other controller.  Make sure you enable Dedup and disable Monitor.
