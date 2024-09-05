# BHimaging
_A modern rethinking of Luminet  (1979)_

In this tutorial we rethink the derivations of 
[Luminet (1979, A&A 75, 228)](https://ui.adsabs.harvard.edu/abs/1979A&A....75..228L/abstract)
and we study, using a modern computer-based approach, the image of an
accretion disk around a non-rotating black hole (BH).

![image](https://github.com/user-attachments/assets/d467ade8-1156-4b58-97b2-23fed5be9068)

## Purposes and cautionary notes

The tutorial has been inspired by the “Interstellar” movie and the simulations displayed there.
We will cover ideas, ranging from classical mechanics to spherical trigonometry, to numerical techniques.
Knowledge of General Relativity is only necessary to solve the questions of Sect. 2 (but one can just use
the results provided as granted and skip this part). Knowledge of a programming language is necessary
to implement some numerical exercises; the solutions are here given in Python.

The tutorial, necessarily, simplifies a lot of what is shown in “Interstellar”. As a start, we consider 
a non-rotating (symmetric) black hole, instead of a rotating one and we generally assume the observer is
very distant. For a deeper understanding of the “Interstellar” simulations see 
[James et al. (2015, Class. Quantum Grav. 32 065001)](https://iopscience.iop.org/article/10.1088/0264-9381/32/6/065001) 
and [James et al. (2015, Am. J. Phys. 83, 486)](https://pubs.aip.org/aapt/ajp/article/83/6/486/1057802/Visualizing-Interstellar-s-Wormhole).



