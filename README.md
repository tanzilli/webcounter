# webcounter

NodeRED simple flow to count how many times three pushbuttons are pushed and show the result on a webpage

![Screenshoot](/screenshoot.png)


## Installation

Starting from a working Rasbian Lite (tested on the version March 2018) install NodeRED by typing this command:

```
bash <(curl -sL https://raw.githubusercontent.com/node-red/raspbian-deb-package/master/resources/update-nodejs-and-nodered)
```

Access via web to your Raspberry Pi NodeRED interface:

<http://raspberrypi.local:1880>
 
Install the palette __ttb-node-red-counter__ using the Palette manager

Import the __webcounter.json__ file using the __Import->Clipboard__ function available on the NodeRED menu.
