### A7 – Finite Element Analysis on Bracket

### Objective
The objective of this assignment is to use Finite Element Analysis (FEA) to improve the bracket design from a previous assignment. There will be multiple iterations of the design and for each one I will be running simulations to analyze stress, deflection, and safety factor. Then I will be making changes to increase strength and stiffness while reducing weight. Different mesh sizes will also be tested to ensure accurate results.

## Iteration 1 – Original Design

### Setup
Material: ASTM A36 Steel
Applied Load: 600 lbf

I designed the part in Creo originally, but imported it into SolidWorks to run the stress analysis. 

![Original Design](originaldesign.PNG)

Here I selected the surfaces where the bracket is held in place.

![Fixtures](Fixtures.PNG)

Here I applied the force to the cylindrical part of the bracket.

![Load](load.PNG)

Here I assigned the material used for the bracket.

![Material](material.PNG)

Here I analyzed how the bracket deforms under the applied load.

![Deformation](deformation.PNG)

Here I checked the stress with a factor of safety of four. The entire top portion is blue, meaning it can withstand the current stress.

![Factor of Safety](FOS.PNG)

### Iteration 1 Results

The lowest factor of safety found in this simulation was 0.07432. The bottom portion of the bracket is relatively thin, there was an obvious mistake in my earlier calculations so that part will be made thicker.

### Iteration 2 – Modified Design

### Design Changes
Describe what was changed and why.

![Modified Design](iteration2.PNG)

### Mesh Analysis

![Coarse Mesh](mesh2_coarse.PNG)

![Medium Mesh](mesh2_medium.PNG)

![Fine Mesh](mesh2_fine.PNG)


### Results
Explain how the changes affected the bracket.

### Iteration 3 – Final Design

### Design Changes
Describe the final changes and why they were made.

![Final Design](iteration3.PNG)

### Mesh Analysis

![Coarse Mesh](mesh3_coarse.PNG)

![Medium Mesh](mesh3_medium.PNG)

![Fine Mesh](mesh3_fine.PNG)


### Results
Explain the final simulation results.

### Final Design Comparison

| Measurement | Design 1 | Design 2 | Design 3 |
|---|---|---|---|
| Maximum Stress and Location | | | |
| Maximum Deflection and Location | | | |
| Mass | | | |
| Safety Factor | | | |
| Number of Elements | | | |

### Comparison
Compare the three designs in terms of strength, stiffness, and weight.

### Lessons Learned
Explain what was learned about FEA, mesh convergence, and design optimization.

### Mistakes and Challenges
Describe any mistakes and how they were corrected.

### Time Spent
- Iteration 1:
- Iteration 2:
- Iteration 3:
- Documentation:
- Total:

### Final CAD File
[Download Final Bracket](INSERT_LINK_HERE)
