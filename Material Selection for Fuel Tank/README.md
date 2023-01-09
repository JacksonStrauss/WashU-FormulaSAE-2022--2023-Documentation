# Material Selection for Fuel Tank

For the WUFR-22 car (the previous season), the team had decided to create a 3D printed fuel tank out of [Nylon PA 12](https://www.protolabs.com/media/1021634/sls-data-sheet-pa-12-white-f.pdf). The tank was printed as two separate parts and then would be connected together using fasteners. One half of the printed fuel tank had baffles in order to reduce the sloshing inside the fuel tank. 

This fuel tank concept was good in theory but had some issues that needed to be solved for the 2022-2023 season. For example, the Nylon PA 12 did not have a high enough [HDT (Heat deflection temperature)](https://en.wikipedia.org/wiki/Heat_deflection_temperature) and so parts of the fuel tank deformed due to the heat that was radiating from the exhaust tubes. The fuel tank did not incorporate an O-ring/gasket and so fuel could easily escape the system. Lastly, because the baffles were connected from the top half of the fuel tank, air was trapped at the top of the fuel tank and reduced the amount of fuel the tank could hold. As such, the car ran out of fuel just as it was about to reach the finish line. (See image of trapped air in baffles below)

(image of trapped air)

There are several other important factors to take into account when selecting the material of the fuel tank. Keeping the price of manufacturing the fuel tank is important because the team runs a tight budget and sometimes you have to prioritize cost efficiency over other capabilities of the design. The density of the material for the fuel tank is an important factor because on a race car you want to keep components as light as possible. (The principle where F = ma which means that a = F/m so if you keep force constant and decrease mass then you have a higher acceleration which means that the race car can travel faster.) You also need to have a material that is highly corrosive resistant so that it won't corrode when it comes into contact with the fuel.

Below is a table comparing some of these factors for different material considerations for the fuel tank:

| Material | Price | Density | HDT at 66 psi | Compression Yield Strength | Design Constraints |
| --- | --- | --- | --- | --- | --- |
| Aluminum Sheet Metal | Relatively cheap | 2.7 g/cm3 | HDT not an issue for aluminum | ~450 MPa | Fuel tank would be one part; holley hydramat permanently sits inside the tank; It's difficult to create openings in the tank for fuel lines, filler neck, etc; Fuel tank can't necessarily be designed with optimal geometry (weight-savings) because difficult to weld/fold |
| [Nylon PA 12](https://www.protolabs.com/media/1021634/sls-data-sheet-pa-12-white-f.pdf) | ~$1,800 | 1.02 g/cm3 | 350 °F | 327 MPa | Heat shield would be required; Fuel tank would consist of 2 separate printed pieces |
| [Ultem 1010 Resin](https://www.stratasys.com/siteassets/materials/materials-catalog/fdm-materials/ultem1010/mds_fdm_ultem-1010-resin_0921a.pdf?v=48e257) | ~$2,500 | 1.29 g/cm3 | 417 °F | 245 MPa | Fuel tank would consist of 2 separate printed pieces |

I initially decided that a Nylon PA 12 3D printed fuel tank would be the best choice because although it would require a heat shield, it would be less expensive than other plastic alternatives and we would have experience with the material since it was used the previous year. So I got to work designing a 3D printed fuel tank in CAD.

Later in the semester though, some of my lead members recommended that I revisit the idea of doing an aluminum sheet metal fuel tank, and that it would not be as difficult to manufacture as originally thought. I determined that the aluminum fuel tank would weight ~1.44 lbs while the nylon fuel tank would weigh ~1.53 lbs not including the heat shield and heat shield mounting.
