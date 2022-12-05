# pStrain


#### Installation
pStrain has the following dependencies:

#### Required dependencies
 - Kraken 2.0.9-beta
 - Trimmomatic 0.39
 - Samtools 1.9 
 - BWA 0.7.12-r1039
 - BCFTOOLS 1.9 
 - PICARD
 - ggtree 2.0.4
 - ggplot2 3.3.1


There are a way to install pStrain and details are provided below. 
````
pip install pStrain
````
#### Running the tests
#### Usage
````
pStrain/process.py -s  -i list -n 4 -m ~133s_2298p.txt -r CO92.chr.fas -t 133strain_branch_type.list -o fina -g IP32953_outgroup
````
