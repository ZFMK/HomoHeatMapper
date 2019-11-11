# HomoHeatMapper
 HomoHeatMapper: A perl script designed to generate heat maps from matrices of probabilities generate by Homo v2.0


## Notes regarding software

###Name        
HomoHeatMapper

###Version
1.0

###Copyright
Copyright © 2019 Bernhard Misof. All rights reserved.

###Warning
The copyright holder takes no legal responsibility for the correctness of 
results obtained using this program.

#Author
Bernhard Misof

#Address
Center for Molecular Biodiversity Research
Zoological Research Museum A. Koenig
Bonn, Germany

###Contact
b.misof@leibniz-zfmk.de

###Date
2 November 2019

###Purpose
HomoHeatMapper produces a heat map from a distance matrix with probabilities 
obtained using Homo v2.0 (https://github.com/lsjermiin/Homo.v2.0).
            
The smaller a probability is, the darker the corresponding pixel in the heat 
map is.
 
###Format
Probabilities must be saved in a text file with comma-separated values (.csv).

The first line must contain the number of samples being compared. 

Each of the following lines must start with a sample name, and then followed
by the probabilities, one for each comparison involving the named sample.
 
###Example
See file labelled 22_root_Pvalues.csv.

###Install
To install HomoHeatMapper.pl, type (in the command line):

            sudo cp HomoHeatMapper.pl /usr/local/bin/. 

###Exceute
            HomoHeatMapper -i <infile.csv> <-t|f>

###Help
            -t = triangular heat map; -f = square heat map

###Status
Software complete

###Note
Contact author for updates, etc

###ReferenceJ
ermiin LS, Lovell DR, Misof B, Foster PG, Robinson J. Software for detecting 
            heterogeneous evolutionary processes across aligned sequence data. Syst. Biol.
            (submitted)
