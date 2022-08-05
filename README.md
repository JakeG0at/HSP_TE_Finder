# HSP_TE_Finder
Python Pipeline to explore TE insertion in the proximal promoter region of HSP genes

1.)Import and Parse Annotated GFF File for Genome
    Identify Number of HSP proteins
    Create filtered Datasets for negative and Positive Strand
    Calculate the intergenic position range for each protein
    
2.)Perform a local Blast for each Gene 
    Inputs include:
                  {Chromosome Fasta Sequence},
                  {Start and Stop Position of Intergenic Region},
                  {Output File name and location}
                  
3.)Run Repeat Masker on Intersequence fasta files
    Inputs include:
                  {TE Library fasta Sequence for Species},
                  {Intergenic Sequence Fasta Files}
