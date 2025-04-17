---
title: "Bike Phone Mount/Holder"
excerpt: "An application of Top-Down Modeling" 
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: assets/img/TModel.png
  teaser: assets/img/TModel.png
---
### This project utilizes [Top-Down Modeling](#td) to create a versatile, secure phone holder for a bike or scooter handle that is compatible. A video walking through the outcome can be seen directly below, and further details are throughout this page.

<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH286ddQT78850c0d8a4e5bb1a6017753046?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

## Description of Top-Down Modeling <a id="td"></a>

Top-down modeling is a powerful CAD design technique where the overall geometry and design intent of an assembly are defined at the top level before individual parts are created. This contrasts with bottom-up modeling, where parts are designed in isolation and later assembled. In top-down modeling, reference geometry such as planes, axes, and master sketches are established first and used as a foundation for all components, which are created in context to ensure fit and function.

For this project, top-down modeling was essential to ensure precise alignment between the phone, handlebars, and rotating holder components. I began by modeling the handlebar as a fixed reference component using real-world measurements (25.4 mm clamp diameter, 22.2 mm grip diameter, 60 mm long). Then, I imported a CAD model of my phone and established a comfortable viewing angle. From there, I designed the bracket, cradle, and detent mechanism in place, using as-built joints to simulate real-world motion and alignment. This approach allowed for easy modifications and ensured all [components](#parts) worked seamlessly [together](#togeth).

## Design Rationale

The design features a rotating phone cradle attached to a handlebar bracket via a [detent rotation mechanism](#detent). This mechanism uses a 3D-printed spring-loaded ball and corresponding notches to create tactile “clicks” when rotating 45 degrees. The rotation mechanism worked effectively after parameter tuning for spring force and notch depth, providing enough resistance to prevent unintended rotation while still being easy to adjust by hand.

To account for 3D printing tolerances, I adjusted clearances, diameters, and notch widths. For example, the hole for phone side clamp insertions were designed with a 0.3 mm clearance to account for filament expansion and blips. Additionally, tolerances were added to ensure the spring could compress without jamming, and the detent could engage firmly.

The FFF printer was used for the prototype due to accessibility and rapid iteration. For the side clamps and base of the phone holder, TPU was used. This ensured more elastic properties which allowed ease of side clamps arm insertion into the grooves of the center holder. Since the detent spring holder and bike handle brackets needed to remain stiff and firm, PLA was used for those two components. 

## Assembly and Use Instructions
This tool-free installation makes the design highly user-friendly and adaptable for bikes or scooters that need simple detachment and attachment.

### First Time Assembly:
1. **Place Heat Inserts where Necessary**: Heat inserts need to be secured in the four holes on the [bike brackets](#secdet) to ensure it stays clamped onto the bike. Also, one needs to be placed into the hole on the cover of the detent cylinder because this allows the end of a secure screw catch the cylindrical groove on the detent spring side. This will ensure the phone holder will remain attached to the bike brackets.
2. **Insert the Detent Mechanism**: Attach the spring with the [detent ball](#detent) into the cavities made to hold them. Ensure the spring has the ability to compress enough to where the ball can be fully detracted into the cavity, yet fully come out when tension is released as shown [below](#detgif).

### Day-to-Day Use:
1. **Mount the Bracket**: Attach the handlebar bracket to your bike using M5 x 25 mm fasteners aligned with the heat-set inserts. The bracket's inner diameter should align with the handlebar’s 22.2 mm or 25.4 mm diameter -- as it can fit either -- clamp area.
2. **Attach the Phone Cradle**: Align the [center phone holder](#center)'s base -- the detent cylinder -- with the designated cylindrical hole in the [bike bracket extension](#secdet). Look to put the detent ball in line with the cylinder notch for easier insertion, then fully place inside. Align the M3 × 1 mm screw with the heat insert in the covering cylinder of the center piece, then secure it. You should feel a click when [rotating the phone cradle between landscape and portrait orientation](#disp).
3. **Place Your Phone**: Place your phone in the center base by securing the top and bottom under the lips while keeping the side clamps out wide, not touching the phone. Push the side extensions toward one another as you slide the clamp closer to the phone. Stop once the phone can no longer move and your phone is securely gripped. No tools are required for this step.


## Printing Technology Used

- **Bracket and Detent Mechanism**: These were printed using PLA to offer enough stiffnessyet fine detail for the ~ 2 mm or less features.
- **Phone Holder**: These parts were printed separately with TPU to provide greater flexibility and wear resistance, as well as more forgiving interaction with the phone. The downside with this was the extensive support material that was both tedious and difficult to remove.

---

## CAD Model of the Phone Holder with Phone Inside

<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH286ddQT78850c0d8a47f0a9aa554930934?mode=embed" width="800" height="600" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

---
## Rotation Explained <a id="detent"></a>

### Internal Rotation Mechanisms

Below is the CAD model sliced to view what is seen within the device:

<img src="https://raw.githubusercontent.com/segatti21/segatti21github.io/main/assets/img/detentmech.png" alt="Sliced View Showing Detent" style="width:60%; max-width:500px;" />

Here is a demonstration of the mechanism as the Phone Holder Rotates:  <a id="detgif"></a>

<div style="width:500px;max-width:100%;"><div style="height:0;padding-bottom:78.2%;position:relative;"><iframe width="500" height="391" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameBorder="0" src="https://imgflip.com/embed/9r2jn8"></iframe></div><p><a href="https://imgflip.com/gif/9r2jn8">via Imgflip</a></p></div>

### External Outcome  <a id="disp"></a>

Here are real life showcases of the mechanism at work:

<div style="width:260px;max-width:100%;"><div style="height:0;padding-bottom:177.69%;position:relative;"><iframe width="260" height="462" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameBorder="0" src="https://imgflip.com/embed/9r2mdt"></iframe></div><p><a href="https://imgflip.com/gif/9r2mdt">via Imgflip</a></p></div>

<div style="width:260px;max-width:100%;"><div style="height:0;padding-bottom:177.69%;position:relative;"><iframe width="260" height="462" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameBorder="0" src="https://imgflip.com/embed/9r2miu"></iframe></div><p><a href="https://imgflip.com/gif/9r2miu">via Imgflip</a></p></div>

---

## Security in Position

Notice how despite the twisting and shaking, in remains in tact and in the vertical position:
<div style="width:260px;max-width:100%;"><div style="height:0;padding-bottom:177.69%;position:relative;"><iframe width="260" height="462" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameBorder="0" src="https://imgflip.com/embed/9r2mkl"></iframe></div><p><a href="https://imgflip.com/gif/9r2mkl">via Imgflip</a></p></div>

---

## CAD Model in Isolation <a id="togeth"></a>

<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH286ddQT78850c0d8a413d9274d3ca5fc37?mode=embed" width="800" height="600" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

---

## Picture of Printed Model

<img src="https://raw.githubusercontent.com/segatti21/segatti21github.io/main/assets/img/inRL.png" alt="Sliced View Showing Detent" style="width:60%; max-width:500px;" />

---

## Individual Components <a id="parts"></a>

### Center Phone Holder with Detent Cylinder <a id="center"></a>
<img src="https://raw.githubusercontent.com/segatti21/segatti21github.io/main/assets/img/centerclamps.png" alt="Center of Phone Holder" style="width:60%; max-width:500px;" />

### Side Clamps for adjustable security <a id="sides"></a>
<img src="https://raw.githubusercontent.com/segatti21/segatti21github.io/main/assets/img/sideclamps.png" alt="Phone Clamps" style="width:60%; max-width:500px;" />

### Handlebar Security Brackets: Detent Side <a id="secdet"></a>
<img src="https://raw.githubusercontent.com/segatti21/segatti21github.io/main/assets/img/detentside.png" alt="Detent Side of Handle Bracket" style="width:60%; max-width:500px;" />

### Handlebar Security Brackets: Plain Side <a id="secplain"></a>
<img src="https://raw.githubusercontent.com/segatti21/segatti21github.io/main/assets/img/plainside.png" alt="Plain Side of Handle Bracket" style="width:60%; max-width:500px;" />

-- 
## Overview
Finally, here are various perspectives of the assembled design in CAD as an overview:

<img src="https://raw.githubusercontent.com/segatti21/segatti21github.io/main/assets/img/Rmodel.png" alt="Sliced View Showing Detent" style="width:60%; max-width:500px;" />
<img src="https://raw.githubusercontent.com/segatti21/segatti21github.io/main/assets/img/LModel.png" alt="Sliced View Showing Detent" style="width:60%; max-width:500px;" />
<img src="https://raw.githubusercontent.com/segatti21/segatti21github.io/main/assets/img/BModel.png" alt="Sliced View Showing Detent" style="width:60%; max-width:500px;" />
<img src="https://raw.githubusercontent.com/segatti21/segatti21github.io/main/assets/img/UModel.png" alt="Sliced View Showing Detent" style="width:60%; max-width:500px;" />
<img src="https://raw.githubusercontent.com/segatti21/segatti21github.io/main/assets/img/TModel.png" alt="Sliced View Showing Detent" style="width:60%; max-width:500px;" />
