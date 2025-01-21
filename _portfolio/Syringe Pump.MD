---
title: "Syringe Pump"
excerpt: "This DIY syringe pump is motor-driven and capable various flow rates and syringe diameters."
header:
  image: /assets/img/Cyber-Scooter-Banner.jpg
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

# Arduino Code for Proper Liquid Dispensal

[Arduino Code]([https://github.com/segatti21/Syringe-Pump/blob/main/Syringe_Pump_Arduino_Code.ino]).

{% include gallery caption="Photos from throughout project" %}
