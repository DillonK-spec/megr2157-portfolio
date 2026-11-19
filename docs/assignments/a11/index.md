
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

I used excel to generate theoretical speed and power values based off of torque. 10 N*m is the peak torque listed and my excel formula for speed was “(33*(1-A2/10))*2*PI()/60”  which linearly decreased the speed from 33 to 0 and converted RPM to Rad/s.

![excelcurve](excelcurve.png)

This is the generated graph showing the relationship between torque, speed, and power.

![speedtorquecurve](speedtorquecurve.png)

The max power output is around 5 N*m and 15 RPM.
## Motor Mount Design (Sean)

The goal of this part of the assignment is to find how thick the motor mounts need to be. Our design features two different motors, which meant we would have 2 brackets.

![2a](2a.PNG)

Here, I stated all of the variables we knew and every variable that needed to be found. The force, torque, and dimensions of the holes/bracket were known, except for the thickness of the bracket which is what we are solving for.

![2b](2b.PNG)

I drew a Free Body diagram of the bracket in question to get a good layout of the bracket and the spacing of each hole, as well as drawing out where each force and moment will be acting.

![2c](2c.PNG)

I then solved for the thickness algebraically. I solved for both sizes of holes, using two separate diameters.

![2d](2d.PNG)

Plugging in the numerical values, I got a minimum thickness of .74mm, which is not going to be our thickness of the plate, as that is thin and will ultimately lead to a less accurate plate, we will decide the actual thickness later in the project.

## Coupler Design (Sean)

The next part of the project was designing a coupler

![3a](3a.PNG)


![3b](3b.PNG)


![3c](3c.PNG)


![3d](3d.PNG) 

## Mount design (Sean)

![4a](4a.png)


![4b](4b.png)


![4c](4c.png)


![4d](4d.png) 

## Mounting Bearing (Dillon)

An RC3 running fit was used for the floating bearing mount at the bottom of the leadscrew. For the 0.5 inch diameter leadscrew, the hole has a tolerance of +0.0007”/-0.00” and the shaft has a tolerance of -0.0006”/-0.001”. The mounts are placed directly under the leadscrew. 

![bearingplate](bearingplate.jpg)

This bearing plate will be 0.5” thick and use 0.1/4”-20 bolts at each corner.


## Bill of Materials (Dillon)

| Item Number | Quantity | Name | Cost/Item | Total Cost | Purchase Link |
|:---:|:---:|---|---:|---:|---|
| 1 | 2 | 1/2"-10 Acme Lead Screw | $6.95 | $13.90 | [Purchase](https://www.mcmaster.com/98935A911/) |
| 2 | 2 | 932 Bronze Flanged Nut | $125.72 | $251.44 | [Purchase](https://www.mcmaster.com/95120A111/) |
| 3 | 4 | Aluminum Frame Material | $12.25 | $48.98 | [Purchase](https://www.lowes.com/pd/Mecale-23-6-in-4040-Aluminum-Extrusion-T-Slot-Linear-Rail-4-Pack-6063-T5-Anodized-Profile-Black/5021607235) |
| 4 | 1 | 6060 Aluminum Crosshead | ~10.00|~10.00 | N/A |
| 5 | 2 | DC Worm Gear Motor | $18.05 | $36.10 | [Purchase](hhttps://cautop.com/mall/show-1993526.html) |
| 6 | 2 | Motor Mounting Brackets | $8.00 | $16.00 | N/A |
| 7 | 2 | Leadscrew Couplers | $12.00 | $24.00 | N/A |
| 8 | 8 | 1/4-20 Bolts | $0.80 | $7.99 | [Purchase](www.amazon.com/dp/B07MQXL594)|
| 9 | 8 | 1/4-20  Nuts | $0.16 | $4.99 | [Purchase](https://www.amazon.com/dp/B0CSY9G7TW)|
| 10 | 2 | Floating Bearing Mounts | $6.00 | $12.00 | N/A |
| | | | **Total Cost** | **$324.32** | |

### Labor Costs

An hourly rate of $35 was used to calculate engineering labor costs. The total labor cost was determined by multiplying the hours spent on each task by the hourly rate.

| Task | Hours | Rate | Total Cost |
|---|---:|---:|---:|
| Leadscrew Selection and Calculations | 2 | $35 | $70.00 |
| Crosshead Design | 2 | $35 | $70.00 |
| Motor Selection | 1.5 | $35 | $52.50 |
| Motor Mount and Coupler Design | 2 | $35 | $70.00 |
| Frame Design | 2 | $35 | $70.00 |
| FEA Analysis | 3 | $35 | $105.00 |
| Floating Bearing Mount Design | 1 | $35 | $35.00 |
| CAD Assembly and Drawings | 3 | $35 | $105.00 |
| Documentation | 2 | $35 | $70.00 |
| Total | 18.5 | | $647.50 |

## Lessons Learned


### Dillon Knight
Time Spent:


### Sean Chadwick
Time Spent:


### Marvin Sibelius
Time Spent:

