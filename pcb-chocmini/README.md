# Choc Mini PCB

<img width="600" alt="chocmini-pcb" src="https://user-images.githubusercontent.com/800930/230826789-395d313c-e982-46a3-a88b-7a79c3fea62f.png">

## JLCPCB File
`artpad_mini.zip`

![artpad-1](https://user-images.githubusercontent.com/800930/230826857-0c972689-6df6-4ba3-a53a-51002b357275.jpg)

## BOM
| Part | Count | Notes |
|------|-------|-------|
| Choc Mini Switches | 15 - 16 | 
| Choc Keycaps | 15 - 16 | [wrk pure](https://worklouder.cc/shop/wrk-pure/)
| 1N4148 SMD Diode | 16 | 
| SK6812 MINI-E RGB LED | 16 | [Link](https://www.diykeyboards.com/parts/electronics/product/sk6812-mini-e-rgb-led)
| SD1306 OLED | 1 | [Link](https://www.diykeyboards.com/parts/electronics/product/p128x32-oled-lcd-display-ssd1306-driver)
| EC11 Rotary Encoder | 1 |
| Rotary Encoder Knob | 1 |
| Mill-Max 315 low-profile headers (1x12) | 2 | [Link](https://www.littlekeyboards.com/products/ultra-low-profile-sockets?variant=39323794800707)
| Mill-Max round pins | 24 | 
| Elite-C controller | 1 |

## Instructions

The assembly is pretty straight forward.  In order to keep things low profile, you should opt for the SMD diodes since through hole diodes will add to the overall thickness.  The LEDs have one pin with a corner cut off.  Line that pin up with pad that has the triangle printed next to it.

For my build, I used low-profile headers for the Elite-C, but I didn't bother with headers for the OLED since it would be too difficult to get the height exactly right.  I just put a piece of electrical tape under the OLED and placed it right on top of the Elite-C so that both were touching.  Then soldered it in while holding it in place.
