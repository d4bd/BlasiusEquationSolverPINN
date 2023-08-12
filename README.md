# Using a Physics Informed Neural Network (PINN) to solve the Blasius equation

Objective of this project is to compare different methods to solve numerically the Blausius equation, for which an analytical solution is still not known.

More in detail, we will compare a standard method for the numerical computation of the solution, given by the *solve_bvp* algorithm of SciPy, to two different implementations of a Physically Informed Neural Network (PINN) [2, 3, 4]:
- the first one implementing an unsupervised learning process,
- the second one implementing a supervised learning process

PINNs are a particular class of neural networks whose study has recently begun, and which are having a lot of success. They have been developped starting from the observation that neural networks are proving to be very effective in solving problems of applied mathematics such as Partial Differential Equations (PDEs).
Aim of this class of algorithms is to compute numerical solutions for differential equations in a more efficient way that standard computational methods. The way they achive this is by exploiting the knowledge of the equation to improve the training of the network (more details on this are provided in the Jupyter notebook of the project)

## References
[1] https://www.cfm.brown.edu/people/dobrush/am33/Mathematica/ch7/blasius.html

[2] Raissi M, Perdikaris P, Karniadakis GE (2017c) Physics Informed Deep Learning (Part I): Data-driven Solutions of Nonlinear Partial Differen- tial Equations. URL: http://arxiv.org/abs/1711.10561

[3] Raissi M, Perdikaris P, Karniadakis GE (2017d) Physics Informed Deep Learning (Part II): Data-driven Discovery of Nonlinear Partial Differen- tial Equations. URL: http://arxiv.org/abs/1711.10566

[4] Cuomo, S., Di Cola, V.S., Giampaolo, F. et al. Scientific Machine Learning Through Physics-Informed Neural Networks: Where we are and What's Next. J Sci Comput 92, 88 (2022). DOI: https://doi.org/10.1007/s10915-022-01939-z

[5] https://www.youtube.com/watch?v=vWcRuay1tt4

[6] Nascimento RG, Fricke K, Viana FA (2020) A tutorial on solving ordinary
differential equations using python and hybrid physics-informed neural net-
work. Engineering Applications of Artificial Intelligence 96:103,996. DOI: https://doi.org/10.1016/j.engappai.2020.103996, URL: https://www.sciencedirect.com/science/article/pii/S095219762030292X

[7] https://github.com/maziarraissi/PINNs/tree/master

[8] https://i-systems.github.io/tutorial/KSME/CAE/220520/01_PINN.html

[9] https://colab.research.google.com/drive/1BzjE3opm7nlyIQmaidxEhiaJ88rhnoiZ
