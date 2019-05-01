# #Genome-Sequencing

A python based Gene sequence detector in a given Fasta file containing a sequence genes.

A Python GUI is developed using Tykinter which provides facility to the user to upload a Fasta file.
In this project EcoliGeneSequences.txt is the file taken.
If it is not a Fasta file then it displays the message as "Not a Fasta file!!".
Else it further checks for the all other requirements for the Fasta file.

# Requirements for a file to be a Fasta file::
a)	The information line starts with a ‘>’ symbol only.
b)	The information is contained in one single line and is not continued to the next line.
c)	There is no blank line between information line and gene sequence.
d)	The gene sequence contains only 4 characters ‘A’, ‘T’, ‘G’ and ‘C’.

If the file is a Fasta file then all the information from the file are stored in the database by comparing the information with another file named "GeneDetails.txt".
