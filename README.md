# qiime2_amplicon_cleanup
## Test 1
### Test 2
reg text


## Purpose: 
To make pipeline for SSU & 16S amplicon sequencing cleanup and taxonomic identification

## Step 1: Prepare Files & Environment
### Using local drive
Make sure sequences are downloaded in an accessible location on the local drive.


<ins>Download Qiime2 on local drive</ins>
```
Need code for this
```

Activate Qiime2 in terminal command line
```
conda activate /Users/yo/miniconda/envs/qiime2-amplicon-2024.10
```

Set working directory along the path to where the directory where the sequences are stored

For example, if your sequences are found in /home/project/sequences, set your working directory to /home/project
```
cd /path/to/working/directory
```



### Using HPC

Upload all fastq.gz files onto HPC
```
scp -r "path/to/folder" \ 
user@koa.its.hawaii.edu:/home/user/path/to/directory/for/files
```

Installing Qiime2 on HPC 
