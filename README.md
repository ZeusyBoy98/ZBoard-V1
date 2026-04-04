# ZBoard-V1
Video: https://github.com/ZeusyBoy98/ZBoard-V1/blob/main/IMG/ZBoard-V1-Video.mp4.  
The ultimate 75% wireless keyboard that fits my needs!  
Made for Hack Club Fallout.

## Zine
![zine](IMG/ZBoard-Zine.jpg)

## What does it do?
It's a 75% low profile wireless keyboard with Gateron KS33 Chocolate Switches, NuPhy COAST Twilight Keycaps, and a 3D printed shell and plate.

## Why?
Because I hate my current keyboard options. I have a Corsair K70 Core which sucks for anything other than gaming, and some old HP keyboard which doesn't register switch presses half the time. So I decided to build my own keyboard. My requirements were for it to be wireless, so that I could use it untethered, low profile & 75%, so it can fit anywere for any situation, and use switches which I really enjoy pressing. In the end, this is the design I came up with and I could not be happier.

## Motivation
I don't have a good keyboard. My options are a gaming keyboard that double presses, or a membrane keyboard that doesn't press. This should fix both those issues and be actually enjoyable to use.

## How?
In order to make this project for yourself, you'll need to purchase/3D print the items in the bill of materials below.

| Qty          | Component                 | Link                                                                                                                                                                                                                              | Price Individual (USD)        | Price Sum (USD)           |
| ------------ | ------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------- | ------------------------- |
| 100          | Diode                     | [LCSC](https://www.lcsc.com/product-detail/C917030.html?s_z=n_1N4148W)                                                                                                                                                            | 0.0057                        | 0.57                      |
| 50 (minimum) | 866k Resistor             | [LCSC](https://www.lcsc.com/product-detail/C1744629.html?s_z=n_resistor&spm=wm.fly.bg.0.xh___wm.ssy.ml.5-2-6.ent&lcsc_vid=FQVYUQZSEwBYXgdSQFYMBgJfEgcPAlFQFVNdX1VfFQAxVlNRQlBZU1NQQ1RaVDsOAxUeFF5JWBYZEEoKFBINSQcJGk4dAgUUFAk%3D) | 0.0178                        | 0.89                      |
| 50 (minimum) | 2M Resistor               | [LCSC](https://www.lcsc.com/product-detail/C3565452.html?s_z=n_resistor&spm=wm.fly.bg.2.xh___wm.ssy.ml.5-2-6.ent&lcsc_vid=FQVYUQZSEwBYXgdSQFYMBgJfEgcPAlFQFVNdX1VfFQAxVlNRQlBZU1NQQ1RaVDsOAxUeFF5JWBYZEEoKFBINSQcJGk4dAgUUFAk%3D) | 0.0346                        | 0.69                      |
| 1            | Switches                  | [Gateron](https://www.gateron.com/products/gateron-ks-33-low-profile-20-chocolate-switch?VariantsId=11140)                                                                                                                        | 39.60                         | 39.60                     |
| 1            | Hotswap Sockets           | [Gateron](https://www.gateron.com/products/gateron-low-profile-switch-hot-swap-pcb-socket?VariantsId=10234)                                                                                                                       | 11.00                         | 11.00                     |
| 1            | Stabilizers               | [Gateron](https://www.gateron.com/products/gateron-low-profile-plate-mounted-stabilizer?VariantsId=10540)                                                                                                                         | 8.00                          | 8.00                      |
| 1            | XIAO-nRF52840-SMD         | [Core Electronics](https://core-electronics.com.au/seeed-studio-xiao-nrf52840-pre-soldered-bluetooth-5-0-ble-wireless-iot-microcontroller-board.html)                                                                             | 13.31                         | 13.31                     |
| 1            | MCP23017-E_SP             | [LCSC](https://www.lcsc.com/product-detail/C647352.html?spm=wm.gwc.xh.3.cbm___wm.sxq.ssl.gwc&lcsc_vid=FQVYUQZSEwBYXgdSQFYMBgJfEgcPAlFQFVNdX1VfFQAxVlNRQlBZUlBWQlleVTsOAxUeFF5JWBYZEEoKFBINSQcJGk4%3D)                             | 3.00                          | 3.00                      |
| 1            | Heat set insert           | [Core Electronics](https://core-electronics.com.au/brass-heat-set-inserts-for-plastic-m3-x-3mm-50-pack.html)                                                                                                                      | Already owned                 | (8.39)                    |
| 1            | 5mm M3 Screw              | [Core Electronics](https://core-electronics.com.au/machine-screw-m3-5mm-length-phillips-25-pack.html)                                                                                                                             | Already owned                 | (2.24)                    |
| 1            | 1100mAh 3.7v LiPo Battery | [Core Electronics](https://core-electronics.com.au/polymer-lithium-ion-battery-1000mah-38458.html)                                                                                                                                | Already owned                 | (5.96)                    |
| 1            | Case Pieces               | CAD/ZBoard-V1-Print.3mf                                                                                                                                                                                                           | 3D printing (220g filament)   |                           |
| 1            | Keycap Set                | CAD/ZBoard-V1-Print.3mf                                                                                                                                                                                                           | 3D printing<br>(70g filament) | (Total 3D printing: 4.61) |
| 1            | PCB                       | PCB/Gerbers.zip                                                                                                                                                                                                                   |                               | 21.90                     |
| Shipping     |                           |                                                                                                                                                                                                                                   |                               | 14.07+9.53+8.60=30.59     |
| Total        |                           |                                                                                                                                                                                                                                   |                               | 131.16 (147.75)           |

In order to build this keyboard, simply look at the schematic at PCB/ZBoard V1.kicad_sch<br> 
By following this schematic you should be able to place and solder the components easily. 
### Build Guide:
1. Start by soldering the components onto the board in an order that suites you. 
2. Then click in the stabilisers to the PCB. 
3. Then 3D print the case pieces, insert the head thread inserts, and place the PCB in the case and close it. 
4. Then 3D print all the keycaps and put them on each of the keys.
5. Once the build is complete, you'll need to double press the reset button on the Seeed Xiao NRF52840 in order to enter bootloader mode. 
6. Then simply copy the firmware file Firmware/zmk.uf2 into the new drive that appears. 
7. Once the firmware finishes flashing, you should be able to go into your device's bluetooth settings and connect to the keyboard.

## Renders
![image](IMG/side-on.PNG)
![image](IMG/top-down.PNG)
![image](IMG/top-angled.PNG)

## Designing
![image](IMG/split.png)
![image](IMG/pcb.png)
![image](IMG/routing.png)