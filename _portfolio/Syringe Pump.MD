---
title: "Syringe Pump"
excerpt: "This DIY syringe pump is motor-driven and capable various flow rates and syringe diameters."
header:
  image: /assets/img/SP Teaser.png  
  teaser: /assets/img/CAD Model.png
gallery:
  - url: /assets/img/CAD Model.png
    image_path: assets/img/CAD Model.png
    alt: "CAD image"
  - url: /assets/img/RL Model.png
    image_path: assets/img/RL Model.png
    alt: "Final Product"
  - url: /assets/img/Circuit.png
    image_path: assets/img/Circuit.png
    alt: "Circuitry"
---

# Quick Product Overview

The syringe pump features a stepper motor-driven lead screw for precise operation and supports flow rates adjustable via an Arduino program, accommodating decimal values and syringe diameters from 5 mL to 20 mL without requiring fastener adjustments. It includes a status LED (green for running, yellow for paused, red for empty), a latching start/pause button, and a limit switch to halt motion when the plunger reaches its end. Designed with short, clean electrical wiring and protected components, the pump integrates all core parts into a single unit for user safety and ease of use. It also features unique branding, uses fasteners or snap fits for assembly, and is easily disassembled for reuse without damaging components.


# Operating Instructions

The syringe pump should be operated by adhering to the following steps:
1. Ensure that the power supply is connected to the syringe pump. The LED light should be blue.
2. Place the syringe in the supports with the tip that outputs liquid at the far right end.
3. Adjust the flow rate in the Arduino code at line 18.
4. Input the size of syringe into the Arduino code at line 19.
5. To begin dispensing liquid from the syringe, press the red power button to be lowered. This is placed at the bottom left of the front panel of the enclosure. The LED light should be green during liquid dispense.
6. To pause the liquid dispense, press the power button again so it is raised. The LED light should show blue.
7. To continue dispensing the liquid, press the power button again so it stays lowered. 
8. Once all liquid possible has been dispensed, the LED will turn red and the actuation will stop.

# CAD Model

<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH286ddQT78850c0d8a47e94ace65a8e8875?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

# Off-the-Shelf-Parts:

| Part Name with Link                              | Quantity of Part  |
| ------------------------------------------------ | --------------------------------------------------------------------------------- |
| [250 mm lead screw with 2 mm pitch and 2 mm lead](https://www.amazon.com/dp/B07R1H5ZMV/ref=cm_sw_em_r_mt_dp_0YZ13D4HQBGW2Z86PBV1?_encoding=UTF8&psc=1) | 1 |
| [250 mm lead screw with 2 mm pitch and 8 mm lead](https://www.amazon.com/gp/product/B0B8RKN89V?ie=UTF8&th=1&linkCode=sl1&tag=drd0cf-20&linkId=bb4eefbbfff880704d7cd0784b1af8c0&language=en_US&ref_=as_li_ss_tl) | 1 |
| [1/4" x 8mm Flexible Coupling](https://us.openbuilds.com/1-4-x-8mm-flexible-coupling/) | 1 |
| [200 mm linear rod with 8 mm diameter](https://www.amazon.com/dp/B07MPGWJMS/ref=cm_sw_em_r_mt_dp_X5AQS0ES7JH8JG83AAZ3) | 2 |
| [LM8UU Linear bearing for 8 mm diameter rod](https://www.amazon.com/gp/product/B087WPGQ8T/ref=ppx_yo_dt_b_asin_image_o00_s00?ie=UTF8&psc=1) | 2 |
| [2040 Aluminum Extrusion 1' Length ](https://us.openbuilds.com/v-slot-20x40-linear-rail/) | 1 |
| [Nema 17 Stepper Motor](https://www.amazon.com/gp/product/B07LF898KN/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&th=1) | 1 |
| [MEAN WELL RQ-65D AC-DC Power Supply Quad Output 5V 12V 24V 12V 4 Amp](https://www.amazon.com/dp/B005T9HGLI/ref=cm_sw_em_r_mt_dp_A8CZ056TM52EJGZTGZGR?_encoding=UTF8&psc=1) | 1 |
| [Arduino Uno](https://www.amazon.com/dp/B007R9TUJE/ref=cm_sw_em_r_mt_dp_TY8JGK0CJD1JEJM4BNNJ) | 1 |
| [A4988 Stepper Driver](https://www.amazon.com/dp/B01FFGAKK8/ref=cm_sw_em_r_mt_dp_V0YKTYKDWMR8WHTKA53T?_encoding=UTF8&psc=1) | 1 |
| [Small Breadboard](https://www.amazon.com/dp/B07R1H5ZMV/ref=cm_sw_em_r_mt_dp_0YZ13D4HQBGW2Z86PBV1?_encoding=UTF8&psc=1) | 1 |
| [Panel Mount Latching Push Buttons](https://www.amazon.com/dp/B07XTBL1NP?smid=A2NNH5C5IP9N3O&linkCode=sl1&tag=drd0cf-20&linkId=43b42a7cb2a088ebd85d65cb9da46725&language=en_US&ref_=as_li_ss_tl&th=1) | 1 |
| [Limit Switch](https://www.amazon.com/gp/product/B073TYWX86/ref=ppx_yo_dt_b_asin_image_o01_s00?ie=UTF8&psc=1) | 1 |
| [RGB Common Cathode LED](https://www.amazon.com/dp/B0194Y6MW2/ref=cm_sw_em_r_mt_dp_FW3CFQT7ZGFQ2R04N6G3?_encoding=UTF8&psc=1) | 1 |

# 3D Printed Parts:
| Part Name | Part Function |
| --------- | -------------------------------- |
| Carriage, Coupler | Mount the motor to the aluminum extrusion |
| End and Tips Supports | Hold the syringe |
| Enclosure | Enclose the electronics and brackets |


## Arduino Code for Proper Liquid Dispensal can be found here: [Arduino Code](https://github.com/segatti21/Syringe-Pump/blob/main/SP_ArduinoCode.html)

{% include gallery caption="Photos from throughout project" %}
