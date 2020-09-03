list984.txt: a list of PDB-ids of 984 high-resolution protein structures used in sbNMA computations. The list is sorted by the sizes of the structures (numbers of residues).

pdbsAndpsfs: this folder contains 7 zip files. The 7 zip files contain the autopsf-generated pdb and psf files of all the structures in list984.txt. These pdb and psf files are used in sbNMA computations. 

sbNMAmagnitudesOfVibrations.zip: this zip file contains the magnitudes of thermal vibrations computed from sbNMA (at 100 K) of all the structures in list984.txt. For each PDB-id in list984.txt, there is a (PDB-id).sbNMA file that contains the magnitudes of thermal vibrations of individual atoms, listed in the same order as atoms are listed in the corresponding autopsf-generated pdb file. The .sbNMA files are stored in sbNMAmagnitudesOfVibrations.zip.

The entire sbNMA code is available at:
https://github.com/htna/sbNMA-Matlab
