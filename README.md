# Opening the Density-Functional Theory Black Box
This repository contains three Google Colab notebooks that are designed to facilitate understanding of Density-Functional Theory (DFT) through interactive visualizations. Our motivation for developing this software stems from the knowledge deficiency that is often produced from using DFT as a black box in commercial software. By applying DFT to the familiar particle in a box model system employing a real-space grid basis, we hope to have reduced DFT to its fundamental essence fit for pedagogy. Brief instructions for executing the code are provided in each notebook, and a problem sheet for getting started is attached. Python programming knowledge is not required.
<p align="center"> 
  <img src='https://github.com/BashirovaD/DFT_code/blob/main/figures/graphical_abstract.png' width = "262" height = "300"> 
</p>

## Notebook 1&ndash;Particle in a 3D Box
<img align="right" src='https://github.com/BashirovaD/DFT_code/blob/main/figures/NB1_wavefunction.png' width = "87" height = "100">
In this notebook, we’ll consider the particle in a three-dimensional box system treated in any undergraduate physical chemistry textbook. High-quality energy level diagrams and isosurface renderings of the wavefunction can be generated from user-specified box lengths. Depicted here is the 321 state of an anthracene-like box of dimensions 16 x 8 x 3 Bohr. 
<br />
<br>
<strong> Click here to open the notebook in Google Colab: </strong> 

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/BashirovaD/DFT_code/blob/main/1/3d_PIB1.ipynb)

<br>
<br>
<br>
<br>
<br>
<br>
<br>


## Notebook 2&ndash;PAH Frontier Orbitals
<img align="left" src='https://github.com/BashirovaD/DFT_code/blob/main/figures/NB2_anthracene.png' width = "300" height = "300">
Next, we’ll look at a real chemical system in the form of polycyclic aromatic hydrocarbons (PAHs). We can perform Hartree-Fock/STO-3G calculations to find the shapes and energies of their frontier molecular orbitals, which can make for interesting comparisons with the analogous results from Notebook 1.
<br />
<br>

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/BashirovaD/DFT_code/blob/main/2/PAH_Orbitals1.ipynb)

## Notebook 3&ndash;Density-Functional Theory
<img align="right" src='https://github.com/BashirovaD/DFT_code/blob/main/figures/NB3_density.png' width = "300" height = "300">
Finally, we’ll reconsider the system from Notebook 1, but now we’ll turn on electron-electron interaction through the Kohn-Sham potential. We’ll consider each term of the single-particle Hamiltonian and put everything together into a self-consistent field (SCF) DFT calculation. We can then analyze the how the density and eigeneneriges change as a function of SCF iteration number. LDA and PBE are the available exchange-correlation functionals.
<br />
<br>

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/BashirovaD/DFT_code/blob/main/3/DFT_code1.ipynb)
