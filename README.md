![RFID](https://cloud.githubusercontent.com/assets/8536299/8459378/03f6b900-201d-11e5-82d9-d7288c7a8099.jpg)

# NFC/RFID Card Catcher v0.1
* Recording NFC/RFID cards for fun and hacking
* Original idea from a french television program "On n'est plus des pigeons"

# Requirements
* Arduino Mega 2560
* SD Card Reader
* Adafruit PN532

# Does it work ?
* Half, for an unknown reason SD reader can't work while PN532 is working, i suppose the problem come from the SPI.
However i've decided to release my code till i (or someone) fix it or change the wiring of the PN532 to I²C bus.

# Warning
* Regarding to the Eagle board layout, i know there is no reason yet to make it but anyway i've designed it to use a specific SD Card reader who can be bought on DealeXtreme, detail can be found on the header of Catcher.ino

# License

WTFPL (see license.txt)
