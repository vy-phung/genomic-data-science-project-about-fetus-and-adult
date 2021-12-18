## RNA-sequence re-analysis for developmental regulation of human cortex transcription between fetus and adult.
### Summary
I do this project in order to practice and understand deeply how to do genomic data science. 

The purpose of this re-analysis is to examine the correlation of differential gene expression between fetal and adult brains, which is evaluated through RNA-sequencing.
If it has correlation, then count how many up-regulated and down-regulated genes. All of this using R, RStudio. 

Moreover, I will use the genomic data including not statistically analyzed data, and already statistically analyzed data in order to predict and classify some characteristics of samples (gender, age). All of this using Python, Google Colab. 
### Links to access  
1. The article "developmental regulation of human cortex transcription between fetus and adult": http://www.ncbi.nlm.nih.gov/pmc/articles/PMC4281298/

2. The article's RNA-seq data: http://www.ebi.ac.uk/ena/data/view/PRJNA245228

3. The article's phenotype meta-data for the samples: http://www.ncbi.nlm.nih.gov/bioproject/?term=PRJNA245228

### Brief overview
1. Download RNA-seq data vs phenotype metadata (checking code book.docx for more details)
2. Using The Galaxy Project to do (checking code book.docx for more details):
- FASTQ Quality Control
- Alignment with HISAT2
- Get feature count from "featureCounts" in RNA-seq
- Get tidy data (count table)
3. Do exploratory analysis and statistical analysis in R
4. Predict and classify characteristics of samples in Python 

### Drawbacks:
- Using 10 samples, which means the sample size is too small to infer for the large population and can be biased

### Reference:
- Genomic Data Science Specialization audit courses
(https://www.coursera.org/specializations/genomic-data-science)
- https://github.com/friveramariani/GenomicDataScience_FetalAdultBrain.git
- https://github.com/jtleek/datasharing.git
- http://jtleek.com/genstats_site/
