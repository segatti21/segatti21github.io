---
title: "Microfluidic Device"
excerpt: "Resin-printed mold for a microfluidic device"
subtitle: "The math ([Geometries](#geo)), the idea ([CAD Model](#CAD-Model)), demonstrated outcome ([Outcome](#DIA)), and everything else about the resin-printed mold for the microfluidic device project!"
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/img/MOLD.png
  teaser: /assets/img/MOLD.png
gallery:
  - image_path: assets/img/MOLD.png
  - image_path: assets/img/DEVICE.png
  - image_path: assets/img/CADDrawing.png

---  
**The math ([Geometries](#geo)), the idea ([CAD Model](#CAD-Model)), demonstrated outcome ([Outcome](#DIA)), and everything else about the resin-printed mold for the microfluidic device project!**
{: .subtitle}

## Introduction
### μFluidic Devices
The fundamental design of microfluidic devices often involves the integration of channels, pumps, and valves on a single chip, allowing for the controlled movement and mixing of fluids. This miniaturization leads to several advantages, including reduced reagent consumption, faster reaction times, and the ability to conduct multiple analyses simultaneously. 
Microfluidics can be categorized into three main types: continuous-flow, droplet-based, and digital microfluidic systems. Continuous-flow devices utilize permanently etched channels to guide fluid streams, while droplet-based systems create and manipulate discrete droplets within microchannels. Digital microfluidics, on the other hand, employs electrowetting techniques to manipulate droplets on a surface, allowing for flexible and programmable fluid handling without the need for complex channel networks. Each type of microfluidic system offers unique capabilities tailored to specific applications, such as cell sorting, biochemical assays, and environmental monitoring. 

Example of a commercial device in action:
<iframe width="560" height="315" 
    src="https://www.youtube.com/embed/45m8hGkdYrw" 
    frameborder="0" 
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
    allowfullscreen>
</iframe>

### Pinch Flow Fractionation
Pinch flow fractionation is a powerful technique designed for the continuous separation of particles based on size, which  leverages laminar flow dynamics within microchannels to achieve size-based particle separation. This microfluidic device operates using laminar flow, as shown in the figure below. The fundamental mechanism involves introducing a particle-laden fluid alongside a sheath fluid into a microchannel that narrows at a specific segment. As the flow enters the pinched segment, the particles experience a lateral force that drives them towards the channel wall. The extent of this lateral displacement is influenced by the size of the particles, with larger particles being pushed further from the center of the channel compared to smaller ones. This separation occurs as the flow transitions into a broadened segment, where the particles are allowed to spread laterally, effectively increasing the distance between particles of different sizes. The design of the microchannel, including the dimensions of the pinched and broadened segments, plays a crucial role in optimizing the separation efficiency.

### Application for Sorting Small Particles
Sorting small particles is crucial for point-of-care diagnostics. For example, detecting an infection may involve using a microfluidic device to analyze small particles and determine the white blood cell count.This is vital for patient relief and efficient, accurate treatment plans. Although all of these applications may not apply to the device I have created, some [hypothetical applications](#apps) that can be beneficial for use.

---
## Instructions  
How to go from the 3D printed mold to the final device:
1. **CAD model**
    - Begin by creating a detailed [CAD Model](#CAD-Model) of the desired microfluidic device, including all channels, chambers, and other microstructures required for the device's functionality. Ensure dimensions are based on accurate calculations.
2. **Print and cure mold**
    - Utilize a high-resolution 3D printer (in our case, a Form4 printer) to fabricate the mold based on the CAD design. High Temp resin was chosen for its durability and resistance to extreme temperatures. 
    - After printing, the mold should undergo a curing process to solidify the material and enhance its mechanical properties. This process includes cleaning the mold with isopropyl alcohol, placing the mold into a UV-curing chamber, and repeating until the mold is free from uncured resin.
3. **Parylene device**
    - To render the 3D-printed mold biocompatible and suitable for use as a master mold for elastomeric device fabrication, deposit a thin layer of parylene—a polymer commonly used in medical device applications—onto the mold. This coating prevents leaching of toxic substances from the resin, ensuring compatibility with cell cultures.​ See the reasoning for this in the '[Benefits](#benefits)' in Discussion section.
4. **Cast PDMS**
    - Mix polydimethylsiloxane (PDMS) elastomer and curing agent in the appropriate ratio (commonly 10:1 by weight) and degas the mixture to remove air bubbles.​
    - Pour the degassed PDMS over the parylene-coated mold, ensuring complete coverage of all microfeatures.​
    - Cure the PDMS by placing it in an oven at the recommended temperature (typically 60°C) for the specified duration to achieve complete polymerization.

After this, the resulting device can be tested to deem the success of the design and calculations.

{% include gallery caption="Visuals of the resin-printed mold (left), the casted device (middle), and a general CAD drawing (right)" %}

---
## Discussion 

### Benefits of Coating Resin-printed Molds with Parylene Before Casting the PDMS: <a id="benefits"></a>

| Reason                     | Explanation |
|----------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Prevents PDMS Adhesion** | Resin molds are naturally rough and reactive, leading to PDMS sticking. Parylene creates a smooth, non-stick coating, reducing adhesion and making demolding easier. |
| **Enhances Mold Durability** | Uncoated resin molds degrade after multiple PDMS castings due to mechanical stress and PDMS curing reactions. Parylene is chemically inert and wear-resistant, extending the mold’s lifespan. |
| **Improves Surface Quality** | Resin-printed molds often have microscopic imperfections from the printing process. Parylene forms a uniform, conformal layer, smoothing out minor defects and leading to higher-quality PDMS replicas. |
| **Chemical Resistance** | Some resin materials can react with PDMS curing agents, leading to incomplete curing or surface inhibition. Parylene is chemically stable, acting as a protective barrier against such reactions. |
| **Hydrophobic Properties** | PDMS prefers hydrophobic surfaces for better replication of microstructures. Parylene’s hydrophobicity helps maintain fine details in microfluidic or soft lithography applications. |

### Hypothetical Applications of this Microfluidic Device: <a id="apps"></a>

| Application Field  | Device Capacity | Outcome | Why It's Important |
|--------------------|-------------------------------------|----------------------|-------------|
| Cancer Diagnostics | Can separate circulating tumor cells from blood | Early cancer detection | [Early Detecting Saves Lives](https://www.cancerresearch.org/blog/february-2025/early-detection-saves-lives-the-essential-cancer-screenings-you-cant-afford-to-skip#:~:text=The%20earlier%20a%20cancer%20is,cancer%20prevention%20and%20early%20detection.) |
| Immunity | Can separate white blood cells and red blood cells | Understand a patient's immune health | [Cancer-Immune Interations](https://pmc.ncbi.nlm.nih.gov/articles/PMC4743529/#:~:text=It%20is%20the%20ability%20to,of%20flow%20in%20microfluidic%20systems.) |
| Drug Dosing | Can separate drug nanoparticles | Keeps dosage formation consistent | [Pharmacy Calculations](https://www.ncbi.nlm.nih.gov/books/NBK560924/) |
| Filtration Systems | Filter out chemical particulates from wastewater | Pollution Control | [Water Treatment](https://www3.epa.gov/npdes/pubs/bastre.pdf) |

### Geometry Explained <a id="geo"></a>

By utilizing the pinched flow fractionation, difference in particle size can determine separation. 

1. *Pinch Width (pw)- 0.50 mm*
  - Allows guidance of 125–150 μm and 425–500 μm particles into separate flow paths 
  - On the smaller side of optimal size, but needs to be larger than the largest particle that should go through
2. *Outlet Width- 3.655mm*
  - Small particles will travel to the top (17.6mm - 15.355mm from the bottom)
  - Large Particles will travel to the middle outlet (15.355mm - 12.60 mm from the bottom)
  - All others should go into the final and largest outlet at the bottom
  - This was found using the outlet position equation: Y0 = (pw - D/2) * (bw/pw)
3. *Port Location- Staggered*
  - Dr. Florian gave a base model that ensures sample flow at a velocity that maintains laminar conditions, avoids recombination, and any back pressure
4. *Channel Depth- 
  - To ensure flow continues
5. *Broad Width (bw)- 25 mm*
  - Ensures chaotic advection will occur by allowing for more space to do so while also keeping the flow constant (ideally)
6. *Channel Width- 19 mm*
  - This leaves room for the buffer zone while maximizing the space that the liquid can enter

### Device Functionality <a id="DIA"></a>
Despite sub-optimal testing conditions, the device still showed proper separation of particles. The smaller orange particles went to the highest outlet channel, and some larger purple particles went into the middle outlet channel.


## CAD Model <a id="CAD-Model"></a>

<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH286ddQT78850c0d8a4e82600be13efa8e4?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>
