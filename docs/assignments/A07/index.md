# A7 – FEA on Bracket

## Objective

The Objective of this assignment was to create a high stiff, high strength, and lightweight component. Use Finite Element analysis to drive your decision making process throughout your design. Each step of the analysis and before you make geometric changes make sure the component’s results (stress/displacement/Safety Factor) converge on a 7% difference. Achieve this by modifying the number of elements. If after three attempts to converge use the stiffness and stress from the finer mesh size use the finest mesh size and proceed through the process. 

## CAD Modeling

### Design 1

My first design I pulled directly from the last assignment. I set up the FEA by putting the 500lbf load at the bottom bottom of the piece and i set the inside tops of the inside as a fixed geometry. I then ran the FEA simulation on it and did a coarse mesh and he are the results for that.  

![A7](d1c1.png)
![A7](d1s1.png)
![A7](d1df1.png)
![A7](d1sf1.png)

I had a max stress of 20020 psi, A max deflection of .01338 inches, and a minimum safety factor of 1.992 

Next i took the same design but used a finer mesh of a medium size and reran all the simulations 

![A7](d1c2.png)
![A7](d1s2.png)
![A7](d1df2.png)
![A7](d1sf2.png)

I got a max stress of 24740 psi, a max deflection of .01416 inches, and a minimum safety factor of 1.612, using the formula for convergence of (2(Xf-Xi)/(Xf+Xi)) I got a convergence of 21.9 percent for my stress, 5.7 percent for my deflection, and 21.1 percent for my safety factor. Since only my deflection is within the 7% allowance i will have to optimize my design and redo the simulations 

### Design 2

Here is the second design. Looking at my first simulations i saw the stress was mainly in the connector arm and it was also very high. Because of this I made the connector arm much thicker and added a fillet since the stress was locking onto the sharp edges. I then took off a lot of material from the top half as a lot of it was under barley any lo0ad and was not necessary to i got rid of it to reduce material and weight. I then ran the same simulations on it and here are the results 

![A7](d2c1.png)
![A7](d2s1.png)
![A7](d2df1.png)
![A7](d2sf1.png)

It had a max stress 10000 psi which is a lot lower then the first design, it had a max deflection of .004346 inches which is also better, and a minimum safety factor of 3.989 which is also better than the first design all while taking a lot of material off overall.  

I then changed my mesh to a finer medium size and redid the simulation 

![A7](d2c2.png)
![A7](d2s2.png)
![A7](d2df2.png)
![A7](d2sf2.png)

I got a max stress of 15540 psi, a max deflection of .004690 inches, and a minimum safety factor of, 2.566. This gave me a convergence of 43 percent for stress, 7.6% for my deflection, and 43 percent. This is quite confcuting since all metrtircs of my design perfomred better with less material, lower stress, lower deflection, and a better saftey faccor but my convergnge for stress and saftey factor increased greatley. Since these are outside the alloable range i did a third design.

### Design 3 

Since i had already cut out a lot of material I wanted to focus on lowering my max stress and trying to get my convergence to be better. In order to do this I added a second connecting bar instead of just having one which should make the stress and deflection more uniform. I then ran the simulations and here are the results 

![A7](d3.png)


![A7](d3c2.png)
![A7](d3s2.png)
![A7](d3df2.png)
![A7](d3sf2.png)

It had a max stress of 7391 psi, max deflection of .0009881 inches, and a minimum safety factor of 5.397

I then changed the mesh size to be finer and rerun the simulations

![A7](d3c1.png)
![A7](d3s1.png)
![A7](d3df1.png)
![A7](d3sf1.png)

It had a max stress of 9539 psi, a max deflection of .001091 inches, and a minimum safety factor of 4.168. This gives a convergence of 25 percent for the stress, 9 percent for the deflection, and 25 percent for the safety factor. These are better than the previous and the overall design is much better optimized but the convergence is still not in the allowed 7%.

## Reflections

This assignment showed me really how you can optimize the design based on the FEAs. For example i saw where my stresses were really high in the FEA and added material or altered the geometry to make it more distributed and where there was material with almost 0 load on it in the FEA i saw to remove that material as it was not needed allowing me to better optimize my design quicker. This assignment took me about 3 hours from start to finish. 


## Communicate

