# Lab 5: Alberto Molina Muros

### Analog-to-Digital Conversion

1. Complete table with voltage divider, calculated, and measured ADC values for all five push buttons.

   | **Push button** | **PC0 voltage** | **ADC value (calculated)** | **ADC value (measured)** | **ADC value (measured, hex)** |
   | :-: | :-: | :-: | :-: | :-: |
   | Right  | 0&nbsp;V     | 0   | 0   | 0 |
   | Up     | 0.495&nbsp;V | 101 | 99  | 63  |
   | Down   | 1.203&nbsp;V | 246 | 257 | 101  |
   | Left   | 1.969&nbsp;V | 403 | 410 | 199  |
   | Select | 3.113&nbsp;V | 651 | 640 | 27F  |
   | none   | 5&nbsp;V     | 1023 | 1023 | 3FF  |

### Temperature meter

Consider an application for temperature measurement. Use analog temperature sensor [TC1046](http://ww1.microchip.com/downloads/en/DeviceDoc/21496C.pdf), LCD, and a LED. Every 30 seconds, the temperature is measured and the value is displayed on LCD screen. When the temperature is too high, the LED will turn on.

2. Draw a schematic of temperature meter. The image can be drawn on a computer or by hand. Always name all components, their values and pin names!

   ![Lab 5 Schematic](https://user-images.githubusercontent.com/114478568/198685627-e2bad498-89a0-447d-9241-6fe5dcf403b6.jpg)


3. Draw two flowcharts for interrupt handler `TIMER1_OVF_vect` (which overflows every 1&nbsp;sec) and `ADC_vect`. The image can be drawn on a computer or by hand. Use clear descriptions of individual algorithm steps.

   ![Lab 5 Schematic (1)](https://user-images.githubusercontent.com/114478568/198685644-68556c3b-4ab7-475e-82a1-7848b7456769.jpg)

