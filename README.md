# Introduction
This repository contains code developed to analyze the differential equations that describe compact stars.
In particular, the focus is on the study of white dwarfs and neutron stars.

The purpose of this README is to briefly explain the different scenarios considered in this project, in order to help the reader better understand its structure.

# Background 
This project studies the structure of compact stars such as white dwarfs and neutron stars. Both these kind of objects are described by two fundamental differential equations: 

- one for the mass, given by:

   $\frac{dm}{dr}=\frac{4\pi r^2 \epsilon (r)}{c^2}$

- one for the pressure,  given by:
  
  $\frac{dp}{dr}= -\frac{G \epsilon (r) m(r)}{r^2 c^2}$    or
   $\frac{dp}{dr}= -\frac{G \epsilon (r) m(r)}{r^2 c^2} \bigl[1+ \frac{p(r)}{ \epsilon (r)}\bigr] \\bigl[1+ \frac{4 \pi r^3 p(r)}{ m(r) c^2}\bigr]  \bigl[1 - \frac{2G m(r)}{r c^2}\bigr]^{-1}$

The two possibilities for the pressure differential equation depend on whether one is working in a Newtonian regime (then one should use the first equation) or 
in the General Relativity one (then one should consider the second equations).

One can however notice that the system of these differential equations is actually incomplete since it has three unknown variables and only two equations.
What is in fact missing is a third equation which ties the energy density and the pressure inside the compact object: the equation of state. 
In this project many different equations of state have been studied.


# Project Structure
This repository contains:
- A folder [White Dwarfs](https://github.com/MariaLuciaMarcelli/White-Dwarfs-and-Neutron-Stars/tree/ddae02996478aface23f17790ee452736155701f/White-Dwarfs) which contains the analyis for white dwarfs
- A folder [Pure Neutron Stars](https://github.com/MariaLuciaMarcelli/White-Dwarfs-and-Neutron-Stars/tree/ddae02996478aface23f17790ee452736155701f/Pure-Neutron-Stars) which contains the analysis for pure neutron stars
- A folder [Neutron stars with protons and electrons](https://github.com/MariaLuciaMarcelli/White-Dwarfs-and-Neutron-Stars/tree/ddae02996478aface23f17790ee452736155701f/Neutron%20Stars%20with%20protons%20and%20electrons)  which contains the analysis for neutron stars that also have protons and electrons
- A folder [Neutron Stars compOSE](https://github.com/MariaLuciaMarcelli/White-Dwarfs-and-Neutron-Stars/tree/ddae02996478aface23f17790ee452736155701f/Neutron%20Stars%20compOSE) which contains the analysis of neutron stars described by equations of state obtained by the website [compOSE](https://compose.obspm.fr)

# White Dwarfs

# Pure Neutron Stars

# Neutron Stars with protons and electrons

# Neutron Stars with compOSE

