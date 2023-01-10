# Welded Aluminum Sheet Metal Tank

For the welded aluminum sheet metal fuel tank, the same design requirements as the 3D printed fuel tank are present but I'll list them again here:
* The tank needed to have around 5 Liters of capacity.
* A taller fuel tank is sometimes better because it reduces the amount of sloshing in the tank. However, a shorter/flatter fuel tank makes it so that the fuel tank has a lower center of gravity. (You want to try and keep most components on a race car as low as possible because that keeps the car's center of gravity low and the tires get better grip on the road.) 
* The tank needed to attach via at least three easy to access tabs to the frame of the car.
* Try to keep the weight of the fuel tank as low as possible without risking structural integrity
* It's best to keep the fuel tank as far away as possible from the exhaust because using colder fuel runs the engine more efficiently. [(1)](https://www.racecar-engineering.com/articles/f1/technology-explained-f1-fuel-systems/)
* The fuel tank must have room for the Holley Hydramat at the bottom. 

#

To start off though, I first needed to determine what type of aluminum alloy to use for the fuel tank. Common aluminum types include the 2000, 3000, 5000, 6000, and 7000 series. Below is a table listing each aluminum alloy with their properties and strengths

| Alloy | Yield Strength | Modulus of Elasticity | Fatigue Strength | Corrosion Resistance | Weldability | Other |
| --- | --- | --- | --- | --- | --- | --- |
| [2024 Aluminum](https://www.thomasnet.com/articles/metals-metal-products/6061-aluminum-vs-2024-aluminum-differences-in-properties-strength-and-uses/) | 324 MPa | 73.1 GPa | 138 MPa | Requires cladding? | Not great | |
| [3003 Aluminum](https://www.thomasnet.com/articles/metals-metal-products/3003-aluminum/) | 186 MPa | 68.9 GPa | 115 MPa | Decent | Good | Commonly used in fuel tanks |
| [5052 Aluminum](https://www.thomasnet.com/articles/metals-metal-products/6061-aluminum-vs-5052-aluminum/) | 193 MPa | 70.3 GPa | 115 MPa | Very Good | Good | Commonly used in fuel tanks |
| [6061 Aluminum](https://www.thomasnet.com/articles/metals-metal-products/6061-aluminum-vs-5052-aluminum/) | 276 MPa | 68.9 GPa | 96.5 MPa | Very Good | Good | Cracks when bending |
| 7075 Aluminum | | | | | | [Doesn't bend well](http://haomei-aluminium.com/en/News/Knowledge/7075-aluminum-sheet-bending.html) |

A really important requirement is that the sheet metal has to be able to be bent into shape. If a certain alloy cracks when it is bent then it is unusable for the aluminum fuel tank. I ultimately decided to use 5052 Aluminum for the fuel tank at a thickness of 0.030"

#

Below are a few screenshots of the fuel tank design in SolidWorks. The tank has a flat 3" by 15" base for the [Holley Hydramat (2)](https://www.holley.com/products/fuel_systems/hydramat/). (The Holley Hydramat basically acts as a sponge that absorbs fuel in the tank and thus ensures a constant pump/flow rate of fuel even while some of the fuel might be sloshing in the tank.) 

INSERT SCREENSHOTS

Because the fuel tank is made out of sheet metal, the CAD design also had to be made using SolidWorks' special sheet metal option. This SolidWorks feature allows the user to create a bent sheet metal part that folds up from one flat sheet metal piece. This is really handy because now we can waterjet cut a large piece of aluminum sheet metal and then bend it using a metal brake. Below is a drawing of the fuel tank unfolded and a screenshot of the fuel tank partially unfolded.

INSERT SCREENSHOTS

Another cool feature that this fuel tank implements is that all of the faces on the top side slope upwards toward a singular horizontal face. At the horizontal face is where the fuel filler neck tube is and thus where the air and pressure from the fuel vapors escapes. The top faces have to be sloped in this manner because the gas needs to always be traveling upwards towards the filler neck so that it does not get trapped inside the tank. Getting this design down probably took longer than it should have. It works by having each of the faces normal to the top horizontal face having the same angle of depression (2°) and then creating diagonal faces in between that line up with the faces at 2°.

INSERT SCREENSHOTS

#

### References
1. https://www.racecar-engineering.com/articles/f1/technology-explained-f1-fuel-systems/
2. https://www.holley.com/products/fuel_systems/hydramat/
[2024 aluminum spec sheet](https://www.thomasnet.com/articles/metals-metal-products/6061-aluminum-vs-2024-aluminum-differences-in-properties-strength-and-uses/)
[5052 aluminum spec sheet](https://www.thomasnet.com/articles/metals-metal-products/6061-aluminum-vs-5052-aluminum/)
[3003 aluminum spec sheet](https://www.thomasnet.com/articles/metals-metal-products/3003-aluminum/)
[6061 aluminum spec sheet](https://www.thomasnet.com/articles/metals-metal-products/6061-aluminum-vs-5052-aluminum/)
[7075 not bending well](http://haomei-aluminium.com/en/News/Knowledge/7075-aluminum-sheet-bending.html)
