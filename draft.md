## Prepare input files
To analyse with our packages you need to provide a set of input files, including the mutation information (MAF files), the analysis result of Pyclone(ccf files) as well as necessary information of samples(sampleID,patientID,lesion and time)
 
 Below are examples of the input file with information of your samples.
 
 |  ```sample```  |  patient |  lesion |  time  |
 | :------ | :------- | :------ | :------- |
 | 311252-S | 311252 |  S      |      -   |
 | 311252-V |  311252  |  V  |     -   |
 
 The Pyclone files:
 
| sample_id |	cluster_id | size | mean | std |
| :--------| :------ | :----- | :------ | :---|
| 311252-TP2-2	|  0  |	44 | 0.6889794185857827	| 0.04896247067312107 |
 
 | mutation_id	| sample_id |	cluster_id	| cellular_prevalence |	cellular_prevalence_std	| variant_allele_frequency |
 | :---- | :----- | :----- | :---- | :---- | :---- |
 | ABCB10:1:229678207 |	311252-TC1 | 2	| 0.4904968994179655 |	0.15225139438684998 |	0.0970873786407767 |
 
 
 
 
## Prepare input files
To analyse with our packages you need to provide a set of input files, including the mutation information (MAF files), the analysis result of Pyclone(ccf files) as well as necessary information of samples.
 Below are several examples of the input files.
 
#### Information of samples
 
 |  ```sample```  |  patient |  lesion |  time  |
 ---- | ------ | ------ | ------
 | 311252-S | 311252 |  S      |      -   |
 | 311252-V |  311252  |  V  |     -   |
 
#### The analysis result of Pyclone 
 
| sample_id |	cluster_id | size | mean | std |
| :--------| :------ | :----- | :------ | :---|
| 311252-TP2-2	|  0  |	44 | 0.6889794185857827	| 0.04896247067312107 |
 
 | mutation_id	| sample_id |	cluster_id	| cellular_prevalence |	cellular_prevalence_std	| variant_allele_frequency |
 | :---- | :----- | :----- | :---- | :---- | :---- |
 | ABCB10:1:229678207 |	311252-TC1 | 2	| 0.4904968994179655 |	0.15225139438684998 |	0.0970873786407767 |
 
#### The MAF file
| Hugo_Symbol|	Chromosome | Start_Position |	End_Position |	Variant_Classification | Variant_Type |	Reference_Allele |	Tumor_Seq_Allele1 | Tumor_Seq_Allele2 |	Ref_allele_depth |	Alt_allele_depth |	VAF	CDS_Change	| Protein_Change |	Tumor_Sample_Barcode |
|:-----| :------| :------ | :----- | :------ | :----- | :---- | :-----| :----- | :----- | :-------| :---- | :-----| :----- |
| LOC729737| 1 | 135207 |	135207	| RNA |	SNP |	C | C |	G |	40	| 4 | 0.0909 | NA |	NA | 311252-S