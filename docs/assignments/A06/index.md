# A6 - Bracket Drawing

## Objective

This project entails creating a parametric model of the previously designed bracket and creating a fully dimensioned engineering drawing.

## Analyze

The bracket from the previous assignment was designed using strength and stiffness calculations to determine the necessary dimensions. These dimensions will now be used to create the parametric CAD model.

![multiview2](multiview2.jpg) <br>

The bracket also needs to properly fit over the given T-beam. The dimensions and tolerances of the T-beam are shown below.

![BracketSpecs](bracketspecs.png) <br>

## Decide

### Parametric Model

The bracket was modeled in Creo using parameters for the important dimensions. This allows dimensions to change based on the equations used to design the bracket.

![parametric1](parametric1.PNG) <br>
I started by designing the cylinder that holds the strap.

![parametric2](parametric2.PNG) <br>
I then set the length

![parametric3](parametric3.PNG) <br>
I created the bottom of the bracket.

![parametric4](parametric4.PNG) <br>
I created the sides of the bracket.

![parametric5](parametric5.PNG) <br>
I then created the top of the bracket.

### Drawing

A multiview drawing was created using third-angle projection.

![Drawing](drawing.PNG)

The sliding surfaces use tighter tolerances because they need to properly fit over the T-beam. Less important dimensions use looser tolerances because they do not directly affect the fit of the bracket.

### Mistakes

Originally, I incorrectly used separate variables for some dimensions instead of relating them to the main design parameters. I fixed this by connecting the sketch and feature dimensions using relations, allowing changes to the main parameters to update the model. 

## Communicate

The final design uses parameters to control the important dimensions of the bracket. A fully dimensioned drawing was also created so that the bracket could be manufactured with the required fits.

### Lessons Learned

This project showed how parameters can be used to connect engineering calculations directly to a CAD model. I also learned how different tolerances can be used depending on how important a dimension is to the function of the part.

### Time Spent

The project took around 3 hours to complete.

### CAD Files

[Bracket CAD Files](https://github.com/DillonK-spec/megr2157-portfolio/blob/main/docs/assignments/A06/drawing1.prt)

[Drawing](https://github.com/DillonK-spec/megr2157-portfolio/blob/main/docs/assignments/A06/drw0001.drw)
