#Recommended run sequence  

##FASTQ qc, Alignment inc qc  
trim_qc.pbs
aligntophat_rna_50bp.pbs

##Quantification  
featureCounts.pbs 
