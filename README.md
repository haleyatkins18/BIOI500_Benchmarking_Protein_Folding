# BIOI500_Benchmarking_Protein_Folding

## Benchmarking Project for protein folding in BIOI 500. Benchmarked the tools: AlphaFold, ESMFold, and SWISS-MODEL. AlphaFold web server, ESMFold API, and SWISS-MODEL web server. 


## Running AlphaFold on web server:
https://deepmind.google/technologies/alphafold/alphafold-server/
  - login with a Google email
  - Input: FASTA file/PDB file/ FASTA sequence
  - Output: 5 models (0-4)
    -   1 *.json/ model
    -   1 *.cif file/ model
    -   1 confidences file/ model
   
## Running ESMFold API  
https://esmatlas.com/resources?action=fold 
  - Input: FASTA format sequence
  - Output: Predicted structure with downloadable .pdb file


## Running SWISS-MODEL
https://swissmodel.expasy.org/ 
  - start modelling
  - Input: FASTA file/FASTA sequence
  - Output: predicted structures
      - Sequence identity
      - Template
      - GMQE
      - QMEANDisCo Global
      - Oligo-state

## Pymol Commands (Educational Version)
- open predicted protein structure in Pymol
- fetch {experimental protein PDB code}
- as cartoon, all
- align predicted structure, experimental structure
- Output:
  - aligned protein structures
  - RMSD calculations

## Citations 
1. Jumper, J., Evans, R., Pritzel, A. et al. Highly accurate protein structure prediction with AlphaFold. Nature 596, 583–589 (2021). https://doi.org/10.1038/s41586-021-03819-2
2. Zeming Lin et al. ,Evolutionary-scale prediction of atomic-level protein structure with a language model.Science379,1123-1130(2023).DOI:10.1126/science.ade2574
3. Waterhouse A, Bertoni M, Bienert S, Studer G, Tauriello G, Gumienny R, Heer FT, de Beer TAP, Rempfer C, Bordoli L, Lepore R, Schwede T. SWISS-MODEL: homology modelling of protein structures and complexes. Nucleic Acids Res 46, W296-W303. (2018)
4. The PyMOL Molecular Graphics System, Version 3.0 Schrödinger, LLC.

   



