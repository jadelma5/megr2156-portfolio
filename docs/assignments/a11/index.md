# A11 – Motor Selection

## Objective  
Our objective this week is develop the motorized drive and structural integration for the 2kN tester, focusing on motor selection, mounting, frame stability, and clamp design. This phase will ensure that the crosshead moves smoothly under controlled torque and speed while maintaining precise load alignment and secure specimen gripping. The motor selection will be based on our data calculated last week through the analysis of the leadscrew, flange, nut, frame and crosshead.  

Key Constraints: 
- No electronics, no software: purely mechanical.
- Load capacity: 2kN (with appropriate safety factor in structure and drivetrain).
- Speed range: 1-50 mm/min (achieved via lead screw selection).
- Form factor: bench-top footprint favored; manageable overall height; 18 inch lead screw minimum
- Safety Factor : 4

Outline:  
1): Motor Selection  
2): Designing Motor Bracket housing  
3): Select or designing coupler  
4): Select connectors for frame
5): FEA for the top of frame  
6): FEA on vertical components of frame  
7): Designing a floating bearing mount  
8): Tabulation  
9): Lessons learned   

## Analyze
### Motor Selection

From the last assignment i learned that with my 1/4 inch lead screw the required toque for each motor would be .6786 N-m and the rotational speed range for this torque is .63 - 31.5 RPM. Based off of this i reachred a;l type of motors and landed on the Nema 23 Bipolar 3Nm(425oz.in) 3.5A 57x57x113mm 4 Wires CNC Stepper Motor. 

![motor](motor.png)
![dimen](dimensions.png)
[Link to Motor](https://www.omc-stepperonline.com/nema-23-bipolar-3nm-425oz-in-3-5a-57x57x114mm-4-wires-cnc-stepper-motor-23hs45-3504s)

The reason i selected this motor is because first it is a steeper motor which allows it to control its speed and also knows its location so it can be used for precise movements. Second it has a 3nm torque rating which is well above the required torque of .6786 N-m so it has a built and safety factor. Also by looking at its torque speed graph we can see that under 31.5 RPM it still has a output torque of 2.67 N-m which is plenty for this lead screw design. 

![graph](Torquegraph.png)

### Coupler Design

The nest thing to do was to design a coupler that would connect the lead screw to the motor shaft. I first started out by listing all my knowns. I knew the inetrnal diamater of the coupler must be 10 mm as that is the shaft size of the motor, the material of the coupler will be steel so its yeild strength is 250 MPA, and lastlty i know the torque applied to the coupler will be .6785 N-m. From these i know i need to solve for the outer diamatter/ size fo the coupler so it can withstand the torque applied. 

From my calculations I see that i need an outer diameter of at least 10.13 mm but i decided to round up to 10.5 mm to be easier to actually manufacture and to have a built in extra safety factor  

### Mounted Bearing w/ RC3 Class fit  
Justification of each size and location dimension on mount: The bearing bracket sits parallel to the frame of the tensile tester. It will screw into the bottom of the frame using a #9 drill. With the bearing mounts being small, this gives us space to put two with enough distance between them on the frame.  

Noting functional tolerances: RC3 fit for the bearing inner diameter allowing for a slip fit for the lead screw.
#8 screws for the mounting holes, because the diameters allow for little clearance between the chamfer the hole and the head of the screw.  

[Link to Mounted Bearing](https://www.mcmaster.com/4575N33/?utm_term=mounted+sleeve+bearings&matchtype=e&campaignid=22711799005&adgroupid=180671261479&location=9009981&gad_source=1&gad_campaignid=22711799005&gbraid=0AAAAACLR9bxAAeR6trfCg2NwrnhPP943C&gclid=CjwKCAiA5Y_YBhBbEiwAK5Dl7cv5DuWSrVLJgJ4cEetm9r8teNK4lYjQCNme6oHTpvSKDxixhAoPXBoCp3wQAvD_BwE)  

## Decide
_Reference your concept selection (Pugh matrix) here. How does this design follow from that decision?_

## Communicate
