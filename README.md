# GAAD SIG: Clinical-Bioinformatics Resource Hub

Welcome to the **Clinical-Bioinformatics Resource Hub**, an open-access initiative led by the Global Alliance for Antimicrobial Discovery Special Interest Group (GAAD SIG).

This directory bridges high-throughout computational discovery with clinical pharmacology, providing researchers and industry partners with verified workflows to advance antimicrobial target discovery.

## Hub Pillars

### Pillar 1: Open-Source Pipelines

Standarized computational workflows for genome assembly, functional annotation, variant calling, and mobile genetic element (MGE) mapping.

| Pipeline / Tool | Category | Key Capabilities / Description | Source / Reference | License |
| :--- | :--- | :--- | :--- | :--- |
| **CdMEC-A** | MGE & AMR Stratification | Automated spatial risk stratification and contextual analysis of MGEs in *C. difficile* | [GitHub Repo](https://github.com/reemasingh/CdMEC-A) | Open Source |
| **wf-bacterial-genomes** | Workflow / Assembly | EPI2ME workflow for bacterial genome assembly and analysis | [EPI2ME Docs](https://epi2me.nanoporetech.com/epi2me-docs/workflows/wf-bacterial-genomes/) | Open Source |
| **nf-core/bacass** | Bacterial Assembly | Nextflow pipeline for bacterial genome assembly | [nf-core Docs](https://nf-co.re/bacass/2.0.0/) | MIT |
| **nf-core/funcscan** | Functional Annotation | Nextflow pipeline for screening screening contigs for functional genes | [nf-core Docs](https://nf-co.re/funcscan/) | MIT |
| **rMAP 2.0** | Resistance Mapping | Rapid Mapping and Annotation Pipeline for bacterial genomes | [GitHub Repo](https://github.com/gmboowa/rMAP-2.0) | Open Source |
| **AMRFinderPlus** | AMR Identification | NCBI tool for identifying resistance genes and point mutations | [NCBI Portal](https://www.ncbi.nlm.nih.gov/pathogens/antimicrobial-resistance/AMRFinder/) | Public Domain |
| **RGI (Resistance Gene Identifier)** | AMR Annotation | CARD-based tool for predicting resistomes from nucleotide/protein sequences | [GitHub Repo](https://github.com/arpcard/rgi) | GPL-3.0 |
| **ResFinder** | AMR Identification | Identifies acquired antimicrobial resistance genes in total genomic sequence | [Genomic Epidemiology](https://www.genomicepidemiology.org/) | Open Source |
| **Bactopia** | High-Throughput WGS | Flexible pipeline for complete bacterial genomic analysis | [GitHub Repo](https://github.com/bactopia/bactopia) | MIT |
| **Nullarbor** | Public Health WGS | Pipeline for public health microbiology genomics | [GitHub Repo](https://github.com/tseemann/nullarbor) | GPL-3.0 |
| **Gen2Epi / Gen2EpiGUI** | Genomic Epidemiology | Workflow and GUI for translating genomic data to epidemiological metrics | [GitHub Repo](https://github.com/ReemaSingh/Gen2Epi) | Open Source |
| **ASA3P** | Automated Annotation | Automatic Scaffold Annotation and Analysis Pipeline | [GitHub Repo](https://github.com/IFO-MOC/ASA3P) | Open Source |
| **dragonflye / shovill** | Genome Assembly | Assemblers optimized for Nanopore (dragonflye) and Illumina (shovill) reads | [GitHub Repo](https://github.com/tseemann/shovill) | GPL-3.0 |
| **staphopia-sccmec** | Typing & Profiling | MGE typing and pathogen profiling frameworks | [GitHub Repo](https://github.com/staphopia/staphopia-sccmec) | MIT |

### Pillar 2: Multi-Omics Databases and Repositories

Curated public datasets (genomics, transcriptomics, proteomics, and metabolomics) supporting accerelerated target identification.

| Resource/Database | Data Type | Primary Application | Access Link |
| :--- | :--- | :---| :--- | 
|**The Antimicrobial Resistance Portal (EMBL-EBI)**|Genotype-to-Phenotype Coordination||https://www.ebi.ac.uk/amr/|Open Source|
|**ABRomics Platform**|||https://www.abromics.fr/home/abromics-platform/|Open Source|
|**CARD: Comprehensive Antibiotic Resistance Database**|||https://card.mcmaster.ca/|Open Source|
|**Omics Discovery Index (OmicsDI)**|||https://www.omicsdi.org/|Open Source|
|**BV-BRC (Bacterial and Viral Bioinformatics Resource Center)**|||https://www.bv-brc.org/|Open Source|


### Pillar 3: AMR Discovery Protocols and Translational Frameworks

Guidelined for predictive leads, host-pathogen interaction modeling, and computational PK/PD integration.

| Protocol/Framework | Application | Target Audience | Reference / Resource |
| :--- | :--- | :---| :--- | 

## How to Contribute

We welcome contributions from academic and inductry collaborators! To suggest a tool, database, or protocol:

1. Open a new request under the **[Issues](../../issues)** tab.
2. Provide the resource name, category, brief description, and publication/source link.

## Contact and Governance

**Initiative Lead:** Dr. Reema Singh

**Organization:** Global Alliance for Antimicrobial Discovery Special Interest Group (GAAD SIG)
