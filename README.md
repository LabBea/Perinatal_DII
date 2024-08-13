---
date: 2024-02-20
output: html_document
title: Perinatal DII
---

# R Scripts and Data for "Inflammatory dietary potential is associated with vitamin de-pletion and gut microbial dysbiosis in early pregnancy"

------------------------------------------------------------------------

This repository contains the R scripts and raw data included in the work
"Inflammatory dietary potential is associated with vitamin de-pletion
and gut microbial dysbiosis in early pregnancy" by Alvernaz et al 2024.
The full publication can be found
[here](https://www.mdpi.com/2072-6643/16/7/935). In this study, 47
pregnant persons completed an early pregnancy food frequency
questionnaire (Vioscreen or DHQII) and provided a stool sample for 16s
Amplicon sequencing. The information provided in this repository are as
follows


## Data

------------------------------------------------------------------------

There are four data files included in this upload.\
- **DHQII_Raw.xlsx** - This contains the raw DHQII data from 24
participants\
- **Vioscreen_RAW.xlsx** - This contains the raw Vioscreen from 25
participants\
- **FFQdate_ID.xlsx** - This contains the FFQ dates as well as matching
IDs for the DHQII participants\
- **Metadata_Mapfile** - This file has the mapfile information for the
fastq files as well as all of the cleaned metadata. Note the ages have
been deidentified to an age range. The raw fastq files will be uploaded
to the NCBI SRA database. The SampleID column in this file matches to
the file names for the raw fastq files


## Scripts

------------------------------------------------------------------------

There are three reference R scripts provided in this repository\
- **Diet_DHQII/Vioscreen** - Processing of the raw data and how the DII
scores were calculated\
- **DADA2_to_Phyloseq** - Taking the raw fastq files through the
processing and cleaning to final count tables stored a phyloseq object\
- **Mat_Diet_Microbiome** - Statistical analysis of the microbiome data
and DII scores. All figures for the manuscript were generated in this
file


## Questions

------------------------------------------------------------------------

Please contact Dr. Peñalver Bernabé at the University of Illinois
Chicago for questions about data availability.
