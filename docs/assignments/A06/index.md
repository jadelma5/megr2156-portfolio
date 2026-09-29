# A6 – [Bracket Drawing]

## Objective

The objective for this assignment was to generate a comprehensive solid model and a multi-view engineering drawing that accurately represents your designed bracket, incorporating all features to ensure both strength and stiffness requirements are met.

## CAD Modeling

### Parametric Model

The first thing to was to decide to use either my siffness of strength values form the previous assignment. I decided to go with my strength values as most of them were larger then my sitffness meaning they would meet both requirements under the load. After choosing which design i will be modeloign I started ot enter all of the parameter into my equation editior. After plugging in all equations and numbers into CAD I am now able to model the enitre designin paramtetrically.

![eq](equation1.png)
![eq2](equation2.png)

I first started by modeling the T Block shape into my main body using all of my parametric values and extruded it to 1 inch.

![block](blocksketch.png)
![block2](blockextrude.png)

From there I connected the bottom piece to the underside of the main body using the thickness from my equations.

![bottom](bottomsketch.png)
![bottom2](bottomextrude.png)

Finally I connected the cylinder feature that allows the strap to hook onto the design and my model was finished.

![circle](circlesketch.png)
![final](final.png)

## CAD Drawing

Now having the finished my model I can then move onto the drawing. I used third angle projection with an isometric view in the top left. I included all dimension that are necessary to remake this piece and to easily understand what this design looks like. I also added a title and a tolerance block in the bottom right to make sure all relevant information is available. The final thing to do was to add tolerances to the three dimensions that make the shape for the T block to fit in because the T block itself has very specific tolerances for its shape and size.  

![draw](draw.png)

[Part Download](hw6bracket.prt.2)

[Drawing Download](bracketdrawing.drw.2)

[Drawing PDF Download](Hw6drawpdf.pdf)

## Reflections

A.) I used my strength analytical equation to get my radius for the feature that the Uline strap will attach too. The main reason I choose this was because it was larger than my stiffness value so I choose the larger value to ensure it could withstand both strength and stiffness when needed. I first started by entering all of my knowns into equation editor and solve for the Z for a cylinder feature for strength. Once I had my Z I should do ((4*Z)/(pi))^1/3 to get my radius of .4 or a diameter of .8. This is different from my original calculation in the last assignment as it seems i had made an error when plugging in my yield strength and got a diameter of 1.72 instead of .8 but it did not lead to another further errors.  

B.) One dimension I applied a tighter tolerance gap to was my wing thickness on the top of the bracket. I had to apply this tighter tolerance because the T beam itself was already at a tight tolerance and I had to make sure that the T beam would be able to fit into the desired slot so I made sure that the Width was never smaller than the width of the T block to ensure the bracket would fit onto the block and would work properly. A tolerance I allowed to be lower is the outside thickness of the piece since it is not directly interacting with anything and already has a safety factor of 4 meaning it will withstand its load and work properly inside the whole tolerance range     
 
Overall this assignment took me about 4 hours as I am getting better with modeling parametrically 


## Communicate

