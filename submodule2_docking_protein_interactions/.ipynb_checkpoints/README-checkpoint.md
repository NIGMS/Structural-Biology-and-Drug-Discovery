# Submodule 2- Docking and Protein-Protein Interaction

## Background:
This module takes the user step-by-step through preparing the protein and ligand for docking calculations and analysis. Users can extract the ligands from the protein data bank. Ligands can also be prepared by sketching, generating a 3D structure of the ligand in PDB format.  Examples of PDB drug-protein complexes will be used to demonstrate docking using docking software. Analysis and preparation of files for presentation and detailed description are provided. In addition, users can visualize protein-protein interactions and analyze the details of interaction sites. Autodock  software is used for docking ligands to protein molecules. PyMol is used for visualization and Cluspro is used for generating protein-protein complexes using individual PDB files. Each part involves examples and tutorials using visualization software. Quizzes and assignments are provided to test the user’s knowledge.  This module can run on Google Cloud Platform (GCP) and python commands are used. Docking can be done using GUI mode command mode. Final docked structures are used using PyMol. 

## Learning Objectives
- Prepare the protein of interest for docking calculations. 
- Retrieve the protein and ligand structures from the protein data bank and prepare the structures for docking calculations.
- Perform protein-ligand docking calculations, analyze the docking results, and choose the most possible docking ligands in the order of binding affinity (docking energy) for drug design.
- Sketch a small molecule ligand and prepare the 3D structure of ligand drugs to dock to proteins.
- Perform protein-protein docking and analyze the interaction surface of two proteins.

## Key Tools and Datasets
- Visualization: `PyMOL`
- Docking: `AutoDock` & `ClusPRO`
- Protein Structure: `Protein Data Bank (PDB)`
- Binding Site Identification: `FTMAP`
- Drawing Molecular Structures: `e-DRUG3D`, `rdkit`

## Workflow
- PyMol and Autodock can be executed from within the notebook. 
- We will use a protein data bank to access 3D structures. 
- All the activities are done using PyMOL GUI, executing PyMOL commands, or writing, loading, and running PyMOL scripts. Instructions for all options are provided. 
- Most of the data preparations for docking can be done using Notebook. 
- Autogrid and Autodock are run on local machines and instructions are provided to set this up. 
- Similarly ClusPro is run on a server using login credentials.
 
## Data
- Coordinates of 3D structures of proteins and sequence of proteins are directly downloaded from the protein data bank (PDB) . 
- Output files for docking are provided for the users for analysis of docking results in the *data* directory.

## Troubleshooting
+ Make sure your notebook is running on a python kernel.
+ Make sure to run code cells in the order they are presented within the notebook.

## Funding
This resource was supported with funds from NIH grant P20 GM103424-21 

## License for Data
Text and materials are licensed under a Creative Commons CC-BY-NC-SA license. The license allows you to copy, remix and redistribute any of our publicly available materials, under the condition that you attribute the work (details in the license) and do not make profits from it. More information is available here.
