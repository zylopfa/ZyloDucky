# ZyloDucky

The ZyloDucky is a usb hardware key injector, that work a little bit like this:


* Stick it into a USB port on the computer you wish to inject keypresses into
* Share your phones internet, for the ZyloDucky to use, or configure with other AP creds.
* ZyloDucky use the available wifi connection to connect to a preconfigured irc server / channel
* From the IRC channel you can control the ZyloDucky to make it inject whatever you please,
  whenever.

There are several parts that goes into making a ZyloDucky, the major parts are as follows
and will be explained further in their own sections.


* **Hardware**, what microcontroller, wifi module ,what other discrete components and how its
put together
* **Microcode**, the programming on the microcontrollers, irc bot software etc.
* **Support Programs**, program to convert text,actions to scancodes, delays.
* **Ducky Language**, simple declarative language to instruct the ZD on what to type

