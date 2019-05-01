# #Genome-Sequencing

A python based Gene sequence detector in a given Fasta file containing a sequence genes.

A Python GUI is developed using Tkinter which provides facility to the user to upload a Fasta file </br>
In this project EcoliGeneSequences.txt is the file taken </br>
If it is not a Fasta file then it displays the message as "Not a Fasta file!!".</br>
Else it further checks for the all other requirements for the Fasta file </br>

# Requirements for a file to be a Fasta file::
a) The information line starts with a ‘>’ symbol only. </br>
b) The information is contained in one single line and is not continued to the next line. </br>
c) There is no blank line between information line and gene sequence. </br>
d) The gene sequence contains only 4 characters ‘A’, ‘T’, ‘G’ and ‘C’.</br>

If the file is a Fasta file then all the information from the file are stored in the database by comparing the locations with another file named "GeneDetails.txt".

# Output Screenshots::

Tkinter GUI:
![1](https://user-images.githubusercontent.com/47445363/57035600-14a4ea80-6c70-11e9-98fe-fbff411c4c12.png)

Database Content:
![2](https://user-images.githubusercontent.com/47445363/57035601-153d8100-6c70-11e9-9926-97e6c14d02f0.png)
