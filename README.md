## RNA-sequence re-analysis for the correlation of differential gene expression between fetal and adult brains
### Summary:
I do this project in order to practice and understand deeply how to do genomic data science. <br> You can see its webpage <a href="https://vy-phung.github.io/vyphung/summary.html">here</a>

I get the data at the link below to re-analyze. The purpose of this re-analysis is to examine the correlation of differential gene expression between fetal and adult brains, which is evaluated through RNA-sequencing.
If it has correlation, then count how many up-regulated and down-regulated genes. All of them are done in R, RStudio. 

Moreover, I will use the genomic dataset (already statistically analyzed data) in order to predict and classify some characteristics of samples (gender, age). All of them are done in Python, Google Colab. 
### Links to access the data source:  
1. The article "Developmental regulation of human cortex transcription and its clinical relevance at base resolution":<br> http://www.ncbi.nlm.nih.gov/pmc/articles/PMC4281298/

2. The article's RNA-seq data: <br> http://www.ebi.ac.uk/ena/data/view/PRJNA245228

3. The article's phenotype meta-data for the samples: <br> http://www.ncbi.nlm.nih.gov/bioproject/?term=PRJNA245228

### Brief overview:
1. Download RNA-seq data vs phenotype metadata (checking code book.docx for more details)
2. Use The Galaxy Project to do (checking code book.docx for more details):
- FASTQ Quality Control
- Alignment with HISAT2
- Get feature count from "featureCounts" in RNA-seq
- Get tidy data (count table)
3. Do exploratory analysis and statistical analysis in R
4. Predict and classify characteristics of samples in Python 

### Drawback:
- Use 10 samples, which means the sample size is too small to infer for the large population and can be biased

### Reference:
- Genomic Data Science Specialization audit courses <br>
(https://www.coursera.org/specializations/genomic-data-science)
- https://github.com/friveramariani/GenomicDataScience_FetalAdultBrain.git
- https://github.com/jtleek/datasharing.git
- http://jtleek.com/genstats_site/
