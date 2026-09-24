# A5 – Bracket Design
## Objective
In this project, I will be designing a bracket that fits around a T beam and holds a strap below the beam. 

### Specifications
My bracket design needs to have a safety factor of 4 and I'm choosing to have an applied load of 600lbf.
Below are the dimensions the bracket will be built around.

![BracketSpecs](bracketspecs.png) <br>
The bracket has a max deflection of 0.005 inches. I'm choosing to use ASTM A36 Steel in this design since it has the largest Young's modulus out of my choices and will require less material to meet deflection requirements. The Young's modulus for ASTM A36 Steel is 29,000 ksi and its yield strength is 36 ksi.

## Design

To determine the bracket dimensions, I have to do a stress analysis and then an elongation analysis for each section. The parts were already sections off as shown below.

![bracketsections](bracketparts.png)

### Stress Analysis
Every stress analysis assumes the force is 600lbf, there is a safety factor of 4, the bracket is 2 inches long, and the yield strength of the material is 36,000 psi.


Part A of the stress analysis involved determining the radius of the cylinder that holds a weighted strap. The radius must be greater than or equal to 0.5537 inches.
![stress1](stress1.jpg) <br>

I found the required area for part B, but actual dimensions will be calculated later. It must be greater than or equal to 0.1333 square inches.
![stress2](stress2.jpg) <br>

Feature C was treated as a simple supported beam. With a given width and length, I solved for height. This feature has to be at least 0.4996 inches tall.
![stress3](stress3.jpg) <br>

Feature D was treated as if it was in compression.  I solved for width and it had to be greater than or equal to 0.0333 inches.
![stress4](stress4.jpg) <br>

Feature E was treated as if it was in compression. I solved for height and it must be greater than or equal to 0.0667 inches.
![stress5](stress5.jpg) <br>

### Elongation Analysis
I continued the analysis by determining the minimum dimensions required to keep deflection below 0.005 inches. ASTM A36 steel has an elastic modulus of 29,000,000 psi.

Feature A was treated as a cantilever beam. I solved for the minimum radius needed to keep deflection below 0.005 inches. The radius must be greater than or equal to 0.409 inches.
![deflection1](deflection1.jpg) <br>

Feature B was treated as an axially loaded bar. I solved for the minimum cross-sectional area required to keep elongation below 0.005 inches.
![deflection2](deflection2.jpg) <br>

Feature C was treated as a simply supported beam with a concentrated load at the center. With the given width and length, I solved for height. The height must be greater than or equal to 0.252 inches.
![deflection3](deflection3.jpg) <br>

Feature D was treated as an axially loaded member in compression. I solved for the minimum cross-sectional area required to keep deformation below 0.005 inches. The required area is 0.00620 square inches.
![deflection4](deflection4.jpg) <br>

Feature E was treated as an axially loaded member in compression. With a width of 0.9992 inches and length of 2 inches, I solved for height. The height must be greater than or equal to 0.00828 inches.
![deflection5](deflection5.jpg) <br>

## Design


## Communicate

