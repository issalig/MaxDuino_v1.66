# maxduino

http://www.va-de-retro.com/foros/viewtopic.php?t=5541

* V1.38	Code reformatted, cas is optional with new #def Use_CAS. Solved a bug when back with stop button from 4th subdir.
* V1.37 Minor optimizations for counter format, acorn standard/turbo speed, simplication in polarity handling and now controlled from menu using the same option for tsx acceleration: tsxSPEEDzxPOL.
* V1.36 Polarity handling with conditional define.
* V1.35t Acorn speed for loading now 1500 baud, 20% faster (standard is 1200).
* V1.35 Uncompressed UEF support for Acorn computers.
* V1.34 alias "EEPROM version". Now blocks can be directly read/written from EEPROM.Also logo can be copied to eeprom using #define option.
	After that, you can select option for loading logo directly from EEPROM.. this saves 512 bytes in the sketch.
* V1.33 Blocks for manual REW/FF expanded from 10 upto 20, used as circular buffer. On Oled screen prints upto 99 blocks, 
	overflowing to 00. Selecting a block in pause mode traverse last 20 blocks.
* V1.32 Deprecated old pskipPause. New block2A pause control managed in menu.
* V1.31 Modified ID20,2A to support automatic pausing(@spirax). Also swapped REW-FW for block navigation(@acf76es). 
* V1.30 max TSX speed 3850 vs cas speed 3675. Also changed in Menu.
* V1.29 3-digits counter can be configured to display m:ss with #define CNTRBASE
* V1.28 Better speeed loading tzx files, more than 5000 baud using PORT instructions

### In memoriam

To my father R.I.P. who bought my first ZX spectrum and forced me to learn with his casio programming calc.