# Trapped atoms in spatially-structured vector light fields
The Mathematica code reproduces the results presented in the article: [“Trapped atoms in spatially-structured vector light fields”](https://doi.org/10.1038/s41598-023-48589-1), SciRep 13, 21283 (2023). These simulations are a useful theoretical framework for the experiments I directly performed on trapped Ca⁺ ions during my PostDoc in Germany at the Johannes-Gutenberg University of Mainz in the Ferdinand Schmidt-Kaler's [group](https://www.quantenbit.physik.uni-mainz.de/).

* [General info](#general-info)
* [Goal](#goal)
* [Usage](#usage)
* [Extensions](#extensions)

## General info
* The software has been created within Mathematica 12 by M. Verde in collaboration with C. T. Schmiegelow and F. Schmidt-Kaler
* It enables the calculations described within the paper [“Trapped atoms in spatially-structured vector light fields”](https://doi.org/10.1038/s41598-023-48589-1)
* It can be used and modified in agreement with the GNU General Public License v3.0

## Goal
* The goal of the software is providing a computational framework for further scientific development in the area of quantum-optics, -sensing and -information
* The software offers a set of computational tools to design and engineer the interaction between singly trapped atoms or ions and spatially-structured light fields, with special attention to light beams carrying orbital angular momentum
* The readers of our work can use the software as a guide to adapt our calculations to their specific case of interest 

## Usage
* Set the desired parameters describing the Hermite-Gaussian and Laguerre-Gaussian vector beams used in our software
* The calculations does apply to different atoms and ions species under the hypotheses discussed in our work
* Calculate the angular part of matrix element for different quadrupole Zeeman transitions and for different geometries of light propagation direction and magnetic field quantization axis
* Calculate the strenght of motional excitations occurring along the quadrupole transitions under different trapping potentials in the side-band resolved regime

## Extensions
* Arbitrary spatially-structured vector beams can be defined and used in place of the Hermite-Gaussian and Laguerre-Gaussian vector beams used in our software
* Further generalization can explore the role of structure light fields in newly designed optical traps or take into account the spatial extension of the electronic wavefunction, which is relevant for Rydberg atoms or ions
