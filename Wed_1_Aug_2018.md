Download and test: [guide](https://software.broadinstitute.org/gatk/documentation/article.php?id=2899)   
Software packages.   
BWA call it by indicate its full path (/Users/shuanglu/Documents/bwa-0.7.17/bwa)    
SAMtools    
apro13-36hv29:samtools-1.9 shuanglu$ ./configure   
apro13-36hv29:samtools-1.9 shuanglu$ make   
test in terminal:
/Users/shuanglu/Documents/samtools-1.9/samtools   
Picard.   
shuanglu$ cd    
shuanglu$ java -jar /Users/shuanglu/Documents/picard.jar   
Genome Analysis Toolkit (GATK).   
IGV.   
RStudio IDE and R libraries ggplot2 and gsalib.    
When try to install r package into R but fault report: tar: Failed to set default locale' error?    
Step 1 (In R Console)   
system('defaults write org.R-project.R force.LANG en_US.UTF-8')   
Step 2: Restart R
