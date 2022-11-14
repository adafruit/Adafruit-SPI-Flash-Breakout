## Adafruit SPI Flash Breakouts

<a href="http://www.adafruit.com/products/5635"><img src="assets/5635.jpg?raw=true" width="400px"></a>&nbsp; 
<a href="http://www.adafruit.com/products/5636"><img src="assets/5636-01.jpg?raw=true" width="400px"></a><br />
<a href="http://www.adafruit.com/products/5643"><img src="assets/5643-01.jpg?raw=true" width="400px"></a>&nbsp; 

Click to purchase from the Adafruit Shop:
- [Adafruit SPI FLASH Breakout - W25Q16 - 16 Mbit / 2 MByte](https://www.adafruit.com/product/5635)
- [Adafruit SPI FLASH Breakout - W25Q64 - 64 MBit / 8 MByte](https://www.adafruit.com/product/5636)
- [Adafruit SPI FLASH Breakout W25Q128 - 128 MBit / 16 MByte](https://www.adafruit.com/product/5643)

PCB files for the Adafruit SPI Flash Breakouts. 

Format is EagleCAD schematic and board layout

### Description

Sometimes you need a little extra storage for your microcontroller projects: for files, images, fonts, audio clips, etc. If you need lots of space, like in the gigabytes, we always recommend an SD card because you can easily plug it into a computer to edit files. But sometimes you don't need whole gigabytes, you just need a megabyte or two, with the lower cost and power usage that comes with it. That's when we recommend an Adafruit SPI FLASH Breakout such as this one that is fitted with a W25Q16 - 16 Mbit / 2 MByte, W25Q64 - 64 Mbit / 8 MByte or W25Q128 - 128 Mbit / 16 MByte chip.

Compared to our QSPI breakouts, this one is single-channel SPI only...BUT it comes with level shifting so it can be used safely with 3V or 5V power and logic. Since we needed to add level shifting, the chip is pre-wired into single channel "SPI" mode, with a level shifters so you can use it with 3V or 5V logic easily. You also get a 3.3V regulator and a pullup on CS. 

Note that the chips come blank, and do not have a wear-leveling subsystem. You can address them as a flat memory space or, if you like, format them with a filesystem like littleFS or FAT. Great for use with data-logging or storage needs where you are OK with doing the management yourself - or if you are adding external memory to an older chip that would like 5V-compatibility.

In Arduino, we have the Adafruit_SPIFlash library that can be used to interface with this chip. Comes with a bit of header that can be used to solder in and plug into a breadboard if desired.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
