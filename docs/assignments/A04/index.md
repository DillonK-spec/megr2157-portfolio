# A4 – Motor Mount Design

The objective of this project is to design a motor mount based on calculated stress and deflection. It contains a brushed 24V gear motor with a 99.5:1 gearbox. 

![brushedmotor](brushedmotor.jpg) <br>

## Specifications

This motor's specifications are as follows: <br>
Motor Size: Φ27.7 x 38mm <br>
Gearbox Size: Φ28 x 36.6mm <br>
Shaft Diameter: Φ6mm <br>
Shaft Length: 18mm <br>
D-cut Length: 12mm <br>

The bracket will need to handle 3.6Kg.cm

The maximum deflection is 0.3mm

### ABS

I chose to use ABS as the material. It has a Yield Strength of 29.6 MPa and a Young's Modulus of 1.79 GPa.

## Feature 1
Below are my stress calculations for Feature 1 of the motor mount. I chose b to be 6mm because that much of the shaft doesn't have a D-cut.
![feature1stress](stress1.jpg) <br>
These are my deflection calculations for Feature 1. I chose L to be 28mm in order to fit the motor.
![feature1deflection](deflection1.jpg) <br>
I believe a good fit for b would 28mm, even though the mount could be thinner based on my calculations. This would prevent the motor tilting to the sides.


## Feature 2
Below are my stress calculations for Feature 2 of the motor mount.
![feature2stress](stress2.jpg) <br>
These are my deflection calculations for Feature 2.
![feature2deflection](deflection2.jpg) <br>

## Designing the Mount
I first made a quick drawing for the motor mount.
![quickdraw](drawing.jpg) <br>
This is modeling for the mount done in Creo. I started with feature 1.
![mount1](mount1.PNG) <br>
I then made feature 2.
![mount2](mount2.PNG) <br>
I created a 6.05mm hole for the motor shaft, making it slightly larger for clearance.
![mount3](mount3.PNG) <br>
I then added 4 3.4mm clearance holes evenly spaced on feature 2.
![mount4](mount4.PNG) <br>

Here is a link to the CAD file : ![part]([motormount.prt](https://github.com/DillonK-spec/megr2157-portfolio/blob/main/docs/assignments/A04/motormount.prt))
## Drawing

This is the drawing I created for the part. I struggled with finding the template to add the material, my name, etc, so I inserted text manually.
![drawing]([enginemountdrw.pdf](https://github.com/DillonK-spec/megr2157-portfolio/blob/main/docs/assignments/A04/enginemountdrw.pdf)) <br>

## Reflection
This project took around 4 hours to complete. The hardest part was the math for the deflection and stress. The modeling was easier but my design was simple.

## Appendix
Here are some motor mounts with a similar design.

![universalMount](universalMount.jpg) <br>

![gokartmount](gokart.jpg) <br>




