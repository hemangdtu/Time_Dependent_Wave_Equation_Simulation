# Schrodinger’s Time Dependent Wave Equation Simulation
A Python code to simulate Schrodinger’s Time Dependent Wave Equation Simulation for Particle in a Box (1D).

#### Importance of Schrödinger’s Wave Equation
Schrodinger wave equation is a mathematical expression describing the energy and position of the electron in space and time, taking into account the matter wave nature of the electron inside an atom. It is based on three considerations which are listed below:
<UL>
<LI>Classical plane wave equation</LI>
<LI>Broglie’s Hypothesis of matter-wave</LI>
<LI>Conservation of Energy</LI>
</UL>
Schrodinger equation gives us a detailed account of the form of the wave functions or probability waves that control the motion of some smaller particles. The equation also describes how these waves are influenced by external factors. Moreover, the equation makes use of the energy conservation concept that offers details about the behaviour of an electron that is attached to the nucleus.
Besides, by calculating the Schrödinger equation we obtain Ψ and Ψ2 which helps us determine the quantum numbers as well as the orientations and the shape of orbitals where electrons are found in a molecule or an atom.
There are two equations which are time-dependent Schrödinger equation and a time-independent Schrödinger equation.

#### Time Dependent Equation for Particle in an Infinite Square Well case
The initial ψ(x, 0) is generated by a complex gaussian wave packet.

The first step is to normalize the wave function given by the equation below,<br>
<img src = "https://github.com/hemangdtu/Time_Dependent_Wave_Equation_Simulation/blob/main/Images/Normalization%20Equation.png">

Now, the energy Eigen-state wave functions are then found. Again, the energy Eigen-state wave function need to be normalized and the following equation is derived,<br>
<img src = "https://github.com/hemangdtu/Time_Dependent_Wave_Equation_Simulation/blob/main/Images/Eigen%20state%20function.png">

Discrete quantized wave vectors are required to solve the Time-Dependent equation, ψ(x, t). The energy quantization for the system becomes,<br>
<img src = "https://github.com/hemangdtu/Time_Dependent_Wave_Equation_Simulation/blob/main/Images/Energy%20function.png">

Finally, the last item the time dependent Schrödinger equation depends on is Cn, the expansion coefficient that changes the probability amplitude. The indefinite integral of the complex conjugate of eigenstate wave function and the initial wave function with respect to the spatial dimension x,<br>
<img src = "https://github.com/hemangdtu/Time_Dependent_Wave_Equation_Simulation/blob/main/Images/Cn%20function.png">

Thus the final result that we can obtain by combining the expressions for ψn(x), En and Cn is,<br>
<img src = "https://github.com/hemangdtu/Time_Dependent_Wave_Equation_Simulation/blob/main/Images/psi%20function.png">

Now, as t increases the wave equation is determined.

#### Simulation
<img src = "https://github.com/hemangdtu/Time_Dependent_Wave_Equation_Simulation/blob/main/Sample%20Simulation.gif">

#### Conclusion
Following are the conclusions that we can derive after gaining the simulation and mathematical solution of the wave equation,
<UL>
<LI>The mathematical result for the solution of the wave equation turned out to be a complex value consisting of a real and an imaginary part.</LI>
<LI>We plotted the absolute values, real values and imaginary values on the plot plane and used pause() function available in matplotlib Python Library to obtain a simulation out of continuous plotting of the results.</LI>
<UL>
