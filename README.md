# Loop
How to take HiC data and make bedpe files for loops (visualize in IGV)

#What is the Plan? 
We have the paired end demultiplexed reads post bcl2fastq 
Now we need to take this Sample1_R1_fastq.gz and Sample2_R2_fastq.gz and go through a pipeline to get bedpe files. 
#Why am I doing this? 
I have .hic files that I generated through juicer but I seem to can't use HiCCUPS because I work on a CPU and do not have CUDA and it has been a pain till now. So let's prepare a pipeline where I take fastq.gz files, align it, take the bam/sam file and generate a bedpe file. 

Let's see how it goes
