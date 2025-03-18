---
title: "Microfluidic Device"
excerpt: "Resin Printing of Microfluidic Molds" 
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/img/ExampleMicrofluidicDevice.png
  teaser: /assets/img/ExampleMicrofluidicDevice.png
--- 

# Introduction
## μFluidic Devices
- The fundamental design of microfluidic devices often involves the integration of channels, pumps, and valves on a single chip, allowing for the controlled movement and mixing of fluids. This miniaturization leads to several advantages, including reduced reagent consumption, faster reaction times, and the ability to conduct multiple analyses simultaneously. 
- Microfluidics can be categorized into three main types: continuous-flow, droplet-based, and digital microfluidics. Continuous-flow devices utilize permanently etched channels to guide fluid streams, while droplet-based systems create and manipulate discrete droplets within microchannels. Digital microfluidics, on the other hand, employs electrowetting techniques to manipulate droplets on a surface, allowing for flexible and programmable fluid handling without the need for complex channel networks. Each type of microfluidic system offers unique capabilities tailored to specific applications, such as cell sorting, biochemical assays, and environmental monitoring 

## Pinch Flow Fractionation
- Pinch flow fractionation is a powerful technique designed for the continuous separation of particles based on size, which  leverages laminar flow dynamics within microchannels to achieve size-based particle separation. The fundamental mechanism involves introducing a particle-laden fluid alongside a sheath fluid into a microchannel that narrows at a specific segment.As the flow enters the pinched segment, the particles experience a lateral force that drives them towards the channel wall. The extent of this lateral displacement is influenced by the size of the particles, with larger particles being pushed further from the center of the channel compared to smaller ones. This separation occurs as the flow transitions into a broadened segment, where the particles are allowed to spread laterally, effectively increasing the distance between particles of different sizes. The design of the microchannel, including the dimensions of the pinched and broadened segments, plays a crucial role in optimizing the separation efficiency

## Application for Sorting Small Particles
- Sorting small particles is key for point-of-care diagnostics. For example, the detection of an infection would use a microfluidic device to sort through the small particles to find the white blood cell count. This is vital for patient relief and efficient, accurate treatment plans.

# Discussion 
Why are resin-printed molds coated with parylene prior to casting the PDMS? What are hypothetical applications of your microfluidic mixer or sorter?

Why is your geometry conducive to sorting? Discuss specific dimensions (pinch width, outlet width, location of ports, etc.)

# Instructions  
How to go from the 3D printed mold to the final device:
1. **CAD model**
    - Begin by creating a detailed CAD model of the desired microfluidic device with all channels, chambers, and other microstructures required for the device's functionality.
2. **Print and cure mold**
    - Utilize a high-resolution 3D printer (in our case, a Form 4 printer) to fabricate the mold based on the CAD design. High Temp resin was chosen for its durability and resistance to extreme temperatures. 
    - After printing, the mold should undergo a curing process to solidify the material and enhance its mechanical properties. This process includes cleaning the mold with isopropyl alcohol, placing the mold into a UV-curing chamber, and repeating until the mold is free from uncured resin.
3. **Parylene device**
    - To render the 3D-printed mold biocompatible and suitable for use as a master mold for elastomeric device fabrication, deposit a thin layer of parylene—a polymer commonly used in medical device applications—onto the mold. This coating prevents leaching of toxic substances from the resin, ensuring compatibility with cell cultures.​
4). **Cast PDMS**
    - Mix polydimethylsiloxane (PDMS) elastomer and curing agent in the appropriate ratio (commonly 10:1 by weight) and degas the mixture to remove air bubbles.​
    - Pour the degassed PDMS over the parylene-coated mold, ensuring complete coverage of all microfeatures.​
    - Cure the PDMS by placing it in an oven at the recommended temperature (typically 60°C) for the specified duration to achieve complete polymerization.
5). **Plasma bond glass slide**
    - Once cured, carefully peel the PDMS layer from the mold, exposing the microfluidic structures.​
    - Clean both the PDMS surface and the target glass slide thoroughly to remove any contaminants.​
    - Subject both surfaces to oxygen plasma treatment to activate them, which facilitates strong bonding.​
    - Immediately bring the activated PDMS and glass surfaces into contact, applying gentle pressure to ensure uniform adhesion and prevent the formation of air gaps.

# CAD Model

<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH286ddQT78850c0d8a4e82600be13efa8e4?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

---



