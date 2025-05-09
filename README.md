# Introduction
This repository contains code developed to analyze the differential equations that describe compact stars.
In particular, the focus is on the study of white dwarfs and neutron stars.

The purpose of this README is to briefly explain the different scenarios considered in this project, in order to help the reader better understand its structure.

# Theoretical Background 
The fundamental equations describing the internal structure of compact stars are:

- $\frac{dm}{dr}=\frac{4\pi r^2 \epsilon (r)}{c^2}$

- $\frac{dp}{dr}= -\frac{G \epsilon (r) m(r)}{r^2 c^2}$    or
   $\frac{dp}{dr}= -\frac{G \epsilon (r) m(r)}{r^2 c^2} \bigl[1+ \frac{p(r)}{ \epsilon (r)}\bigr] \\bigl[1+ \frac{4 \pi r^3 p(r)}{ m(r) c^2}\bigr]  \bigl[1 - \frac{2G m(r)}{r c^2}\bigr]^{-1}$

The two possibilities for the pressure differential equation depend on whether one is working in a Newtonian regime (first equation) or 
in the General Relativity one (second equation).

To solve these equations,one also must provide an equation of state (EoS) which relates the pressure p to the energy density $\epsilon$. 

In this project many different equations of state have been studied.


# Project Structure
This repository includes:
- [White Dwarfs](https://github.com/MariaLuciaMarcelli/White-Dwarfs-and-Neutron-Stars/tree/ddae02996478aface23f17790ee452736155701f/White-Dwarfs): analysis of white dwarfs;
- [Pure Neutron Stars](https://github.com/MariaLuciaMarcelli/White-Dwarfs-and-Neutron-Stars/tree/ddae02996478aface23f17790ee452736155701f/Pure-Neutron-Stars):  analysis of pure neutron stars;
- [Neutron stars with protons and electrons](https://github.com/MariaLuciaMarcelli/White-Dwarfs-and-Neutron-Stars/tree/ddae02996478aface23f17790ee452736155701f/Neutron%20Stars%20with%20protons%20and%20electrons):  analysis of neutron stars that also contain protons and electrons;
- [Neutron Stars compOSE](https://github.com/MariaLuciaMarcelli/White-Dwarfs-and-Neutron-Stars/tree/ddae02996478aface23f17790ee452736155701f/Neutron%20Stars%20compOSE) : analysis of neutron stars described by equations of state obtained by the website [compOSE](https://compose.obspm.fr).

## White Dwarfs
This section includes code for analyzing white dwarfs in different scenarios:
- Non relativistic and relativistic polytropic EoS in a Newtoninan regime;
- Non relativistic and relativistic polytropic EoS in a General relativity regime;
- A more realistic EoS obtained using a root-finding routine in a General relativity regime. 

## Pure Neutron Stars
The analysis of pure neutron stars has been organized similarly to the White Dwarfs' one. 

Additionally, it includes code that highlights the differences between the Newtonian and the General Relativity regimes.

## Neutron Stars with protons and electrons
This section analyses neutron stars composed of neutrons, protons and electrons. The code explicitly computes the total pressure and energy density and obtains a more realistic equation of state through a root-finding routine.

## Neutron Stars with compOSE
Finally, this section includes an analysis of neutron stars described by realistic equations of state obtained by the website [compOSE](https://compose.obspm.fr). 

It also contains the used EoS data files. 

# References 
The references for this project have been:
- *Compact Stars for Undergraduates* , Irina Sagert, Matthias Hempel, Carsten Greiner, and Jurgen Schaffner-Bielich
- *Computational Physics, Lecture Notes Fall 2015*, M. Hjorth-Jensen (in particular Part III)

