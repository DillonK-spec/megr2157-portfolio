# A11 – Motor Selection

## Objective
In this project, we will continue designing a tensile tester that can withstand a 2kN load. We will be selecting motors to drive the leadscrews, designing motor mounts and then creating a frame. Our group includes Dillon Knight, Marvin Sibelius, and Sean Chadwick.

## Specifications

Maximum tensile load: 2,000 N

Number of leadscrews: 2

Leadscrew length: 24 inches

Leadscrew diameter: 1/2 inch

Leadscrew lead: 0.1 in/rev

Required travel speed: 1–50 mm/min

Factor of safety: 4

Leadscrew material: ASTM A108

## Motor Selection (Dillon)

Each leadscrew requires 5.459 N·m of torque. Since each leadscrew will be driven by its own motor, both motors must be capable of producing at least this amount of torque. Each motor must also operate over an output speed range of approximately 0.394–19.685 RPM.

A DC gearmotor is being considered because the leadscrews require relatively high torque at low speeds. A motor with an output speed near 20 RPM and a continuous torque rating of at least 5.459 N·m would be suitable.
I found a motor rated for 6 N*m and 28RPM [Here](https://cautop.com/mall/show-1993526.html)

I used excel to generate theoretical speed and power values based off of torque.
![excelcurve](excelcurve.PNG)

This is the generated graph showing the relationship between torque, speed, and power.

![speedtorquecurve](speedtorquecurve.PNG)

## Communicate



