# pStrain


#### Installation
pStrain has the following dependencies:

#### Required dependencies
 - kraken
 - Trimmomatic 
 - Samtools
 - BWA
 - BCFTOOLS
 - PICARD
 - ggtree 

There are a way to install pStrain and details are provided below. 
````
pip install pStrain
````
#### Running the tests
#### Usage
````
pStrain/process.py -s  -i list -n 4 -m ~133s_2298p.txt -r CO92.chr.fas -t 133strain_branch_type.list -o fina -g IP32953_outgroup
````
