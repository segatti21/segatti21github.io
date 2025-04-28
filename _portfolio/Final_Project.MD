---
title: "Final Project: Solder Station Organizer"
excerpt: "Use of Generative Design to create an aid for the soldering iron station of the Digital Fabrication space" 
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: assets/img/solderin.png
  teaser: assets/img/solderin.png
---

### After choosing the third path, Digital Fabrication Aid, of the Generative Design Final Project for CHBE 4200, the idea of a new solder iron holder that can [hold the iron](#hold), [hold the solder spools](#spool), [hold new soldering tips](#tips), and [hold solder cleaning wire](#wire) came to mind. 

--- 

## Overview of the Part and Application

### Final Design with Components in Place
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH286ddQT78850c0d8a4aa7b6c719d66a30b?mode=embed" width="800" height="600" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

### Final Part Description and Real World Context

This Part Can...

- Hold the Soldering Iron <a id="hold"></a>

- Hold the Solder Spool and Guide During Use <a id="spool"></a>

- Hold a Extra Spool of Solder

- Hold Up To Five Soldering Tips <a id="tips"></a>

- Hold Soldering Iron Tip Cleaner Wire <a id="wire"></a>

<img src="https://raw.githubusercontent.com/segatti21/segatti21github.io/main/assets/img/fp/BLANK" alt="Model Serving Purpose" style="width:60%; max-width:500px;" /> 

... Which is Important in the Real World Because...

  A soldering iron holder plays a critical role in electronics assembly, repair, and prototyping, especially in environments where safety, efficiency, and precision are essential. In academic and lab settings —- such as instrumentation courses or when assembling biomedical devices like syringe pumps -— a soldering iron holder provides a stable, heat-safe resting place for the iron between uses. This minimizes the risk of workspace damage, component burns, or fire hazards, while keeping the area organized for faster and more accurate soldering. Also, in professional or industrial workspaces, an optimized soldering iron holder contributes to faster production and better ergonomics by streamlining workflows and maintaining tool access. 


### How This Improves the Functionality of the Soldering Station

  By having the tip and cleaning wire both so readily available and nearby the iron itself, this allows for quicker soldering times. These assisting items needed at the station will have high proximity to the area of use, meaning less time spent on transportation and search. Also, this leads to higher area organization. When placing something back into its position after using it with the iron, the easiest spot to put it is also where it goes. Additionally, the message of keeping clear of plastic helps remind both new and veteran users that this will oxidize the tip and make it useless.

- Old Set Up

<img src="https://raw.githubusercontent.com/segatti21/segatti21github.io/main/assets/img/fp/old.jpeg" alt="Previous Setup" style="width:60%; max-width:500px;" /> 

- Idea For Organization By Grouping

<img src="https://raw.githubusercontent.com/segatti21/segatti21github.io/main/assets/img/fp/org.jpeg" alt="Previous Setup" style="width:60%; max-width:500px;" /> 

- Outcome After Organizer in Place

<img src="https://raw.githubusercontent.com/segatti21/segatti21github.io/main/assets/img/fp/new.jpeg" alt="Current Setup" style="width:60%; max-width:500px;" /> 

### Relevance of the Soldering Iron to Me

Improving the efficiency, organization, and speed of a soldering station is something my academic work would benefit from, especially when soldering comes up in prototyping, assembly, and instrumentation work. As someone who has used soldering to build circuitry for syringe pumps, radios, and other lab assignments, a well-optimized station minimizes time spent adjusting tools or searching for parts, allowing for deeper focus on precision and functionality. A streamlined setup reduces frustration and rework, which is crucial when handling sensitive components or operating under tight design iterations. It enhances safety and repeatability—two qualities essential in both academic and medical device settings. As I begin my transition to a professional role in medical technology, I hope these habits translate directly to better product quality, faster development cycles, and higher confidence in builds.

---
## CAD Journey

### Original CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH286ddQT78850c0d8a443e561e7b00a1b4d?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

### Generated Design Options
<img src="https://raw.githubusercontent.com/segatti21/segatti21github.io/main/assets/img/fp/genopt.png" alt="Generated Options" style="width:60%; max-width:500px;" />

### Chosen Generated Design Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH286ddQT78850c0d8a4f826b9cfd465529e?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

