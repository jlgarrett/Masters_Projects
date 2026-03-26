Hyperspectral unmixing with Simulated Annealing
=

The NTNU smallsat lab has been involved in hyperspectral imaging for nearly a decade.
One of the most common analysis techniques to apply to hyperspectral data is unmixing.
A few months ago, I was comparing a new unmixing technique against traditional methods, and I realized that an ancient numerical optimization method known as Simulated Annealing (SA) could minimize the unmixing objective function if a few constraints are applied.
A simple implementation of SA-unmixing showed performance comparable to more modern deep learning methods. 
While I had been mainly concerned with using SA-unmixing as a comparison, its surprisingly good performance has convinced me that I should offer a masters thesis in which you could explore variants and applications of SA-unmixing in more detail. 

There are a number of different directions that this project could take, depending on what interests a particular student.
Some possible options include:
1) Discritize the abundance matrix: the original SA-unmixing only discritized the spectral matrix, while the abundance matrix was updated according to standard least-squares unmixing.
2) Explore different objective functions: With simulated annealing, the objective function no longer needs to be differentiable. Therefore, more different objective functions are possible
3) Explore how to grow networks in neural-network based unmixing: In deep learning, the network structure is not included in optimization because changes to it are discrete. However, simulated annealing could allow a network to be grown.

This thesis would be an excellent fit for someone who enjoys the creative side of mathematics.
I wrote the basic SA-unmixing in python, but any programming language experience should suffice for this thesis.

Skills you will learn include:
- Hyperspectral data analysis, including unmixing
- Optimization on non-differentiable functions with simulated annealing
- (maybe) growth of neural network architectures with simulated annealing

Some relevant papers:
- [Entropic Descent Archetypal Analysis for Blind Hyperspectral Unmixing](https://ieeexplore.ieee.org/abstract/document/10213413)
- [Optimization by Simulated Annealing](https://hedibert.org/wp-content/uploads/2013/12/1983KirkpatrickGelattVecchi.pdf)
