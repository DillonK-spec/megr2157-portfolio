# A10 – Lead Screw Design

## Objective
The objective of this assignment is to design and build a mechanically driven tensile tester. The tester must be capable of applying up to a 2 kN axial load. It must also have a controllable crosshead speed  
from 1mm to 50mm per minute and be designed with a safety factor of 4. The leadscrew must be at least 18 inches and it's preferred to be short enough to fit on a workbench.

Below is the concept image given.

![leadscrewconcept](leadscrewconcept.png)

## Lead Screw Selection

### Thickness

These are the knowns and unknowns for the lead screw:

![knowns](known.jpg)

Here is the FBD and numerical solving for the screw. The required force is split along two screws, but they need a safety factor of four.

![FBD](FBD.jpg)

The provided resources show leadscrews made with steel or stainless steel. The minimum yield strength for steels is around 205 MPa, so I will use that to calculate minimum diameter.

![dmin](dmin.jpg)

### Rotational Speed

Here are the knowns and unknowns for to determine the rotational speed based on a range of vertical speeds.

![known2](known2.jpg)

This is a free body diagram demonstrating how the nut translates around the screw. I made a mistake here for lead, it's 1/TPI, not TPI.

![FBD2](FBD2.jpg)

These are the calculations, I just chose 0.1 as as the lead since 10 threads per inch seemed common. The lead screw will operate from 0.394 to 19.68 RPM.

![RPM](RPM.jpg)

### Torque 

The coefficient of friction between steel and bronze was assumed to be 0.16, using this [Coefficient of Friction Reference Chart](https://www.schneider-company.com/coefficient-of-friction-reference-chart/) as a reference.

Here are the knowns and unknowns to find the Torque:

![known3](known3.jpg)

This is a rough free body diagram for the torque and the required formula.

![FBD3](FBD3.jpg)

I plugged in the values and found the torque to be 5.459 Newtons times meters. 

![T](T.jpg)

### Lead Screw Selection

The lead screw I selected has a part number 98935A911 on mcmaster.com. It's 24 inches long and has a 64,000 psi tensile strength, which equates to 441 MPa. I used 205 MPa in my earlier calculations, but it was for yield strength, which is always lower. ASTM A108 has a minimum yield strength of 195MPa which is slightly lower than my calculations. Considering the safety factor of 4 and the larger than necessary diameter, this lead screw shouldn't deform. 

![leadscrews](leadscrews.PNG)

## Nut Selection

These are the known forces for the nut.

![known4](known4.jpg)

This is the FBD for the nut and the required equations.

![FBD4](FBD4.jpg)

This is my calculation for the bending stress. I used 10 threads in the calculation because that was the first flange nut I saw with the same thread type.

![nutstress](nutstress.jpg)

This is the nut I ended up choosing, it has part number 95120A111 on McMaster-Carr. Other nuts made of the same material have a tensile strength of 35,000 psi, or 241 Mpa which put it well above the calculated stress. 

![mcnut](mcnut.PNG)

## Crosshead Design

For the crosshead design, I used a length in the range found in "Design, Manufacture, and Testing of an Open Source Tensile Testing Machine for Hands on Learning". I decided to use reasonable lengths and test if they would meet the requirements. It will be made from aluminum. 

![known5](known5.jpg)

Here is a diagram of the crosshead and the formulas I'll use.

![FBD5](FBD5.jpg)

These are the calculations for the dimensions I chose. The initial thickness caused too much deflection, so I increased it.  

![crosshead](crosshead.jpg)

## Decide
_Reference your concept selection (Pugh matrix) here. How does this design follow from that decision?_

## Communicate

