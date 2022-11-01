# Lab 5: INSERT_YOUR_FIRSTNAME INSERT_YOUR_LASTNAME

### Analog-to-Digital Conversion

1. Complete table with voltage divider, calculated, and measured ADC values for all five push buttons.

   | **Push button** | **PC0[A0] voltage** | **ADC value (calculated)** | **ADC value (measured)** | **ADC value (measured, hex)** |
   | :-: | :-: | :-: | :-: | :-: |
   | Right  | 0&nbsp;V     | 0    | 0   | 0     |
   | Up     | 0.495&nbsp;V | 101  | 99  | 0x65  |
   | Down   | 1.203&nbsp;V | 246  | 257 | 0xF6  |
   | Left   | 1.969&nbsp;V | 403  | 410 | 0x193 |
   | Select | 3.181&nbsp;V | 650  | 640 | 0x28A |
   | none   | 5            | 1023 |  -  | 0x3FF |

### Temperature meter

Consider an application for temperature measurement. Use analog temperature sensor [TC1046](http://ww1.microchip.com/downloads/en/DeviceDoc/21496C.pdf), LCD, and a LED. Every 30 seconds, the temperature is measured and the value is displayed on LCD screen. When the temperature is too high, the LED will turn on.

2. Draw a schematic of temperature meter. The image can be drawn on a computer or by hand. Always name all components and their values.

//use the proper symbol (resistnce...) precise value, name, wich pin I use...

   ![IMG_1258](https://user-images.githubusercontent.com/115087529/199303687-3312442b-2a25-4117-9ad9-56feb69cf34d.jpg)
]()

3. Draw two flowcharts for interrupt handler `TIMER1_OVF_vect` (which overflows every 1&nbsp;sec) and `ADC_vect`. The image can be drawn on a computer or by hand. Use clear descriptions of the individual steps of the algorithms.

   ![IMG_1257](https://user-images.githubusercontent.com/115087529/199303853-6d029931-4d54-44c5-ae8f-a8fca6cb3433.jpg)
]()
