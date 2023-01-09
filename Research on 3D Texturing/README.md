# Research on 3D Texturing

One of the main research components for the fuel tank that I conducted for the 2022-2023 season was to determine whether it would be possible to incorporate a 3D bead pattern. This would increase the strength of certain material properties for the walls of the fuel tank while using less material at the same time. This technique of finding the optimal positions in space for where to place material and where to remove material in order to create a strong and efficient part is called [Toplogy Optimization (1)](https://en.wikipedia.org/wiki/Topology_optimization).

And so for the 3D printed plastic fuel tank, we were wondering whether adding 3D texturing would strengthen certain components as illustrated in [this video (2)](https://www.youtube.com/watch?v=3-ygdNQThAs). We wanted to replicate the types of bead patterns that can be found on common sheet metal products as seen in the video.

[This article (3)](https://www.scinapse.io/papers/2020293008) highlights some important things to keep in mind when trying to incorporate a 3D bead pattern for topology optimization. It can be difficult to design a proper bead pattern without using correct methods and if done incorrectly, the bead pattern can actually make the final product weaker than before. Therefore, implementing a 3D textured bead pattern isn't as easy as putting in a few slots where it seems like it would work. 

Dassault Systèmes actually has [generative design software (4)](https://www.engineering.com/story/fastest-ways-to-optimize-designs-for-manufacturing-with-generative-design-on-the-cloud) which can perform the bead optimization. The program comes in a package that costs $60. 

One other thing to keep in mind is that we were going to use the bead optimization for 3D printed components. 3D printed components can have different material properties depending on the orientation and settings used to print the part. I'm not sure whether this would impact the effect of the optimized bead pattern on the fuel tank.

Ultimately we chose to create the welded aluminum sheet metal design for the fuel tank which does not utilize 3D bead pattern texturing. I tried to create some bead patterns manually for the plastic fuel tank in CAD software but the difference seemed negligible in Finite Element Analysis when compared to the fuel tank without the bead patterns. It would be interesting to see in the future if the generative design software which calculates the optimal bead pattern has a noticeable effect on the structural properties of the fuel tank.

### References
1) https://en.wikipedia.org/wiki/Topology_optimization
2) https://www.youtube.com/watch?v=3-ygdNQThAs
3) https://www.scinapse.io/papers/2020293008
4) https://www.engineering.com/story/fastest-ways-to-optimize-designs-for-manufacturing-with-generative-design-on-the-cloud
