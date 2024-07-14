# Molecular-Docking-Demo

This project was intended for Computational Biology Final Project and aims to simulate the interaction between a ligand (Baicalin) and a receptor (NS2B-NS3) using molecular docking techniques. Molecular docking helps predict the preferred orientation of one molecule to another when bound to each other to form a stable complex.

## Workflow 
1. Install necessary libraries and tools using conda and pip. Tools include MGLTools, OpenBabel, RDKit, AutoDock Vina, py3Dmol, PDBFixer, and OpenMM.
2. Download ligand (baicalin.pdb) and receptor (NS2B-NS3.pdb) files.
3. Use PDBFixer to fix any issues with the receptor PDB file and sanitize the ligand PDB file to MOL2 format using OpenBabel and RDKit.
4. Prepare the receptor and ligand files for docking using MGLTools.
5. Create a configuration file (conf.txt) specifying the receptor, ligand, output file, and grid box parameters (center coordinates and size).
6. Execute AutoDock Vina to perform the docking simulation using the configuration file.




