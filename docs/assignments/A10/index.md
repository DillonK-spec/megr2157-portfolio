# A10 – Lead Screw Design

## Objective
The objective of this assignment is to design and build a mechanically driven tensile tester. The tester must be capable of applying up to a 2 kN axial load. It must also have a controllable crosshead speed  
from 1mm to 50mm per minute and be designed with a safety factor of 4. The leadscrew must be at least 18 inches and it's preferred to be short enough to fit on a workbench.

Below is the concept image given.
![leadscrewconcept](leadscrewconcept.png)

## Lead Screw Design

### Thickness

These are the knowns and unknowns for the lead screw:

![knowns](known.jpg)

Here is the FBD and numerical solving for the screw. The required force is split along two screws, but they need a safety factor of four.

![FBD](FBD.jpg)

The provided resources show leadscrews made with steel or stainless steel. The minimum yield strength for steels is around 205 MPa, so I will use that to calculate minimum diameter.

![dmin](dmin.jpg)

### Rotational Speed

Here are the knowns and unknows for to determine the rotational speed based on a range of vertical speeds.

![known2](known2.jpg)

This is a free body diagram demonstrating how the nut translates around the screw. I made a mistake here for lead, it's 1/TPI, not TPI.

![FBD2](FBD2.jpg)

These are the calculations, I just chose 0.1 as as the lead since 10 threads per inch seemed common. 

![RPM](RPM.jpg)



## Decide
_Reference your concept selection (Pugh matrix) here. How does this design follow from that decision?_

## Communicate

