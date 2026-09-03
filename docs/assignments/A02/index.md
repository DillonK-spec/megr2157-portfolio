# A2 – Truss Stress Analysis

## Objective
This project entails creating a lightweight planar truss, analyzing all joints and pins, and determining the necessary size of all parts.

## Analyze
# Truss Design
![Truss Diagram](introtrussdiagram.png) <br>
This is the image used to create a Truss. There are two applied loads, one at C applied upwards and one at D applied downwards. Point A is a pin and Point B is a roller. P represents a load of 20kN, a is a distance of 0.4m, and b is a distance of 0.3m.

## Decide
![Truss Rough Sketch](trussroughsketch.jpg) <br>
This is the rough geometry I created for the truss. The applied loads were put at joints to maximize the compression and tension in beams instead of creating a moment. Point E was added as an attempt to distribute the load more between points B and A. 

![trusslength](trusslengthmath.jpg) <br>
These are the calculated lengths for the beams. Most of the lengths were the given lengths of 0.4 meters or 0.3 meters, except for AE which was 0.8 meters (two of the 0.4 dimensions). The three diagonal beams were all 0.5 meters, they were found using the Pythagorean Theorem.

![trussfbd](trussfbd.jpg) <br>
I created free body diagrams for all the joints within the truss.

![symbolicsolution](beamsymbolicsolution.jpg) <br>
This is the symbolic solution of all internal forces in the in the x and y directions. It's based on the free body diagrams. The terms 0.3/0.5 and 0.4/0.5 are used because they are equivalent to sines and cosines of the truss angles. There was also a mistake in this math, BE = 0.8BC.

![internalforces](beamstresses.jpg) <br>
These are all of the calculated internal forces, the order is different because I had to calculate the moment in the corners and worked inwards. The largest force is a 22.22kN tension in DE.

# Calculating Area

## Communicate

