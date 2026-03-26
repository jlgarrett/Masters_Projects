Multiframe fusion in high-dimensional remote sensing
=
This project with be co-supervised by our collaborators at [Tycho Space](www.tychospace.no)

The NTNU SmallSat lab is contributing a [polarized red-green-blue (P-RGB) camera](https://www.opto-e.com/en/products/itala-g-series/ITA120-GC-11C-PL) to two upcoming satellites: Solan-TD, supporting [Tycho Space](https://www.tychospace.no/), and HYPSO-3. 
This camera can resolve finer spatial details on the ground than the hyperspectral cameras (2.9m spatial resolution), and will be used to define a grid on which to rectify the hyperspectral images. 
Moreover, the polarization information will be used to determine the contribution of aerosols and water vapor to optical transmission through the atmosphere.

To achieve a ground resolution of 2.9m without blur, the exposure time must be quite low, e.g. < (2.9m / 7.6km/s) ~ 0.4ms. Thus, a single image will be darker than desired for the final analysis. To compensate for this, the camera will take many images at about 17 frames per second. 
Then, those images must be fused together in a way that preserves spatial features while also increasing the signal level. 

There are algorithms for this for RGB images, but they do not preserve polarization information, e.g. [Multiframe demosaicing and super-resolution of color images](https://ieeexplore.ieee.org/abstract/document/1556633). 
Your task in this project would be to develop an algorithm to fuse P-RGB images, preserving the polarization information. We have P-RGB cameras in the lab which you can use for data collection. In addition to prototyping the algorithm, the project could also include an analysis of computational / memory complexity and an analysis of the feasiblitiy of on-board implementations.
