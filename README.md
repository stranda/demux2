# demux2
shell script to demultiplex paired end barcodes in illumina data

VERSION: 0.0.1
DATE: 1/20/2020

This folder should include:

  + README (this file)
  + demux2 (shell script that works the whole thing)
  + test_barcode.csv (example barcode-id map)
  + test_R1.fastq.gz test_R2.fastq.gz (example reads)


# This set of codes demultiplexes illumina reads with inline barcodes

To run the analysis for exact matches you just need to run this command:

./demux2 test_R1.fastq.gz test_R2.fastq.gz test_barcode.csv

You should get a new directory installed in this folder called "fastq" containing the compressed demultiplexed reads.

