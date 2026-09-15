# splithie

![splithie](https://raw.githubusercontent.com/makkomise/splithie/refs/heads/main/src/Splithie_pcb.png)

*Ortho-split keyboard with 56 keys and RGB-per key lighting*

> [!CAUTION]
> THIS IS ACTIVE WORK IN PROGRESS. I will upload Gerbers for ordering when they're finished and tested.


TODO (Important):
- [ ] Finish up the PCB Design
- [ ] Solder and test the PCB
- [ ] Make a keymap and compile a test firmware

TODO (Less important):
- [ ] Optimize firmware
- [ ] Print the case and make a proper test fit for everything

----------------------------------------------------------------------------------

BOM

Below are the materials needed for the PCB.

> [!NOTE]
> Oleds and Reset switches are optional, you can use reset by shorting the 2 pins on PCB quickly 2 times with tweezers.

| Type			| Value				| Qty			| Package		| LCSC			|
| ------------- | ----------------- | ------------- | ------------- | ------------- |
| Capacitor		| 100nF		 		| 56			| 0603			| C1591			|
| Diode			| BAV-70			| 28 			| SOT-23		| C22368862		|
| USB-C			| TYPE-C-31-M-12	| 4 			| SMD			| C165948		|
| OLED			| 0.91" 128x32		| 2  			| -				| C5248081		|
| RGB			| SK6812MINI-E		| 56			| SMD			| C5149201		|
| MX_Socket		| -					| 54  			| -  			| C5156480		|
| Dev. Board	| ProMicro RP2040	| 2  			| -  			| -  			|
| Reset SW 		| PTS636 SP43 LFS	| 2				| - 			| C2801383		|

> [!NOTE]
> Even though i tried to list LCSC part numbers for all the parts, for example hotswap sockets and pro micros are cheapest to get from AliExpress.
