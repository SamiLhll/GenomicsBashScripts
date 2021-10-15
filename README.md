# SamiGenomicsBashScripts
A collection of custom-made bash scripts to make my Genomics data analyses easily reproducible 

# MacroSynteny

### Generate_MBH_table :

-------------------------------------------------------
generate blastp MBH (proteins only!) - usage :   
-a path to the first specie proteins dataset (FASTA)   
-b path to the second specie proteins dataset (FASTA)   
-n name to give to the resulting table   
-t number of threads to dedicate to the blast jobs   
-h prints this message and exit   

The output is a tab delimited file formatted as follow :   
proteinID_specie_a  proteinID_specie_b
...

-------------------------------------------------------
