# WifiLight MR16

Its very easy to get hold of a wifi-controlled lightbulb that plugs into an Edison Screw (E27) fitting or a Bayonette fitting (B22).. It is possible to get some IR remote controlled GU10 light fittings.. But what about an ESP8266-powered wifi-enabled light fitting to go into an MR16 socket?

With this in mind I have set out to develop such a product.

![alt text](https://raw.githubusercontent.com/matthewbaggett/wifi-recessed-lightbulb/mk6/wifilight.brd.png)
![alt text](https://raw.githubusercontent.com/matthewbaggett/wifi-recessed-lightbulb/mk6/wifilight.sch.png)

# Programming Harness

To make it easy to program the ESP9266 via the 1.5mm JST socket, I designed a FTDI-based programmer. I have also attached a SMD 6 pin header that works just like any other FTDI serial USB device to make it useful beyond the life of this project.

![alt text](https://raw.githubusercontent.com/matthewbaggett/wifi-recessed-lightbulb/mk6/programmer.brd.png)
![alt text](https://raw.githubusercontent.com/matthewbaggett/wifi-recessed-lightbulb/mk6/programmer.sch.png)
