---
title: pH Sensor Block Diagram
tags:
- tag1
- tag2
---

## Overview
The selected pH probe will allow hydrogen ions in the water to diffuse into the probe so the activity may be measured. A small voltage anywhere from -0.5 volts to +0.5 volts will be generated. This range corresponds to the pH of the water, where the more acidic pH will generate a larger negative voltage and the more basic pH will generate a larger positive voltage.

The signal is amplified by the operational amplifier which has an ideal gain equal to 4. The microcontroller take this analog signal, convert it to digital and then make a decision as to whether the pH is safe or not. After making the decision, either the green or red LED will light up to indicate "SAFE" or 'DANGER", respectively. The decision and pH value will also be sent to the control board where they will be displayed on the device's screen.

There is also a debugging button which allows the PCB to enter and exit "Testing Mode", as well as 2 yellow LEDs for debugging indications.

If there are any power issues, the header pins also provide power connections to either supply or receive 5 volts and a ground connection for the other PCBs.



## Block Diagram 
Figure 1 displays the pH Sensor Block Diagram.

![Figure 1](individualblockdiagramdrawio.pdf)