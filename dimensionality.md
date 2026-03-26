Dimensionality and biodiversity in hyperspectral images
=

The NTNU smallsat lab has been involved in hyperspectral imaging for nearly a decade. The satellites HYPSO-1 and HYPSO-2 are both in orbit, and we are planning a new HYPSO-3 mission.

We now have lots of data to analyze. Come and join us!

Recently, the paper [Intrinsic dimensionality as a metric for temporal plant diversity evaluation](https://esajournals.onlinelibrary.wiley.com/doi/full/10.1002/ecs2.70213) proposed the idea that the biodiversity of an area is related to the intrinsic dimensionality of a hyperspectral image of that area. 
If this hypothesis is true, it would revolutionize hyperspectral remote sensing. It would allow hyperspectral images to be used directly for biodiversity characterization, bypassing the need for algorithms to explicitly label every species in an image. 
More precisely, the authors claim that their method "accounts for subpixel unmixing and does not rely on in situ training data for mapping vegetation variability. "

The goal of this project is then to evaluate the robustness of this claim and to consider whether their methodology can be applied to HYPSO data. I've conceptualized the specialization project and the masters thesis together.
 
The specialization project would explore ID and biodiversity with the same dataset used in the original paper (the authors have made it [publicly available](https://impact.earthdata.nasa.gov/casei/campaign/SHIFT/#data)), using new methods of determining intrinsic dimensionality, such as the Generalized Ratios Intrinsic Dimension Estimator (GRIDE). We've used GRIDE a bit with hyperspectral images and have some (fairly slow) code already. Your task would be to assess whether the apparent relationship between biodiversity and ID persists even when a different technique is used to estimate ID, and to think about the limits of the connection, such as which ecosystems it applies to.

The masters thesis would the explore the possibility of using intrinsic dimensionality to explore biodiversity in other hyperspectral data, probably from the HYPSO-1 and -2 satellites, but maybe others as well. If the specialization project suggests it is feasible for aquatic ecosystems, we could apply it to them, but if it only works on land, then forests would probably be an appropriate ecosystem to consider. 
