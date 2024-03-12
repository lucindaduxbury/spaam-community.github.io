---
layout: page
title: Glossary of ancient metagenomics acronyms
sidebar_link: false
---

I hate acronyms. Here is a list of them. DO NOT USE THEM. Please write them out in full so my acronym-dyslexic brain can cope. Thanks. 

## Programs/tools
| Acronym   | Actual name          | Short description     | Uniform Resource Locator (URL)       |
|----------:|:--------------------:|:---------------------:|:------------------------------------:|
|metaDMG   | Metagenomics DaMaGe  | Estimation, quantification and visualization of postmortem damage of single reads, single genomes and metagenomic environmental DNA | [GitHub](https://github.com/metaDMG-dev/metaDMG-cpp) |
|MALT      | Megan ALignment Tool | High-throughput Metagenomic BLAST-like alignment tool | [Website](https://software-ab.cs.uni-tuebingen.de/download/malt/welcome.html) |
|HOPS      | Heuristic Operations for Pathogen Screening | Tool for the authentication of ancient DNA | [GitHub](https://github.com/rhuebler/HOPS) |
|PyDamage  | Python Damage        | Estimates DNA damage for de novo-assembled contigs | [GitHub](https://github.com/maxibor/pydamage) |
|Fastp | `.fastq` Preprocessor | | [Paper](https://doi.org/10.1093/bioinformatics/bty560), [GitHub](https://github.com/OpenGene/fastp) |
|FastQC  | Fast Quality Control |
|MultiQC | | 
|Metahit
|MEGAN
|bwa aln
|bwa mem
|bowtie
|filterBAM/bam-filter
|AMDirt
|BEAST
|GTDB-Tk | Genome Taxonomy Database Toolkit | provides objective taxonomic assignments for bacterial and archaeal genomes based on the GTDB | [Paper](https://academic.oup.com/bioinformatics/article/36/6/1925/5626182?login=false) |
| Kraken

## Pipelines
| Acronym   | Actual name          | Short description     | Uniform Resource Locator (URL) |
|----------:|:--------------------:|:---------------------:|:-------------------------------|
|nf-core | |A community effort to collect a curated set of analysis pipelines built using Nextflow. | [Website](https://nf-co.re/) |
|nf-core/eager |Efficient Ancient GEnome Reconstruction |A scalable and reproducible bioinformatics best-practise processing pipeline for genomic NGS sequencing data, with a focus on ancient DNA (aDNA) data. It is ideal for the (palaeo)genomic analysis of humans, animals, plants, microbes and even microbiomes. |[Website](https://nf-co.re/eager/2.5.0) |
|nf-core/mag | see MAG |For metagenome assembly, binning and taxonomic classification | [Website](https://nf-co.re/mag/) |
|HOPS | Heuristic Operations for Pathogen Screening | Automated bacterial screening pipeline for ancient DNA sequences that provides detailed information on species identification and authenticity. | [GitHub](https://github.com/rhuebler/HOPS) |


## Databases
| Acronym   | Actual name          | Short description     | Uniform Resource Locator (URL) |
|----------:|:--------------------:|:---------------------:|:-------------------------------|
|GenBank | |NIH genetic sequence database, an annotated collection of all publicly available DNA sequences | [NIH](https://www.ncbi.nlm.nih.gov/genbank/) |
|BUSCO |Benchmarking Universal Single-Copy Orthologs |Provides measures for quantitative assessment of genome assembly, gene set, and transcriptome completeness based on evolutionarily informed expectations of gene content from near-universal single-copy orthologs. | [BUSCO](https://busco.ezlab.org/) |

|GUNC | the Genome UNClutterer | A tool that accurately detects and quantifies genome chimerism based on the lineage homogeneity of individual contigs using a genome’s full complement of genes.  |[Paper](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-021-02393-0) |
|NCBI
|HOMD
|GTDB
|Silva SSU 
|PR2 | Protist Ribosomal Reference | Three interconnected 18S rRNA databases, particularly useful for metabarcoding | [Website](https://pr2-database.org/)


## File formats
| File Extension   | Actual name          | Short description     |
|----------:|:--------------------:|:---------------------:|
|`.fastq`/`.fq` | FastQ |  
|`.fasta` |
|`.bam`/`.sam`/`.cram` | Binary Alignment Map or Sequence Alignment Map or Compressed Reference-oriented Alignment Map | files contain sequenced reads mapped to a reference |
|`.bai` | BAM index file | Index file that often accompanies a `.bam` |

## Misc
| Acronym   | Actual name          | Short description     |
|----------:|:--------------------:|:---------------------:|
|SPAAM | Standards, Precautions, and Advances in Ancient Metagenomics | An international and open community of ancient metagenomics researchers. |
|MAG/SMAG | Metagenome Assembled Genome or ? | Microbial genomes reconstructed from metagenomic data |
|USER or UDG | 
|IGV |
|sedaDNA | Sedimentary ancient DNA | Ancient DNA retrieved from sediment samples |  |
|aeDNA | ancient environmental DNA | Umbrella term for ancient DNA retrieved from the environment including sediment and water. Doesn't include DNA from a deceased organism specimen | |
|eDNA | environmental DNA | Umbrella term for DNA retrieved from the environment including sediment, water or air.
|SNP | Single Nucleotide Polymorphism | | |
|ANI | Average Nucleotide Identity | The average percentage of shared nucleotides between two genomes | [Paper](https://doi.org/10.1073/pnas.0409727102) |
|NGS | Next-generation sequencing |