---

## Preserve and Obstacle Geometry

### Critial Preserve Regions
There were various factors that determined if a component needed to be a preserved. The criteria fell into one of these catergories: 
- Contained mounting points,
- Point of Tool interfaces
- Constrained path

<img src="https://raw.githubusercontent.com/segatti21/segatti21github.io/main/assets/img/fp/preserve.png" alt="Preserve Geometries" style="width:60%; max-width:500px;" />

| Component Name | Preserve Rational | 
| -------------- | ----------------- |
| Base of Holder | The size needs to remain reasonable, and the overall layout should remain similiar |
| Solder Spool Center | The center that the extra spools slides onto must remain that size and diameter so it can hold the spools securely |
| Solder Iron Holders | They need to maintain the right shape to catch the iron in the correct spot so the oxidizable tip can avoid plastic | 
| Solder Pin and Guide Extension | This area needs to accurately match the sizes of the solder components that need to go in there such as the spool, pin, and the guide for the solder |

## Critical Obstacle Regions

There were various factors that determined if a component needed to be an obstacle. The criteria fell into one of these catergories
- Space that another object will take up
- Space the part must avoid
- Area that cannot be overheated
- Space that needs to be open for a part to later access 

<img src="https://raw.githubusercontent.com/segatti21/segatti21github.io/main/assets/img/fp/obstacles.png" alt="Obstacle Geometries" style="width:60%; max-width:500px;" />

| Component Name | Obstacle  Rational |
| -------------- | ------------------ | 
| Solder Tip Clearance | The tip of the soldering iron must be free of obstacles since plastic cannot be in the hot zone |
| Solder Iron Clearance | The straight cyclindrical shape of the iron must fit into the holder |
| Solder Tip Cleaning Wire Holder | There must be room for the wire holder in its cylindrical shape |
| Solder Spools | The spools are a certain size and must be avoided because they need to have space, whether they are extra or in use |
| Spare Soldering Tips | The tips must be place into the organizer without obstruction |
| Solder Tip Guide Component | The generative design must not fill in the holes designed to hold the guide or in the way of the guide's placement |
| Solder Spool Pin Path | The design must remain open where the pin will travel in and out to hold the solder spool and be caught for use |


---

## Load Case Application and Structural Constraints

### Load Characteristics

| Name of Force | Magnitude (N) | Location Applied To | Angle to Face | Force Type
| ------------- | ------------- | ------------------- | -------------- | ------------- |
| Soldering_Iron_Weight | 2.00 | Lower Portion of Inner Cylinder of Iron Holder | 0 degrees | Force |
| Backup_Weights | 4.00 | Base where Wire, Spools, and Catching Tray Go  | Perpendicular | Force |
| Spool_Pin_Circle | 1.00 | Base where Wire, Spools, and Catching Tray Go  | N/A | Bearing Load |
| Counter_Solder_Iron | 1.00 | Upper Portion of Inner Cylinder of Iron Holder | 0 degrees | Force |
| Backup_Movements | 4.00 | Inner Edges of Backup Storage | Perpendicular | Force |
| Solder_Guide | 0.50 | Insert Where Solder Guide Goes | 0 degrees | Force |
| Solder_Spool_Support | 1.50 | Path of Pin to Secure Spot | Perpendicular | Force |


### Determing Force Type, Magnitude, and Direction

| Name of Force | Magnitude Rational | Direction Rational | Type Rational | Force Rational |
| ------------- | ------------------ | ------------------ | ------------- | -------------- |
| Soldering_Iron_Weight | 2.00 | Lower Portion of Inner Cylinder of Iron Holder | 0 degrees | Force |
| Backup_Weights | 4.00 | Base where Wire, Spools, and Catching Tray Go  | Perpendicular | Force |
| Spool_Pin_Circle | 1.00 | Base where Wire, Spools, and Catching Tray Go  | N/A | Bearing Load |
| Counter_Solder_Iron | 1.00 | Upper Portion of Inner Cylinder of Iron Holder | 0 degrees | Force |
| Backup_Movements | 4.00 | Inner Edges of Backup Storage | Perpendicular | Force |
| Solder_Guide | 0.50 | Insert Where Solder Guide Goes | 0 degrees | Force |
| Solder_Spool_Support | 1.50 | Path of Pin to Secure Spot | Perpendicular | Force |

