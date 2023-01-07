# Assignment 4

This assignment was made in collaboration with: Ana Karina Ballesteros Gómez, Ángela Gómez Sacristán, Mariam El Akal Chaji, Marta Fernández González and Paula Fernández Aldama. 

It consists in the following: 

Assignment: use of BLAST to  Discover putative Orthologues 

Orthologue DEFINITION:  Genes that are found in different species that evolved from a common ancestral gene by speciation.

A common first-step in discovery of Orthologues is to do a “reciprocal best BLAST”.  That is, you take protein X in Species A, and BLAST it against all proteins in Species B.  The top (significant!!) hit in Species B is then BLASTed against all proteins in Species A.  
If it’s top (significant) hit is the Protein X, then those two proteins are considered to be Orthologue candidates. (there is more work to do after this, but this is a good start)

Using BioRuby to blast and parse the blast reports, find the orthologue pairs between species Arabidopsis and S. pombe.  I have uploaded their complete proteomes to the Moodle for you.  You do not need to create objects for this task (the existing BioRuby objects are sufficient)

To decide on "sensible" BLAST parameters, do a bit of online reading - when you have decided what parameters to use, please cite the paper or website that provided the information.

# Running the code 

In the terminal type: ruby Main.rb pep_1.fa TAIR10_cds_20101214_updated_1.fa

With this you will generate the Report.txt as the resulting report for this assignment. 

# Other files

In the folder /doc/ it is contained the Yard documentation for the code. 
 

