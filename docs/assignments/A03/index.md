# A3 – [Topic]

## Objective

The Objective of this assignment was to design a bar which has a circular cross section where the values of the criteria given for the material, maximum deflection, and load. Determine the bar’s minimum geometry (ie.. length, diameter, and weight) through parametric design while under direct tension. Then verify the geometry through finite element analysis.

## Analyze

### Cross Sectional Area

The first step in the beam design and length calculation was to find out the cross sectional area of a circular beam. The formula for the cross sectional area of a cylinder is (D^2)*(pi)/4. For this beam design i did some easy mental math and just decided to go with a diameter of .5 inches. Plugging this diameter into the formula gets a cross sectional area of .196 inches^2. 

### Length Calculation

Now that we have the cross sectional area we can find the max length beam without going over the allowed deflection. I did this by using the deflection equation where the deflction = (force*Length)/(Youngs Modulus*Area) and isolate length since all the other variables are known. Since we have the lneght isolated I plugged in all the values and found the maximum lenght of the beam to be 52.92 inches. 

## CAD Modeling

### Parameteric Design

I first plugged all the known values into the equations tab into solid works. Then using these variables in solidworks I used the same formula for length and it solved and gave me a length 53.01 inches. The reason for the difference in lenght from my hand calculation is that solidworks rounded some of my values such as the area and the mas deflection. I then designed my beama nd exturded it using the varibles as my dimensions during the process.

### FEA

Now that the beam model is complete I can run a FEA simulation on it. I set one side as a fixed geometry point and the other side with the load on it. I set the load to -300 lbf so that it would be pulling on the beam and would not be into the beam. 


## Communicate

