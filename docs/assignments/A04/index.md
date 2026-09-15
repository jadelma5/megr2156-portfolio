# A4 – Motor Mount

## Objective

The objective of this assignment was to design a motor mount using a given brushed gear motor that attaches to a rigid wall. We have to decide the thickness of two features one which is attaches to to the motor and one which is attached to the wall by using the stress and deflection equations. We are using an ABS material with a safety factor of 3 and the initial force is 300 N.

![instructions](instructions.png)
## Analyze

### Feature 1 
The first feature I had to work on was the part that was directly attached to the motor. I decided to make the length and width of this feature to be 40 mm to make sure it is big enough to fit the motor no problem and to try and minimize the stresses and deflection. I first listed all the knowns and unknowns and drew the free body diagram to better understand.

![known](Knowns1.jpg)

From the free body diagram I see I am dealing with moment which is just force * distance but since the force is not being applied to the mount and to the motor itself the distance is the length of the motor shaft from the feature.

![FBD1](FBD1.jpg)

Now that I have all my known variables I know that I have to solve for the thickness of the feature. I will do this by using both the bending equations for stress and deflection and isolating the h or thickness

![symbolic](symbolic.jpg)

With these symbolically solved equation all I need to do is plug in all of the known numbers and get the thickness. The stress equation got me a thickness of 9.06 mm and the deflection equation got a thickness of 19.35 mm. I will choose the larger thickness of 19.35 mm as we want to make sure this piece will not fail any of the intial conditions given.

![number](Numerical1.jpg)

### Feature 2 

Since we have the first feature done which directly connects to the motor we can now move to the feature that connects the rest to a wall and secures it. To make this motor mount more symmetrical and maybe easier to produce I also made the height of this section to be 40 mm as well. This feature will also be made out of ABS material and all of the knowns and unknowns are listed below. 

![feature](Feature2.jpg)

We again don't know the h or thickness of this feature and have to solve for it. The first step in doing so is to create a free body diagram. This diagram shows how only the upper portion of the feature is connected to a rigid wall meaning the bottom is allowed to move. We then use that length from where it is allowed to move combined with the previous thickness and motor shaft length to get our distance for the moment. This moment is now larger than the original as the distance is greater. 

![FBD2](FBD2.jpg)

From there we now use the same stress and deflection equations to solve for the thickness. Since the equations have already been symbolically solved I then plugged in the variables and got a thickness of 14.7mm from the stress equation and 26.7mm from the deflection equation and went with the larger one again to ensure the mount can handled all the stresses. 

![sym](Sym2.jpg)
![number](numsym.jpg)

### Isometric Sketch

Having all the values for the whole design a made a hand drawn sketch of the features. This includes all of the holes need to both attach the motor to the mount and the holes needed to attach the mount to the rigid wall. This rough sketch also helps me to see the the whole design allowing me better understand what I need to do for my CAD model. 

## CAD Model

### Paramteric Modeling

To start my CAD model I first plugged in all of my variables and used the equation solver to compute my thickness values and double check them. After confirming all my values are accurate I then used the values in my model to ensure it is all correct size so the motor would properly fit and all conditions are met. 

1[equations](parametric.png)

I then went to sketch out the side view of the mount and also extruded this sketch to the correct width of 40mm.

![sketch](CADsketch.png)
![extrude](Extrude1.png)

After having my whole basic motor mount I then put in a recess to that the motor would sit flat on the motor and be secure.

![recess](Holebig.png)
![hole](Hole1.png)

Now that I have this recess I put holes all the way throughout the mount to that the shaft can go through and so we can screw the motor into the mount itself and be secure.

![motor](motorfit.png)

The final holes I added on were the holes in feature two that allows the mount to be connected to the rigid wall.

![wall](Wallhole.png)

Lastly I added my own design to the mount that was not included in the assignment. I added an extra diagonal piece that farther connects feature one to feature 2. This diagonal piece further helps to distribute the load and minimizes the deflection for the whole design.

![extra](extradesign.png)

Here is the whole model fully completed and ready to be used. 

![final](Fullmodel.png)

[Link for Motor Mount CAD model](designhw4.prt.1)

## Communicate

This assignment took me about 4 hours to complete. Most of the the time was used towards the calculations and the hand sketch's as I am coming more familiar with the parametric CAD modeling. I also started this assignment earlier in the week to not be rushed and have plenty of time to complete. 
