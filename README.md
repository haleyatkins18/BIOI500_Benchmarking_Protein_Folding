# BIOI500_Benchmarking_Protein_Folding

## Benchmarking Project for protein folding in BIOI 500. Benchmarked the tools: AlphaFold, ESMFold, and SWISS-MODEL. AlphaFold web server, ESMFold API, and SWISS-MODEL web server. 


## Steps for running AlphaFold on web server:
https://deepmind.google/technologies/alphafold/alphafold-server/
  - login with a Google email
  - Input: FASTA file/PDB file/ FASTA sequence
  - Output: 5 models (0-4)
    -   1 *.json/ model
    -   1 *.cif file/ model
    -   1 confidences file/ model
   
## Steps for running ESMFold API  
https://esmatlas.com/resources?action=fold 
  - Input: FASTA format sequence
  - Output: Predicted structure with downloadable .pdb file


## Steps for running SWISS-MODEL
https://swissmodel.expasy.org/ 
  - start modelling
  - Input: FASTA file/FASTA sequence
  - Output: predicted structures
      - Sequence identity
      - Template
      - GMQE
      - QMEANDisCo Global
      - Oligo-state
   



