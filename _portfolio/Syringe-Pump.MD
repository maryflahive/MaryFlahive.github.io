---
title: "Syringe Pump"
excerpt: "DIY Syringe Pump capable of uL / min flow rate up to 10 mL / min."
header:
  image: assets/img/Screenshot 2024-04-29 201723.png
  teaser: assets/img/Screenshot 2024-04-29 201723.png
   
---

Syringe pumps, also known as infusion pumps, offer a cost-effective solution for administering precise fluid doses to patients over extended periods, a task that would be costly and inefficient for human nurses. These pumps typically feature a syringe for fluid storage, a block to press the plunger, a lead screw to translate motor rotation into linear motion, a base for structural integrity, and tubing to deliver the fluid, ensuring consistent and controlled fluid delivery. This design incorporates similar components to provide the same functionality of stable and controlled pumping of fluid.

## Components

| Off-the-Shelf Required Parts  | Quantity |
| --- | --- |
| 250 mm lead screw with 2 mm pitch and 2 mm lead  | 1 |
| 1/4" x 8mm Flexible Coupling  | 1 |
| 200 mm linear rod with 8 mm diameter | 2 |
| LM8UU Linear bearing for 8 mm diameter rod | 2 |
| 2040 Aluminum Extrusion 1' Length | 1 |
| Nema 17 Stepper Motor | 1 |
| MEAN WELL RQ-65D AC-DC Power Supply Quad Output 5V 12V 24V 12V 4 Amp | 1 |
| Arduino Uno | 1 |
| A4988 Stepper Driver | 1 |
| Small Breadboard | 1 |
| Panel Mount Latching Push Buttons | 1 |
| Panel Mount Momentary Push Buttons | 3 |
| LCD Display | 1 |
| Limit Switch | 1 |
| RGB Common Cathode LED | 1 |
| Potentiometer | 1 |


| 3D Printed Required Parts  | Quantity |
| --- | --- |
| Carriage | 1 |
| Enclosure Top & Bottom | 1 |
| End Support | 2 |
| Motor Mounting Plate | 1 |


## Operation Instructions

* Ensure that the pump is paused by pressing the leftmost button, the LED turns yellow when the pump is paused.
* Place the syringe with the desired amount of liquid to pump on the end support.
* Using the switches on the right of the display, adjust the carriage so that it touches the end of the syringe plunger.
* Use the potentiometer to adjust as desired the flow rate as seen on the display. 
* Press the leftmost button again to start the pump, the LED should turn green.
* As the pump runs, the display will show the current flow rate and time remaining.
* When the plunger reaches its limit, the carriage actuates a limit switch to stop the motor. The LED turns red to indicate that the run has ended.


## CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH286ddQT78850c0d8a43a7ed807993c6119?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>


