# r-syst::plants
Curated repository of releases of r-syst reference database for plants (fasta files, character files)  


## Projects

The projects are 
* molecular atlas of trees in French Guiana

## Types of files

The datasets of each project are available as three files:
* a fasta file (with suffic .fas)
* a character file (with suffix .char)
* a pairiwse distance matrix (as an array) between sequences (with suffix .dissw)   


For each specimen, the character file is an exel file with tab as separators within a row. Each column corresponds to a taxonomic rank
* Order
* Family
* Genus
* Species

The cell _(i,j)_ of distance file contains the distance between sequences _i_ and _j_ computed from the score or pairwise local alignement (Smith-Waterman algorithm).


## Molecular atlas of trees in French Guiana

Collaborators: Henri Caron, Philippe Chaumeil, Alain Franc (contact), Jean-Marc Frigerio, Jean-François Molino, Rémy Petit, Daniel Sabatier, Ivan Scotti, Caroline Scotti-Saintagne  
contact: alain.franc@inra.fr

Reference: Caron & al. (under review)

Three files can be downloaded 

* French_Guiana_Trees_trnH.fas: fasta file of sequences of marker trnH 
* French_Guiana_Trees_trnH.char: character file of same samples
* French_Guiana_Trees_trnH.dissw: distance file of same samples




