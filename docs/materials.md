## Navigation

- [Home](../readme.md)
- [Expanded Introduction / Forward](introduction.md)
- [Image Gallery](gallery.md)
- [Materials Required](materials.md)
- [Printing Instructions / Suggestions](printing.md)
- [Assembly](assembly.md)
- [STL Index](../stl/readme.md)

# Equipment and Materials
**Note:** None of the links in this guide are affiliated. I hate that and I won't do it to you. Also, I'm going to assume you have a soldering iron here, you didn't make this far without one.

## 1. FDM 3D Printer
Obviously you're going to need one of these, however you need to make sure it will fit the case. The dimensions of the GBAlpha are as follows:

- **Base**: 208.5mm (W) x 84mm (D) x 33mm (H)
- **Lid**: 208.5mm (W) x 84mm (D) x 8.39mm (H)

This will print on an Ender 3 just fine (I use an Ender 3 V2), however if you have a smaller bed (like the Max Creator) you won't be able to print this object.

Furthermore, I highly recommend some sort of auto bed leveling such as a BLTouch or a CRTouch, this will help make your prints far more successful since these are chonky and adhesion can be an issue.

I have not tried this on a resin printer because I do not own one, but I don't see why you couldn't assuming you have a large enough print area.

## 2. Printing Filament
I just used PLA and this entire guide is around using that- brands I used while doing this project were:

 - Amazon https://www.amazon.com/gp/product/B07T6VTG5Q
 - Overture https://www.amazon.com/gp/product/B07VFQS5J3
 - SUN https://www.amazon.com/gp/product/B07ZNHTZ2T

However, use whatever you like. If you want to attempt to use more exotic materials, my printing guide will be of no help to you, you are on your own.

## 3. FFC and FFC Extensions (Flex Cables)
You are going to need these to make the case work because Woozle's cables are hard-wired to the board also the included cables are too short and won't reach otherwise.

### CPU Extension
- 1x 20 Pin 0.5mm FFC Cable (Type A): https://www.amazon.com/gp/product/B07RT6YHYD
- 1x 20 Pin 0.5mm FFC Extender: https://www.adafruit.com/product/5203

### Display Extension

#### Option A (Your GBA has a standard 40 pin FFC)

- 1x 40 Pin 0.5mm 150mm FFC Cable (Type B): https://www.amazon.com/gp/product/B0928Q1N2Z

#### Option B (Your GBA has to use Woozle's FFC)
**Warning:** This is untested, I do not have one, but logically this makes sense like the CPU extensions. However, as noted, I provide no warranty anyways, use your noodle.

- 1x 40 Pin 0.5mm 150mm FFC Cable (Type A): https://www.amazon.com/gp/product/B07S1C68C3
- 1x 40 Pin 0.5mm FFC Extension: https://www.adafruit.com/product/4523

## Variation Materials
Pass this point you will need to make a choice on which variation of the case you want to make. All the variations except the **minimalist variation** will need everything below. For the **minimalist variation** all you will need eight (8) `M2*6` screws and how to get them will be linked below. To see these variations look at the [STL index readme](../stl/readme.md).

## 4. M2 Screws
For the case and the power switch you will need:

- Eight (8) M2 * 6 Screws
- Two (2) M2 * 4 Screws (For the power switch, alternatively you  can just use M2*6)

Honestly buying a set of them is dirt cheap and useful to have, these are the ones I purchased: https://www.amazon.com/gp/product/B08NVVZC7Y

## 5. Power Switch
You just need a two position ON/ON power switch toggle, here is the one I purchased and used on the case:
https://www.amazon.com/gp/product/B007QAJWYW

## 6. LEDs and LED Holders
This case uses 3mm LEDs. These will be going into a 3.3v lead so if you're going to wire them yourself keep that in mind. However if you don't want to fiddle with all of that you can buy pre-assembled LEDs for not a lot of money:

- Pre-Wired LEDS: https://www.amazon.com/gp/product/B07X2YSQTQ
- 3mm LED Holders: https://www.amazon.com/gp/product/B08ZY6C6NC

## 7. DuPont Connectors and Crimps
This case is designed to be disassembled, so one of the things that will be done is that pins will be added to the FPGA board to easilly disconnect and reconnect the power switch and the LEDs. You will need these tools to do so. This kit is a good value and worked for my needs (it also comes with ribbon cable):

https://www.amazon.com/gp/product/B08D34JW68

## 8. Heatshrink
Since you're going to be making connections to the power switch, it's good to get those covered up. I'm not going to link to any specific brand here since they are all generally fine. You can just do a search like this and pick your fancy:

https://www.amazon.com/s?k=heatshrink+tubes+or+wire+cable+sleeve&i=industrial&sprefix=heatshrink%2Cindustrial%2C60