<img src="https://raw.githubusercontent.com/segatti21/segatti21github.io/main/assets/img/fp/loads.png" alt="Preserve Geometries" style="width:60%; max-width:500px;" />


### Structural Constraints
Where did you apply structural constraints, and how did this affect the results?
The primary structural constraint was to the base of the part, which ensured a solid, secure

| Component Name | Constraint  Rational | Picture in CAD |
| ------------- | ------------- | ------------------- |
| Connecting Base of All Features | Keeps the base constant, which all other components depend on | <img src="https://raw.githubusercontent.com/segatti21/segatti21github.io/main/assets/img/fp/base.png" alt="Part Base" style="width:60%; max-width:500px;" /> | 
| Solder Spool Holder Arms | Must remain rigid to avoid snapping / flexing when spool is spun | <img src="https://raw.githubusercontent.com/segatti21/segatti21github.io/main/assets/img/fp/spoolarms.png" alt="Solder Arms" style="width:60%; max-width:500px;" /> |

### Further Testing
Thermal testing should be conducted by running the soldering iron in its holder and using an infrared thermometer or thermal camera to monitor nearby plastic surfaces, ensuring they stay below deformation thresholds. Vibration and handling tests should simulate realistic desk impacts or movement to evaluate part stability, joint durability, and component retention. Finally, a user ergonomics study should observe how users interact with the organizer to identify where loads are applied and how accessibility might influence structural stress. 

Static load testing and fit tolerance checks have already been completed, confirming that the organizer supports the intended components and that multi-material parts align properly.

---

## Generative Design Critique

### Usefulness
In my experience, generative design can be incredibly valuable for practical engineering and prototyping—especially for multifunctional devices like the soldering station organizer shown above. In this project, generative design helped optimize space, minimize material usage, and integrate multiple components into a compact, structurally sound unit. It enabled the rapid exploration of design alternatives that balanced functionality and manufacturability as well as can imitate nature. While the output sometimes required refinement for ease of assembly or printability, the ability to automatically generate geometry based on defined constraints—such as preserve regions around the iron holder or obstacle zones for wiring paths—was a major advantage. Overall, when used thoughtfully, generative design enhances efficiency, innovation, and performance in prototyping workflows.

### Limitations Encountered
One limitation encountered was the need to account for material differences— the generative component was printed using pSLS, while others used PLA filament, requiring careful tolerancing to ensure proper fit. Additionally, thermal management was critical; air gaps and non-contact zones had to be designed to prevent heat from the soldering iron from warping or damaging nearby plastic. These constraints limited the freedom of the generative model and required post-processing adjustments. Despite this, the process still significantly streamlined early-stage design and spatial optimization.

### Industry Evaluation
After my experience with Generative Design, I would say that industries prioritizing weight reduction, strength optimization, and form refinement. Many topologies can be explored as well, offering a wide variety of aestetic options. On the other hand, industries that prioritize maintaining strict standards, easy mass production, and/or would not benefit from what Generative Design has to offer. The table below outlines specific industries that come to mind for either advancing from use or not. 

| Industry | Great/Bad For It | Rational | Source | 
| -------- | ---------------------- | -------- | ------ | 
| Medical Devices | Great For It | Can personalize implants/prosthetics/etc for specific patients | | 
| Architectural Design and Construction| Great For It | Minimize material used and can explore aesthetic options | | 
| Automotive Manufacturing | Great For It | Looks to reduce mass and fuel usage | |
| Aerospace Engineering | Great For It | Saving weight is critical | |
| Standardized Manufacturing | Bad For It | Traditional parts cannot violate norms or tolerances | |
| Mass Electronics | Bad For It | Prioritize aesthetics, internal layout, and mass production compatibility over structural optimization | | 
| Packaging | Bad For It | Needs to be cheap and repeatable with materials like cardboard | | 

Medical Devices:
<img src="https://raw.githubusercontent.com/segatti21/segatti21github.io/main/assets/img/fp/medindus.png" alt="Generative Design in Medical Devices" style="width:60%; max-width:500px;" />
Source: Today's Medical Developments News
