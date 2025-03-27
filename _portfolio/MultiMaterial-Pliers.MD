---
title: "MultiMaterial-Pliers"
excerpt: "3D printed needle-nose pliers with flexible material for the spring mechanism" 
header:
  image: /assets/img/plieroff.png
  teaser: /assets/img/plieroff.png
gallery:
  - image_path: assets/img/plieroff.png
  - image_path: assets/img/plierside.png
   
---
The objective of this project is to leverage flexible and rigid materials to create a spring-loaded tool that works straight off the printer—or with minimal manual assembly—without requiring screws, glue, or post-processing. This can be done using print-in-place [(PIP)](#pip) techniques which can be used in a variety of [applications](#apps) and with different [materials](#mats).

### PIP  <a id="pip"></a>
PIP is a 3D printing technique that enables the creation of fully assembled, movable mechanisms directly on the print bed. Rather than printing each component separately and assembling them later, all parts are designed with precise tolerances and printed as a single object. Once the print is removed from the bed, it’s ready to be used without need for glue, screws, etc. These designs rely on built-in clearances between moving parts and often include clever geometries to allow rotation, flexing, or sliding.

### PIP Applications <a id="apps"></a>

| Application                     | Where to be Used |
|----------------------------|----------------------------------------|
| **Hinges and Joints** | foldable structures or deployable mechanisms |
| **Functional Toys** | articulated dragons, snakes, or puzzles |
| **Snap-fit Tools** | wrenches, tweezers, clamps, ... [pliers!](#CAD-Model) |
| **Integrated Enclosures** | rotating lids or sliding panels |

### Best Material Combinations for PIP <a id="mats"></a>
- *Rigid and Flexible Material* such as [PLA and TPU](#printset), respectively, enables moving parts where rigid sections provide structure and TPU acts as a spring, hinge, or flex joint.
- *PLA Blends* that use different colors or brands can help identify part boundaries or improve layer separation in post-processing if movement is restricted


## CAD Model
### Plier Handles and Clamps: <a id="CAD-Model"></a>
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH286ddQT78850c0d8a43dd46deefdbc450c?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

### Center Flex Piece:
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH286ddQT78850c0d8a41f54c77e74ac39c8?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

## Design and Iterative Process 

To ensure the PLA (rigid) components could snap into secure place with the center piece, three grooves on each side (12 total) were used. These grooves had both vertical and horizontal components in order to increase the stability and connection. Additionally, the length of the center piece was set to be equal to that of the base of the clamps and the handle so it aligned accurately. 

### Issues Encountered
Initially, the pliers were too thin: a 4 millimeter extrusion. The depth was too small relative to the overall length of the handles and clamps. This meant the support in the center could not keep it stable, which made each squeeze of the pliers shaky. From here, a few avenues were explored:

| Alteration | Outcome | Example |
| ----------- | ------- | ------- |
| Smaller overall size by decreasing lengths of clamps and handles | Weaker connection to the center piece | <img src="https://raw.githubusercontent.com/segatti21/segatti21github.io/main/assets/gif/small.gif" alt="Smaller Pliers" |
| Varying infill and perimeter [print settings](#printset) of the center piece | Found a balance between flexibility and security | <img src="https://raw.githubusercontent.com/segatti21/segatti21github.io/main/assets/img/infills.png)" alt="Infills" |
| Altering the handle length and angles | Handles too long touched too soon and prevented complete clamping | <img src="https://raw.githubusercontent.com/segatti21/segatti21github.io/main/assets/img/longpliers.png)" alt="Longer Handles" |

## Relevant Plier Specifications
As shown below, the ratio of handles to clamps was around 4:3. The distance to close to ensure a needle-point end is around 15mm. There is ample space between and high enough angles within the handles to allow for the clamps to meet at the end. These ensure that the resistor with a wire lead of around 0.7mm and a body diameter of around 3 mm will be able to be picked up. 

<img src="https://raw.githubusercontent.com/segatti21/segatti21github.io/main/assets/img/PlierDrawing.png" alt="Minimal Plier Specifications Drawing" style="width:60%; max-width:500px;" />

## Print Settings <a id="printset"></a>
This combination led to the optimal center piece for balancing security and flexibility:
- Infill: 12%
- Perimeters: 3
- No Top or Bottom Shell

<img src="https://raw.githubusercontent.com/segatti21/segatti21github.io/main/assets/img/centerprint.png" alt="Picture of Print Settings" style="width:60%; max-width:500px;" />

## Picture Gallery
{% include gallery caption="The pliers from two different views" %}

## Pliers in Action!
<img src="https://raw.githubusercontent.com/segatti21/segatti21github.io/main/assets/gif/PliersResist.gif" alt="Pliers Picking Up Resistor" style="width:120%; max-width:900px;" />

Here you can see the pliers picking up resistors and manipulating them in real time.
An unskilled, unpracticed user (me) could use the pliers to move 14 resistors in 30 seconds. 
