## Adafruit MCP23017 I2C GPIO Expander Breakout - STEMMA QT / QWIIC PCB

<a href="http://www.adafruit.com/products/5346"><img src="assets/5346.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit MCP23017 I2C GPIO Expander Breakout - STEMMA QT / QWIIC. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/5346

### Description

We’ve gotten a lot of requests for a MCP23017 breakout and we’ve always sorta been like “ehh why not just use the DIP chip?” but with STEMMA QT we could see the use case for a plug and play version that comes with all the passives on board. This Adafruit MCP23017 I2C GPIO Expander Breakout has 16 GPIO with matching ground pad.

We particularly like the '17 as an expander for it's simple no-nonsense capability. It runs happily from 3V or 5V logic and power. Each GPIO can be an output driving up to 25mA, so LEDs are no problem. Or, each can be an input, with optional pullup. There are two IRQ pins that are configurable for what inputs to keep track of so no I2C bus polling is required. With 3 address pins, you can have up to 8 on a single bus for a total of 8 x 16 = 128 GPIO all on one I2C bus!

We've got solid Arduino and CircuitPython libraries with examples, all ready for this chip. But even if you are using some other platform, the MCP23017 is so classic, you'll likely be able to find example code.

Comes with two sticks of header so you can use it in a breadboard, with some soldering. You can also free-wire buttons by connecting one side to the GPIO (set as input with pullup) and the other side to a ground pad.

To get you going fast, we spun up a custom-made PCB in the STEMMA QT form factor, making it easy to interface with. The STEMMA QT connectors on either side are compatible with the SparkFun Qwiic I2C connectors. This allows you to make solderless connections between your development board and the MCP23017 or to chain it with a wide range of other sensors and accessories using a compatible cable.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
