---
title: "Final Project: Solder Holder"
excerpt: "Use of Generative Design to create an aid for the soldering iron station of the Digital Fabrication space" 
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: assets/img/solderin.png
  teaser: assets/img/solderin.png
---

### After choosing the third path, Digital Fabricatiin Aid, of the Generative Design Final Project for CHBE 4200, the idea of a new solder iron holder that can [hold the iron](#hold), [hold new soldering tips](#tips), and [hold solder cleaning wire](#wire) came to mind. 

--- 

## Overview of the Part and Application

### Final Part Description and Real World Context

  ##### - This Part Can...

    ##### * Hold the Soldering Iron

    ##### * Hold Up To BLANK Six Soldering Tips

    ##### * Hold BLANK Grams of Soldering Iron Tip Cleaner Wire

    ##### * Hold a Spool of Solder

<img src="https://raw.githubusercontent.com/segatti21/segatti21github.io/main/assets/img/fp/BLANK" alt="Model Serving Purpose" style="width:60%; max-width:500px;" /> 

  #### - ... Which is Important in the Real World Because...



### How This Improves the Functionality of the Soldering Station

By having the tip and cleaning wire both so readily available and nearby the iron itself, this allows for quicker soldering times. These assisting items needed at the station will have high proximity to the area of use, meaning less time spent on transportation and search. Also, this leads to higher area organization. When placing something back into its position after using it with the iron, the easiest spot to put it is also where it goes. Additionally, the message of keeping clear of plastic helps remind both new and veteran users that this will oxidize the tip and make it useless.

### Relevance of the Soldering Iron to Me

Improving the efficiency, organization, and speed of a soldering station is something my work in electrical/computer engineering and digital fabrication would benefit from, especially when soldering comes up in prototyping and instrumentation work. As someone who has used soldering to build circuitry for syringe pumps, radios, and other lab assignments, a well-optimized station minimizes time spent adjusting tools or searching for parts, allowing for deeper focus on precision and functionality. A streamlined setup reduces frustration and rework, which is crucial when handling sensitive components or operating under tight design iterations. It enhances safety and repeatability—two qualities essential in both academic and medical device settings. As I begin my transition to a professional role in medical technology, I hope these habits translate directly to better product quality, faster development cycles, and higher confidence in builds.

---
## CAD Journey

### Original CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH286ddQT78850c0d8a4e5bb1a6017753046?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

### Chosen Generated Design Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH286ddQT78850c0d8a4e5bb1a6017753046?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

---

## Preserve and Obstacle Geometry


### Critial Preserve Regions
There were various factors that determined if a component needed to be a preserved. The criteria fell into one of these catergories: 
- Contained mounting points,
- Point of Tool interfaces
- Constrained path

| Component Name | Preserve Rational | Picture in CAD |
| ------------- | ------------- | ------------------- |
| Base of Holder | | <img src="https://raw.githubusercontent.com/segatti21/segatti21github.io/main/assets/img/fp/BLANK" alt="Next Comp" style="width:60%; max-width:500px;" /> |

## Critical Obstacle Regions

There were various factors that determined if a component needed to be an obstacle. The criteria fell into one of these catergories
- Space the part must avoid
- Area that cannot be overheated
- It was 

| Component Name | Obstacle  Rational | Picture in CAD |
| ------------- | ------------- | ------------------- |
| Solder Tip Clearance | The tip of the soldering iron must be free of obstacles | <img src="https://raw.githubusercontent.com/segatti21/segatti21github.io/main/assets/img/fp/BLANK.png" alt="Tip Air Component" style="width:60%; max-width:500px;" />|
| Wire Clearance | The end of the iron must have space for the wire to  | <img src="https://raw.githubusercontent.com/segatti21/segatti21github.io/main/assets/img/fp/BLANK" alt="Next Comp" style="width:60%; max-width:500px;" /> |


---

## Load Case Application and Structural Constraints

### Load Characteristics

| Name of Force | Magnitude (N) | Location Applied To | Angle to Face | Force Rational |
| ------------- | ------------- | ------------------- | -------------- | -------------- |

### Determing Force Type, Magnitude, and Direction

| Magnitude Rational | Direction Rational | Type Rational | 
| ------------------ | ------------------ | ------------- |

### Structural Constraints
Where did you apply structural constraints, and how did this affect the results?
The primary structural constraint was to the base of the part, which ensured a solid, secure 
| Component Name | Constraint  Rational | Picture in CAD |
| ------------- | ------------- | ------------------- |
| Connecting Base of All Features | Keeps the base constant, which all other components depend on | <img src="https://raw.githubusercontent.com/segatti21/segatti21github.io/main/assets/img/fp/BLANK" alt="Part Base" style="width:60%; max-width:500px;" /> | 
| Solder Spool Holder Arms | Must remain rigid to avoid snapping / flexing when spool is spun | <img src="https://raw.githubusercontent.com/segatti21/segatti21github.io/main/assets/img/fp/BLANK" alt="Solder Arms" style="width:60%; max-width:500px;" /> |

### Further Testing
How can you test your real-world prototype to further refine the loads?

---

## Generative Design Critique

### Usefulness
In your experience, how useful is generative design for practical engineering or prototyping?

### Limitations Encountered
What limitations did you encounter?

### Industry Evaluation
After my experience with Generative Design, I would say that industries prioritizing weight reduction, strength optimization, and form refinement. Many topologies can be explored as well, offering a wide variety of aestetic options. On the other hand, industries that prioritize maintaining strict standards, easy mass production, and/or would not benefit from what Generative Design has to offer. The table below outlines specific industries that come to mind for either advancing from use or not. 

| Industry | Great For / Bad For It | Rational | Source | 
| -------- | ---------------------- | -------- | ------ | 
| Medical Devices | Great For It | Can personalize implants/prosthetics/etc for specific patients | | 
| Architectural Design and Construction| Great For It | Minimize material used and can explore aesthetic options | | 
| Automotive Manufacturing | Great For It | Looks to reduce mass and fuel usage | |
| Aerospace Engineering | Great For It | Saving weight is critical | |
| Standardized Manufacturing | Bad For It | Traditional parts cannot violate norms or tolerances | |
| Mass Electronics | Bad For It | Prioritize aesthetics, internal layout, and mass production compatibility over structural optimization | | 
| Packaging | Bad For | Needs to be cheap and repeatable with materials like cardboard | | 

<img src="https://raw.githubusercontent.com/segatti21/segatti21github.io/main/assets/img/fp/example.png" alt="Example" style="width:60%; max-width:500px;" />
