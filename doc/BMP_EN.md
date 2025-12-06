# Wireless Implementation Using BMP Boost ([日本語](./BMP.md))

## Note
- Always verify operation in a non-wireless state before switching to wireless mode.
- The slide switch function is now power on/off, and the LED will not illuminate.

## Preparation

### Additional Required
![](./img/IMG_8786.jpg)

- [BMP Boost](https://shop.yushakobo.jp/en/products/10737) ...1
- [Conthrough (12Pin,3.5mm)](https://shop.yushakobo.jp/en/products/31?variant=50965220491495) ...2
- [Battery box](https://akizukidenshi.com/catalog/g/g109292/)(I'm not sure if it will fit properly with any other product besides this one.) ...1
- AA battery ...1

### What to need
- Handyman Macropad v2
- Wireless bag
- USB cable
- Screwdriver

### BMP BOOST Settings
Connect the BMP BOOST to your PC using a USB cable, then access the BLE Micro Pro Web Configurator in Google Chrome.

- [BLE Micro Pro Web Configurator](https://sekigon-gonnoc.github.io/BLE-Micro-Pro-WebConfigurator/)

Update the bootloader and applications. As a general rule, update them to the latest version of the same version.

![](./img/1.png)
![](./img/2.png)
Please verify that CONFIG.BIN is present on the BMP drive.
![](./img/3.png)

Download this zip file.
- [handymanv2_bmp.zip](https://github.com/Taro-Hayashi/Handyman-v2/releases/latest/download/handymanv2_bmp.zip)

rag and drop the three files inside the zip file. Confirm that the files you placed on the drive have disappeared.
![](./img/4.png)



## Disassembly and Assembly
Pull out the knob cover. Be careful not to lose the small acrylic cap.
![](./img/IMG_8730.jpg)

Remove the switch plate. While you can remove them all at once, for safety, remove each switch individually.
![](./img/IMG_8760.jpg)

Remove all switches from the switch plate for installation.
![](./img/IMG_8959.jpg)

Remove the screws and take off the bottom cover.
![](./img/IMG_8769.jpg)

Remove the remaining three screws and detach the bottom stand.
![](./img/IMG_8776.jpg)

Remove the microcomputer cover from the bottom stand. Be careful to pull it straight up vertically, as the marked areas are prone to bending (though bending usually does not affect functionality).
![](./img/IMG_8780.jpg)

Remove the bottom plate. Store the marked parts so they are not lost.
![](./img/IMG_8808.jpg)

Remove the jumper pins from two locations.
![](./img/IMG_8816.jpg)

Thread the spring washer and washer onto the 8mm screw of the wireless bag in that order.
![](./img/IMG_8820.jpg)

Insert an 8mm screw through the two battery holes on the board from the front, then secure it from the back with a washer followed by a nut.
![](./img/IMG_8824.jpg)

Place the metal part of the battery box lead wire between the washer and pad, then screw it down to ensure electrical continuity.
Route the lead wire out in the direction of the arrow.
![](./img/IMG_8828.jpg)

Insert the console. The position is offset by one pin vertically.
The conthrough aligns the window height and orientation. This guide standardizes holes at a higher position and facing forward.
![](./img/IMG_8891.jpg)

Align the BT position and insert the BMP BOOST into the conthrough.
![](./img/IMG_8897.jpg)

Connect via USB and verify operation.
![](./img/IMG_8901.jpg)

If there are no issues, insert the batteries, slide the switch to the ON position, and attempt a Bluetooth connection.
![](./img/IMG_8905.jpg)
Once you've confirmed the connection, remove the battery.

Insert the battery box through the large hole and place the bottom plate onto the circuit board.
![](./img/IMG_8833.jpg)

Reattach the slide switch cover and side button cover.
![](./img/IMG_8915.jpg)

Attach the adapter to the battery box. Align the lead wire outlet with the adapter's protrusion.
![](./img/IMG_8921.jpg)

Insert the battery box with the adapter attached into the bottom stand. Pay attention to the orientation.
![](./img/IMG_8927.jpg)

Place the BMP cover on the BMP BOOST.
![](./img/IMG_8935.jpg)

Place the bottom stand on the bottom plate.
![](./img/IMG_8943.jpg)
Route the lead wire so it doesn't get pinched. Securing it with masking tape makes it easier.

Screw the bottom stand into place. Use 10mm screws for thick sections and 8mm screws for thin sections, then tighten with nuts.
![](./img/IMG_8949.jpg)

Attach the cover and secure the 10mm screw with a nut.
![](./img/IMG_8952.jpg)

Place the switch plate.
![](./img/IMG_8962.jpg)

Install the key switch and reattach the knob.
![](./img/IMG_8966.jpg)


## Key Customization
Connect to your PC via USB and access Vial using Google Chrome (do not use Remap).
- [VIAL WEB](https://vial.rocks/)

Click the key to change the setting, then click the change from below to complete the setting.
![](./img/vialstart.jpg)

The circles lined up on the right correspond to the settings for wheel and dial rotation.
![](./img/vialencoder.jpg)

### Shortcut Settings
To configure various shortcuts, you register the modifier key (such as Ctrl) in the Quantam tab, then register the keys to press within that modifier key.
![](./img/vialquantum.png)

For example, for Ctrl+Z, register LCtrl() and register Z within it.
![](./img/vialz.png)

Abbreviations represent: L/R → Left/Right, C → Ctrl, S → Shift, A → Alt/Option, G → Windows/Command.
Keys labeled with “_T” are Mod-Tap keys. Pressing them briefly activates the key they're overlaid on, while holding them down locks the corresponding modifier key in a pressed state.

### Layer Settings
Click the number on the left to set keys for a different layer. Switching layers changes all settings at once, effectively increasing the number of keys.
![](./img/viallayer.jpg)

Pressing the TG(number) key will switch to the specified layer thereafter.
MO(number) switches to the specified layer only while the key is held down.
![](./img/vialmo.jpg)

### Bluetooth pairing key
Bluetooth-related keys are located in the User tab.
![](./img/vialuser.png)

SEL can switch between USB and wireless.
ADV switches the connection destination, and DEL deletes the connection destination.

### Saving and Restoring Settings
Saving and Restoring Settings
![](./img/vialfile.jpg)

[Back to Start Page](../README.md)
