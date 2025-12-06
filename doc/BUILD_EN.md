# Handyman Macropad v2 Assembly Guide ([日本語](./BUILD.md))

![](./img/IMG_9071.jpg)

## Table of Contents
1. [Preparation](#1-Preparation)
2. [Contents](#2-Contents)
3. [Soldering](#3-Soldering)
4. [Assembly](#4-Assembly)
5. [Link](#5-Link)
6. [Troubleshooting](#6-Troubleshooting)

## 1. Preparation
### 1.1 Additional Required
![](./img/IMG_8596.jpg)
<table>
    <tr>
        <td>Cherry MX Keyswitches</td>
        <td>22</td>
    </tr>
    <tr>
        <td>Keycaps</td>
        <td>22</td>
    </tr>
    <tr>
        <td>Type-C USB Cable</td>
        <td>1</td>
    </tr>
 </table>

#### Optional
<table>
    <tr>
      <td>SK6812MINI-E</td>
      <td>22</td>
    </tr>
    <tr>
      <td><a href="https://tarohayashi.booth.pm/items/7544767">Wrist rest</a></td>
      <td></td>
    </tr>
    <tr>
      <td><a href="https://tarohayashi.booth.pm/items/7544767">Adaptor for Cintiq Pro</a></td>
      <td></td>
    </tr>
 </table>

### 1.2 Tools required
![](./img/IMG_8619.jpg)
<table>
    <tr>
      <td>Soldering iron</td>
      <td>Soldering wire</td>
      <td>Masking tape</td>
    </tr>
    <tr>
      <td>Nipper</td>
      <td>Twezers</td>
      <td>Screwdriver</td>
    </tr>
 </table>

#### Tools optional
<table>
    <tr>
        <td>Heat-resistant mat</td>
        <td>Temperature-controlled soldering iron</td>
        <td>C-type trowel tip</td>
    </tr>
    <tr>
        <td>flux</td>
        <td>IPA</td>
        <td>Desoldering wire</td>
    </tr>
    <tr>
        <td>Multimater</td>
    </tr>
 </table>

## 2.  Verification of Contents
It is packaged in several separate bags.
![](./img/IMG_9317.jpg)

### Bag 1: Implementation Components
![](./img/IMG_9366.jpg)
<table>
    <tr>
        <td>1</td>
        <td>10mm screw</td>
        <td>2</td>
        <td>M2x10mm</td>
    </tr>
    <tr>
        <td>2</td>
        <td>8mm screw</td>
        <td>2</td>
        <td>M2x8mm</td>
    </tr>
    <tr>
        <td>3</td>
        <td>Nuts</td>
        <td>4</td>
        <td>M2</td>
    </tr>
    <tr>
        <td>4</td>
        <td>Diodes</td>
        <td>28</td>
        <td>1N4148</td>
    </tr>
    <tr>
        <td>5</td>
        <td>MX sockets</td>
        <td>22</td>
        <td></td>
    </tr>
    <tr>
        <td>6</td>
        <td>Reset button</td>
        <td>1</td>
        <td></td>
    </tr>
    <tr>
        <td>7</td>
        <td>Slide switch</td>
        <td>1</td>
        <td></td>
    </tr>
    <tr>
        <td>8</td>
        <td>Side button</td>
        <td>1</td>
        <td></td>
    </tr>
    <tr>
        <td>9</td>
        <td>Lever button</td>
        <td>1</td>
        <td></td>
    </tr>
    <tr>
        <td>10</td>
        <td>Rotary Encoder</td>
        <td>1</td>
        <td>EC11 15mm</td>
    </tr>
    <tr>
        <td>11</td>
        <td>Pin header</td>
        <td>1</td>
        <td>40 Pins</td>
    </tr>
    <tr>
        <td>12</td>
        <td>Jumper pins</td>
        <td>2</td>
        <td></td>
    </tr>
    <tr>
        <td>13</td>
        <td>RP2040-Zero</td>
        <td>1</td>
        <td></td>
    </tr>
    <tr>
        <td>14</td>
        <td>Rubber feet</td>
        <td>5</td>
        <td></td>
    </tr>
    <tr>
        <td>15</td>
        <td>Micro controller spacer</td>
        <td>1</td>
        <td>Color is random.</td>
    </tr>
    <tr>
        <td>16</td>
        <td>Micro controller clip</td>
        <td>1</td>
        <td>Color is random.</td>
    </tr>
 </table>

### Bag 2: Circuit board and case
![](./img/IMG_9378.jpg)
<table>
    <tr>
        <td>1</td>
        <td>Main board</td>
        <td>2</td>
        <td>Switch plate</td>
        <td>3</td>
        <td>Bottom plate</td>
    </tr>
<table>

### Bag 3: 3DP Parts
![](./img/IMG_9387.jpg)

<table>
    <tr>
        <td>1</td>
        <td>Bottom stand</td>
        <td></td>
        <td>5</td>
        <td>Encoder cover</td>
    </tr>
    <tr>
        <td>2</td>
        <td>Bottom cover</td>
        <td></td>
        <td>6</td>
        <td>Acrylic stand</td>
    </tr>
    <tr>
        <td>3</td>
        <td>Side button cover</td>
        <td></td>
        <td>7</td>
        <td>Acrylic plate</td>
    </tr>
    <tr>
        <td>4</td>
        <td>Slide switch cover</td>
        <td></td>
        <td>8</td>
        <td>Acrylic cover</td>
    </tr>
</table>


### Bag 4: [1U Wheel Encoder THQWGD001](https://github.com/Taro-Hayashi/THQWGD001) ...2
![](./img/IMG_9349.jpg)
<table>
    <tr>
        <td>1</td>
        <td>Wheel</td>
        <td>2</td>
        <td></td>
    </tr>
    <tr>
        <td>2</td>
        <td>Shaft</td>
        <td>2</td>
        <td></td>
    </tr>
    <tr>
        <td>3</td>
        <td>Spacer</td>
        <td>2</td>
        <td></td>
    </tr>
    <tr>
        <td>4</td>
        <td>Base</td>
        <td>2</td>
        <td></td>
    </tr>
    <tr>
        <td>5</td>
        <td>Cover</td>
        <td>2</td>
        <td></td>
    </tr>
    <tr>
        <td>6</td>
        <td>Wheel encoder</td>
        <td>2</td>
        <td>11mm</td>
    </tr>
    <tr>
        <td>7</td>
        <td>Push button</td>
        <td>2</td>
        <td>6x6x7mm</td>
    </tr>
    <tr>
        <td>8</td>
        <td>6mm screw</td>
        <td>4</td>
        <td>M2x6mm</td>
    </tr>
    <tr>
        <td>9</td>
        <td>Nuts</td>
        <td>4</td>
        <td>M2</td>
    </tr>
</table>

### Bag 5: [Skylight knob (24mm)](https://makerworld.com/ja/models/2022018-skylight-knobs)
![](./img/IMG_9330.jpg)
<table>
    <tr>
        <td>1</td>
        <td>Knob</td>
        <td>1</td>
        <td></td>
    </tr>
    <tr>
        <td>2</td>
        <td>Shaft</td>
        <td>1</td>
        <td></td>
    </tr>
    <tr>
        <td>3</td>
        <td>Acrylic plate</td>
        <td>1</td>
        <td></td>
    </tr>
    <tr>
        <td>4</td>
        <td>5mm screw</td>
        <td>1</td>
        <td>M2x5mm</td>
    </tr>
    <tr>
        <td>5</td>
        <td>Nuts</td>
        <td>1</td>
        <td>M2</td>
    </tr>
</table>

### Bag 6: Wireless bag (Not used, but contents will be checked.)
![](./img/IMG_9305.jpg)
<table>
    <tr>
        <td>1</td>
        <td>BMP Cover</td>
        <td>1</td>
        <td></td>
    </tr>
    <tr>
        <td>2</td>
        <td>Adoptor for battery box</td>
        <td>2</td>
        <td>There are left and right sides.</td>
    </tr>
    <tr>
        <td>3</td>
        <td>USB Cap</td>
        <td>1</td>
        <td></td>
    </tr>
    <tr>
        <td>4</td>
        <td>8mm screw</td>
        <td>2</td>
        <td>M2x8</td>
    </tr>
    <tr>
        <td>5</td>
        <td>Washer</td>
        <td>4</td>
        <td>M2</td>
    </tr>
    <tr>
        <td>6</td>
        <td>Spring Washer</td>
        <td>2</td>
        <td>M2</td>
    </tr>
    <tr>
        <td>7</td>
        <td>Nuts</td>
        <td>2</td>
        <td>M2</td>
    </tr>
</table>

###  RP2040-Zero Operation Verification
Download this file.
- [tarohayashi_handyman_v2_default.uf2](https://github.com/Taro-Hayashi/Handyman-v2/releases/latest/download/tarohayashi_handyman_v2_default.uf2)

Connect the RP2040-Zero to the PC while holding down the BOOT button.
![](./img/IMG_8012.jpg)

Since it is recognized as a drive, drag and drop the downloaded file.
![](./img/drive.png)

Once the drive disappears automatically, you're all set.

## 3. Soldering
Take care to ensure the height of the soldered area is 2.5mm or less.
![](./img/IMG_8016.jpg)
Temporarily securing parts with masking tape before soldering helps prevent them from shifting.
![](./img/IMG_8004.jpg)

### 3.1 (Optional) LED soldering
Place the LEDs from BL1 to BL22, aligning the notches and marks on the legs.
![](./img/IMG_7997.jpg)

Soldering.
![](./img/IMG_7989.jpg)

### 3.2 Soldering diodes
Diodes have a polarity. Align the wire with the mark.
![](./img/IMG_8003.jpg)

Cut the legs on the surface and solder them.
![](./img/IMG_8008.jpg)
There are D1 through D28.
![](./img/IMG_8011.jpg)

### 3.3 Soldering diodes MX Sockets
Place and solder components SW1 through SW22, paying attention to their orientation.
![](./img/IMG_8018.jpg)

### 3.4 Soldering pin headers
Cut two 2-pin connectors from the pin header.
![](./img/IMG_8019.jpg)

Insert the shorter jumper into the two locations, JP1 and JP2, and solder it in place.
![](./img/IMG_8024.jpg)

Be careful not to let them stick together since the space between the pads is narrow. If you don't go wireless, it's fine even if they short-circuit.
![](./img/IMG_8022.jpg)


### 3.5 Soldering the reset button, slide switch, and side button
Solder buttons to three locations: Reset, Slide, and Side.
![](./img/IMG_8031.jpg)
![](./img/IMG_8027.jpg)

### 3.6 Soldering RP2040-Zero
Cut out 2-pin, 3-pin, 5-pin, 5-pin, and 6-pin connectors from the pin header.
![](./img/IMG_8034.jpg)

Insert the shorter side of the pin header into the location labeled RP2040-Zero, then place the micro controller spacer with the stepped side facing down.
![](./img/IMG_8036.jpg)

Once the RP2040-Zero is mounted, secure it with the micro controller clip.
![](./img/IMG_8040.jpg)c

Solder both sides.
![](./img/IMG_8041.jpg)
![](./img/IMG_8088.jpg)

Remove the clip. This creates a gap of about 2mm between the pin header and the RP2040-Zero.
![](./img/IMG_8052.jpg)

### 3.7 Soldering the lever button
Place the lever button on LB1 and solder it in five locations.
![](./img/IMG_8222.jpg)
Solder the left and right pads while tilting the lever with your finger.

### 3.8 Soldering Rotary Encoders
Insert the rotary encoder into R and solder it.
![](./img/IMG_8067.jpg)

### 3.9 Soldering push buttons and wheel encoders
Determine the wheel direction and assign the locations for push buttons B1 and B2, as well as wheel encoders W1 and W2.
![](./img/IMG_8069.jpg)
Soldering the low-profile pushbutton first makes it less likely to shift when soldering the wheel encoder.
![](./img/IMG_8078.jpg)

### 3.10 Functionality Verification
Insert jumper pins into the two jumper locations.
![](./img/IMG_8079.jpg)

![](./img/IMG_8086.jpg)

Ensure the slide switch is turned off.
![](./img/IMG_8082.jpg)

Connect it to your PC using a USB cable and verify that each button functions properly.
![](./img/IMG_8095.jpg)
- The reset button has no function as it is for wireless use.
- You can verify the operation of the MX socket by inserting the switch from the front or applying tweezers to the pins on either side.
- The rotation of the wheel encoder is verified using the shaft.
![](./img/IMG_8102.jpg)
- If you encounter any issues with operation, please also refer to [the Troubleshooting section.](#6-Troubleshooting).

## 4. Assembly
### 4.1 1U Wheel Encoder THQWGD001
Insert the shaft halfway into the flat surface of the wheel.
![](./img/IMG_8103.jpg)
Insert the shaft into the encoder.
![](./img/IMG_8105.jpg)
Attach the spacer and place it on the push button.
![](./img/IMG_8107.jpg)
Attach the base using 6mm screws and nuts.
![](./img/IMG_8116.jpg)
Attach the cover.
![](./img/IMG_8123.jpg)

### 4.2 Bottom plate
Place the bottom plate.
![](./img/IMG_8127.jpg)

### 4.3 Side button cover and slide switch cover
Attach the side button cover and slide switch cover into the gap.
![](./img/IMG_8130.jpg)
![](./img/IMG_8131.jpg)

### 4.4 Bottom stand
If this part of the bottom stand is clogged, remove it as shown in the image (it may be white, but this is normal).
![](./img/IMG_8135.jpg)

Place it on the bottom plate and secure it at three points with nuts and bolts.
![](./img/IMG_8138.jpg)
Use a 10mm screw for the thick section and 8mm screws for the two thin sections.

### 4.5 Bottom cover
Attach the bottom cover and secure it with 10mm screws.
![](./img/IMG_8142.jpg)
Attach the rubber feet.
![](./img/IMG_8143.jpg)

### 4.6 Encoder Cover
Install the encoder cover with the front side facing up, paying attention to the orientation.
![](./img/IMG_8145.jpg)

### 4.7 Switch plate
Place the switch plate.
![](./img/IMG_8148.jpg)
Install all switches starting from the four corners in order.
![](./img/IMG_8650.jpg)
Insert the switch pin vertically into the socket to prevent bending.
![](./img/IMG_8654.jpg)

### 4.8 Acrylic stand, acrylic plate, acrylic cover
Insert the acrylic stand into the switch plate.
![](./img/IMG_8155.jpg)
Peel off the protective film from the acrylic plate.
![](./img/IMG_8159.jpg)
Attach the acrylic cover to the switch plate so that it sandwiches the acrylic stand and acrylic plate.
![](./img/IMG_8175.jpg)
Slide the acrylic plate into place with your finger while adjusting it for smooth and easy installation.

### 4.9 Skylight knob（24mm）
Insert the nut into the gap in the stem, then tighten the 5mm screw just enough to prevent the nut from falling out.
![](./img/IMG_8147.jpg)
Tighten the screw onto the rotary encoder shaft until it cannot be removed.
![](./img/IMG_8661.jpg)
Peel off the protective sticker from the acrylic plate, insert it into the knob, and attach it to the stem.
![](./img/IMG_8724.jpg)
Position the screw head so that it fits into one of the notches.
![](./img/IMG_8730.jpg)

Just to be sure, double-check the operation and then attach the keycaps to complete the process.
![](./img/IMG_8738.jpg)
  
***

### 5. Link

For information on customizing settings such as key assignments, please see here.
- [How to Use](USAGE_EN.md)

For wireless conversion, please refer to this section.
- [Wireless Implementation Using BMP Boost](BMP_EN.md)

***

### 6. Troubleshooting
- The key isn't responding.

Please verify the diode orientation and soldering, as well as the switch socket soldering. Also, check that the switch pins are not bent.

- The slide switch is unresponsive, the rotary/wheel encoder has responsiveness issues, and none of the LEDs are lighting up.

Please verify that jumper pins are inserted into both jumpers.

- Only part of the LED lights up.

The LEDs are connected in the order shown in the image. Please check the soldering on the last LED that lights up and the first LED that does not light up. There is also a possibility that the LED is damaged.
![](./img/IMG_0387.jpg)

- The lever button is unresponsive.

Please ensure that not only the three pads in front but also the two pads on the left and right are soldered.

- The part has become loose.

Using masking tape or similar materials to enlarge the shaft or fasteners may improve the situation. Additionally, 3D-printed parts can be welded by applying a soldering iron to melt them. Using adhesive to bond them together is also acceptable.

[Back to Start Page](../README.md)
