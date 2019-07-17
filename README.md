# Generalized-SU2-Proca

The following repository contains 4 codes that were developed in 2019 by Juan Camilo Garnica Aguirre as a contribution to the research he made in order to achieve the title of 'Physicist' at Universidad Industrial de Santander, Colombia. 
Its corresponding dissertation manuscript was entitled:

"_Inflación y energía oscura en la teoría SU(2) generalizada de Proca_" (Original in spanish).

_ _ _

**In** ***Mathematica:***

* _EOM_: Was designed to compute the evolution (Euler-Lagrange) equations, evaluate them in components, translate them into a new set of adimensional variables and analyze the stability conditions in the high k (sub-horizon) regime of the most general lagrangian considered here. Other features of this code include: the option to consider more general scenarios with Type I Bianchi universes and orthogonal triads with vectors of different magnitudes, the possibility to compare equations of motion with its manual counterparts (deduced using the formulae shown in the dissertation manuscript), and the implementation of a sector of the code whose only purpose is that of the verification of the isotropy of the Energy-Momentum tensor. Future versions of this code will include the analysis of instabilities and speed of gravity.

* _AllContractions_: Was designed to exhaustively produce all Lagrangians of the form {X^2, XY, XZ, Y^2, YZ, Z^2} (according to '_Stable solutions of inflation driven by vector fields_' by Emami et.al, 2017) which belong to the Lagrangian L2 composed by arbitrary functions of the vector fields and its Abelian strength tensor.

* _LDynamics_: Was designed to develope an exhaustive analysis of the dynamics of the autonomous system of the theory, by computing and clasifying all its critical points at the same time that it analyzes the viability of interesting asymptotic behaviours; it also has a sector of the code whose only purpose is that of the creation of numerical solutions. It is important to remark that in this code it is asumed that the components of hot and cold matter are independent, not allowing relativistic particles to decay into non-relativistic particles and viceversa.


**In** ***Maple:***
* _MapleEOM_: Constitutes an alternative to the code '_EOM_' in order to copmute the evaluation in components and translation into adimensional variables of the evolution equations. This code lacks of many functionalities that '_EOM_' offers; however, its processing time is way much shorter and, hence, it works very well to verify the evolution equations produced by '_EOM_'. On the other hand, this code is also useful to demonstrate that the conservation equation DivT=0 is satisfied automatically when the evolution equations for the vector fields and the metric hold, and hence, DivT=0 doesn't constitutes an independent constrain equation.


_ _ _ 

The notation implemented in this codes (especially those of _Mathematica_) resembles the notation used in every standard General Relativity textbook. In case of doubts or suggestions, you can contact the author via e-mail: juancagarnica@hotmail.com .

- - -
