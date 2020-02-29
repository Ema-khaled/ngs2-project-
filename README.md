# ngs2-project-

we have 3 samples with that meta data information 
our samples.........Run............sample name...........age.......librarry name.......sex 
first sample......... SRR8241115........Proband II-1.... 40......HUMrmoXDTABAPEI-1...... male 
Shimaa_2nd sample.....SRR8241113....... Patient III-9... 32.......HUMrmoXDTABAPEI-11....male 
 Third sample........SRR8241116...... Patient III-3......23.......HUMrmoXDTABAPEI-10....femal 

Study Design:
1) Download row data from NCBI (SRA )
- In our study, we will download three samples from the prject .
2)  Download reference genome 
3) Quality control for raw data ( fastQC)  
4)  Alignment using BWA ( The output is bam file)
5) bam sorting and indexing using samtools 
6) Local realignment ( After indexing bam file and reference)
6)  Mark and remove duplicates 
7) Recalibrate Bases (BQSR)
7) Joint variant calling using 
8)  Variant filtering 


First sample done by Eman khaled ahmed ....(ID=191092)
2nd sample done by Shimaa Tawfeeq Abdallah Omara (ID=192060)
Third sample done by Yomna....(ID=...)


##for First sample  (EMAN )  
The first 158 line is the sequnece of my totorial with issues that i faced step by steb mainly untill the alignment step  
then the totorial witout any error to be radable .. 

## For Shimaa files, please reads the files in the following sequences:
1-Shimaa_2nd sample
2-Shimaa_fastqc_multiqc_report
3-Shimaa_statsSummaryFile
4-Shimaa_Sam
5-Shimaa_Bam
6-Issues met Shimaa are serially numbered from First to 8th 
