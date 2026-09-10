# A3 – Parametric Design and Finite Element Analysis

## Objective
The purpose of this project is to parametrically design a bar in CAD software, then apply a distributed load. The bar will also be subjected to finite element analysis. <br>
![distributedload](distributedload.png)

## Analyze
The parameters for the bar have the maximum axial deflection at .009 inches. It's designed from aluminum 6061 and the Young's Modulus will be 10 * 10^6 psi. The axial deflection is the same as the elongation of the bar. I'm using the maximum axial deflection and area to calculate how long the bar can be.

### Bar Design

The bar will be 0.5 inches wide and 0.6 inches tall, this makes the area 0.3 square inches. I tried using small, simple numbers to make math easy and lower length.
![Area](creo1.PNG) <br>
I couldn't figure how to change Creo's generated variables directly so I simply set them equal to named variables. The length of the bar will be determined based on the direct tension elongation equation.
![elongationequation](creo2.PNG) <br>

The software calculated the length to be 67.5 inches.
![lengthcalculation](creo3.PNG) <br>

I then set the material of the object to aluminum and modified the Young's Modulus to match aluminum 6061, the one in my calculations.
![material](creo4_5.PNG) <br>


### Simulations
I fixed one end of the beam and added a 400 pound force to the other end. The force acted in the same direction as the length.
![simulationsetup](creo4.PNG) <br>
This is the deformation simulation in Creo. The sum of the deformation was 0.009005, slightly exceeding the calculated deformation of 0.009
![deformation](creo5.PNG) <br>
Here I ran the Von Mises stress simulation and it had a value of 1.5991 ksi.
![VonMises](creo6.PNG) <br>
The maximum stress calculated was 1.8491 ksi.
![normalstress](creo7.PNG) <br>

## Decide


## Communicate

