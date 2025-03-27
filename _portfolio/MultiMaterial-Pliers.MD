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
PIP is a 3D printing technique that enables the creation of fully assembled, movable mechanisms directly on the print bed. Rather than printing each component separately and assembling them later, all parts are designed with precise tolerances and printed as a single object. Once the print is removed from the bed, it’s ready to be used without needed glue, screws, etc. These designs rely on built-in clearances between moving parts and often include clever geometries to allow rotation, flexing, or sliding.

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
Initally, the pliers were too thin: a 4 millimeter extrusion. The depth was too small compared to the overall length of the handles and clamps. This meant the support in the center could not keep it stable, which made each squeeze of the pliers shaky. From here, a few avenues were explored:

| Alteration | Outcome | Example |
| ----------- | ------- | ------- |
| Smaller overall size by decreasing lengths of clamps and handles | Less secure in connection to the center piece | [25% Scaled Down](/assets/img/smallpliers.png) |
| Varying infill and perimeter [print settings](#printset) of the center piece | Found a balance between flexibility and security | [Various Infills](/assets/img/infills.png) |
| Altering the handle length and angles | Handles too long touched too soon and prevented complete clamping | [Longer Handles](/assets/img/longpliers.png) |

## Relevant Plier Specifications

![Minimal Plier Specifications Drawing](/assets/img/PlierDrawing.png)

## Print Settings <a id="printset"></a>
This combination led to the optimal center piece for balancing security and flexibility:
- Infill: 12%
- Perimeters: 3
- No Top or Bottom Shell

![Picture of Print Settings](https://raw.githubusercontent.com/username/repo/main/assets/img/centerprint.png)

## Picture Gallery
{% include gallery caption="The pliers from two different views" %}

## Pliers in Action!
![Pliers Picking Up Resistors](/assets/gif/PliersResist.gif)
Here you can see the pliers picking up resistors and moving them in real time.
When an unskilled, unpracticed user (me) could use the pliers to move 14 resistors in 30 seconds. 


