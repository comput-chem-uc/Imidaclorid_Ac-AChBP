# "What Can Nature Tell About Relevant Amino Acids to Be Incorporated in Pesticide-Adsorbing Materials? A Multi-Stage Computational Approach"

J. R. C. Santos, P. E. Abreu, and J. M. C. Marques



## DESCRIPTION OF FILES:


### GROMACS INPUT FILES:

In the directory "gromacs-input-files" we include the topology, the molecular dynamics parameters and the coordinates files to run MD Simulations for each system.
The directory is divided in subdirectories named "1chain" and "2chains" where you can find the corresponding inputs files for the simulations using eitheir one chain and two chains of the protein.

Files in the "1chain" directory for each system:

"minim.mdp"     - input parameter file to run the energy minimization

"nvt.mdp"       - input parameter file to run the temperature equilibration (NVT)

"npt.mdp"       - input parameter file to run the pressure equilibration (NPT)

"md.mdp"        - input parameter file to run the main MD trajectory

"ions.mdp"      - input parameter file of the ions

"IMD_GMX.itp"   - topology file for the imidacloprid molecule including the forcefield parameters 

"imd_atoms.itp" - atomtypes file used in the simulation

"topol.top"     - topology file of the system, where the topology of the protein is included

"npt.gro"       - system coordinates (complex + solvent + ions) file after minimization and equilibrations


<br>

Files in the "2chain" directory for each system:

"minim.mdp"     - input parameter file to run the energy minimization

"nvt.mdp"       - input parameter file to run the temperature equilibration (NVT)

"npt.mdp"       - input parameter file to run the pressure equilibration (NPT)

"md.mdp"        - input parameter file to run the main MD trajectory

"ions.mdp"      - input parameter file of the ions

"IMD_GMX.itp"   - topology file for the imidacloprid molecule including the forcefield parameters 

"imd_atoms.itp" - atomtypes file used in the simulation

"topol.top"     - topology file of the system

"topol_Protein_chain_A.itp" - topology file for the chain A of the protein including the forcefield parameters

"topol_Protein_chain_B.itp" - topology file for the chain A of the protein including the forcefield parameters

"npt.gro"       - system coordinates (complex + solvent + ions) file after minimization and equilibrations



<br>

For help and support please contact: qtmarque@ci.uc.pt

GROMACS is freeware downloadable from https://www.gromacs.org/

(see GROMACS users manual for more info https://manual.gromacs.org/documentation/2019/index.html)
