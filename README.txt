 AUTHOR:

       Davide Fassino 
       Politecnico di Torino, Italy
       E-mail: davide.fassino@polito.it

       Gioana Teora 
       Politecnico di Torino, Italy
       E-mail: gioana.teora@polito.it
       
SOFTWARE REVISION DATE:

      July 2023

 SOFTWARE LANGUAGE:

      Python


============================================================================
SOFTWARE
============================================================================


This software provides all the functions needed to compute approximate
solutions to a parametric dvection-diffusion problem using the Physic
Informed Neural Network (PINN) and the Reduced Order Model (ROM) via the
greedy algorithm. The code to compute the online accuracy and speed-up with 
respect to Finite Element Methods (FEM) is provided.

============================================================================
PACKAGE
============================================================================

The directory contains the following files

README.txt                         : this file
Project_PINN_vs_Greedy.ipynb       : the main file, implementing the ROM
                                     and the PINN approaches and the 
                                     comparison w.r.t. the FEM
data.csv                           : dataset of the parametric values 
                                     selected for the training and the test
                                     phases
mesh001.csv                        : mesh needed to be imported in 
                                     'Project_PINN_vs_Greedy.ipynb'in order 
                                     to visualize the solution


============================================================================
HOW TO USE
============================================================================
Run the file 'Project_PINN_vs_Greedy.ipynb' with Colab.