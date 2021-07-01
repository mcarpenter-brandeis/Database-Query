# Sample-Query-Database

#Author: Meredith Carpenter

#Goal: Query online database for genetic analysis
#Inputs: Target gene - MC1R
#Outputs: mc1r.fasta, mc1r_homology_list.txt
#Additional deliverable: assign4.py (python code) and readme.txt

##STEP 1: Use the mygene database restful api endpoint to get the ensamble id for the MC1R gene (human species)

##STEP 2: Use the ensembl database endpoints to grab the nucleotide seqeunce data for MC1R
##Generate mc1r.fasta file containing the nucleotide seqeunce for MC1R.
##Find the longest open reading frame (ORF)
##Convert the longest open reading frame to amino acid sequence with biopython (from Bio.Seq import Seq)
##Write amino acid sequence to mc1r.fasta

##STEP 3: Determine what other species have genes that are homolgous to MC1R.
##Write the full unique list of species to mc1r_homology_list.txt

##To execute:
##python3 assign4.py
