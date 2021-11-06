# RNA-seq re-analysis for developmental regulation of human cortex transcription between fetus and adult.
## Summary
In my personal genomic data science project, the differential gene expression between fetal and adult brains was evaluated in transcriptome sequencing data (known as RNA-seq) and then find out how many up-regulated and down-regulated genes in statistical analysis in R. In order to explore more if having the genomics data (in this case is a table called edata which each row is a gene and each column is a sample) can help to predict and classify some characteristics of samples (gender, age), I will use this genomics data (edata) and analyze it in Python. 
### Sites to access  
1. Find in this link the related publication: http://www.ncbi.nlm.nih.gov/pmc/articles/PMC4281298/

2. Find in this link the RNA-seq data: http://www.ebi.ac.uk/ena/data/view/PRJNA245228

3. Find in this link the phenotype meta-data for the samples: http://www.ncbi.nlm.nih.gov/bioproject/?term=PRJNA245228

### Brief overview
1. Download RNA-seq data vs phenotype metadata (checking code book.docx for more details)
2. Using The Galaxy Project to do (checking code book.docx for more details):
- FASTQ Quality Control
- Alignment with HISAT2
- Get feature count from "featureCounts" in RNA-seq
- Get tidy data (count table)
3. Do exploratory analysis and statistical analysis in R
4. Predict and classify characteristics of samples in Python 
