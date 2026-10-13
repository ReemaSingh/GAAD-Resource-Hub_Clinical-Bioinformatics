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


### Pillar 2: Multi-Omics Databases & Repositories

Curated public datasets (genomics, transcriptomics, proteomics, and metabolomics) supporting accelerated target identification.

| Resource / Database | Data Type | Primary Application | Access Link |
| :--- | :--- | :--- | :--- |
| **Antimicrobial Resistance Portal (EMBL-EBI)** | Multi-Omics / AMR | Genotype-to-phenotype mapping and resistance data integration | [Access Portal](https://www.ebi.ac.uk/amr/) |
| **ABRomics Platform** | Multi-Omics / AMR | French national platform for AMR multi-omics data integration | [Access Portal](https://www.abromics.fr/home/abromics-platform/) |
| **CARD (Comprehensive Antibiotic Resistance Database)** | Resistance Genes | Rigorously curated database of resistance determinants and ARO ontology | [Data Hub](https://card.mcmaster.ca/) |
| **Omics Discovery Index (OmicsDI)** | Multi-Omics | Multi-omics dataset discovery across genomics, transcriptomics, proteomics, and metabolomics | [Search Portal](https://www.omicsdi.org/) |
| **BV-BRC (Bacterial and Viral Bioinformatics Resource Center)** | Genomics & Multi-Omics | Integrated bacterial and viral data analysis, pathways, and target discovery | [Resource Center](https://www.bv-brc.org/) |
| **NCBI AMR Resources** | Genomics / Isolate Data | Reference gene catalog, point mutations, and pathogen isolate surveillance | [NCBI Portal](https://www.ncbi.nlm.nih.gov/pathogens/antimicrobial-resistance/resources/) |
| **MetaboLights** | Metabolomics | Database for metabolomics experiments, raw data, and associated metadata | [EMBL-EBI Portal](https://www.ebi.ac.uk/metabolights/) |
| **PRIDE (PRoteomics IDEntifications Database)** | Proteomics | Standard public repository for mass spectrometry-based proteomics datasets | [EMBL-EBI Portal](https://www.ebi.ac.uk/pride/) |


### Pillar 3: AMR Discovery Protocols and Translational Frameworks

Guidelined for predictive leads, host-pathogen interaction modeling, and computational PK/PD integration.

| Protocol/Framework | Application | Target Audience | Reference / Resource |
| :--- | :--- | :---| :--- | 
|antiSMASH (Antibiotics & Secondary Metabolite Analysis SHell)|Identifies biosynthetic gene clusters (BGCs) in genome sequences to discover novel secondary metabolites.|Natural product chemists, genome miners, and drug discovery teams.|https://antismash.secondarymetabolites.org/#!/start|
|DeepAMR / DeepMicro|Employs deep learning architectures to predict minimum inhibitory concentrations (MIC) directly from sequence data.|Computational biologists and advanced pharmaceutical AI developers.|Peer-reviewed ML literature / GitHub repositories|
|CARD & RGI (Comprehensive Antibiotic Resistance Database)|Predicts resistomes from genomic data using a Detection Engine based on high-quality reference sequences.|Bioinformaticians, microbiologists, and clinical genomic researchers.|https://card.mcmaster.ca/|
|AMRFinderPlus|Locates acquired resistance genes, structural point mutations, virulence factors, and biocide biotypes.|Public health researchers and bacterial genomic epidemiologists|https://github.com/ncbi/amr|
|ResFinder & PointFinder|Identifies acquired AMR genes and specific chromosomal mutations from whole-genome sequencing (WGS) data.|Clinical microbiologists and epidemiological surveillance networks.|https://genepi.food.dtu.dk/resfinder|
|Target Pathogen Database|Links genomic data of priority pathogens to structural models to fast-track target identification and drug repurposing pipelines.|Structural biologists and computational drug design teams.||
|EUCAST & CLSI Breakpoint Frameworks|Sets standardized minimum inhibitory concentration (MIC) thresholds to classify a pathogen as susceptible or resistant.|Diagnostic laboratories, assay developers, and clinical trial designers.|https://www.eucast.org/|
|WHO Target Product Profiles (TPPs)|Outlines specific product criteria (spectrum, safety profile, dosing, price) required for priority pathogen therapeutics.|Biotech startups, academic spin-offs, and pharmaceutical R&D leads.|https://www.who.int/|
|NPL Antimicrobial Metrology Framework|Measures and validates physical mechanisms of action at single-cell levels to reduce preclinical replication failures.|Preclinical drug developers and biometrology scientists.|https://www.npl.co.uk/|
|CARB-X Funding & Mentorship Model|Provides non-dilutive financial push-incentives alongside technical guidance to accelerate early-stage AMR assets.|Early-stage biotechnology companies and academic researchers.|https://carb-x.org/|
|WHO AWaRe Classification|Categorizes antibiotics into Access, Watch, and Reserve groups to guide translation stewardship and restrict marketing.|National health ministries, hospital formulary committees, and clinicians.||
|SECURE Initiative|Ensures equitable access and sustainable stewardship lines for newly translated antibiotics in developing nations.|Public health policymakers, global access foundations, and GARDP.|https://gardp.org/
|Quadripartite One Health Joint Plan of Action|Harmonizes human, animal, and environmental data streams into a single cross-border AMR surveillance framework.|Environmental agencies, agricultural bodies, and public health officials.||
|Co-ADD Screening Protocols|Provides open-access, standardized high-throughput screening workflows for chemical compound libraries against priority pathogens.|Academic chemists and early-stage screening facilities.|https://www.co-add.org/|
|Bacterial Cytological Profiling (BCP)|Uses high-throughput fluorescence microscopy to rapidly identify the mechanism of action of new compounds by monitoring cell structural decay.|Phenotypic screening labs and mechanistic microbiologists.|Standardized university discovery protocols (e.g., UCSD BCP)|
|PBPK Modeling Frameworks for Antibiotics|Simulates physiologically based pharmacokinetics to predict antibiotic tissue distribution and target site concentration (e.g., lung epithelial lining fluid).|Clinical pharmacologists, PK/PD modelers, and regulatory specialists.|US FDA / EMA Translational Guidance Documents|
|nlmixr2 (R Package)|Fits population pharmacokinetic (PK) and pharmacokinetic-pharmacodynamic (PKPD) models using non-linear mixed effects (NLME) to simulate variability in patient drug exposure.|Pharmacometricians, clinical pharmacologists, and drug development leads.|https://github.com/nlmixrdevelopment/nlmixr|
|mrgsolve (R Package)|Simulates continuous time-course events from hierarchical, ordinary differential equation (ODE) based models, establishing exposure-response models for antibiotics.|Quantitative systems pharmacologists (QSP) and clinical trial simulation specialists.|https://mrgsolve.org/|
|PKPDindex (CRAN R Package)|Fits Emax, inhibitory I_max, and sigmoid models specifically to evaluate the exposure-response relationship between antibiotic serum concentration and bacterial killing metrics (e.g., fAUC/MIC).|Preclinical microbiologists, translational pharmacologists, and PK/PD index researchers.|https://cran.r-project.org/web/packages/pkpd.Release/index.html|
|Open Systems Pharmacology Suite (PK-Sim & MoBi)|Builds whole-body, Physiologically Based Pharmacokinetic (PBPK) models to predict antibiotic distribution into site-of-infection tissues (like lung epithelial lining fluid or bone tissue) before clinical data exists.|Translational drug developers, PK/PD modelers, and regulatory submission scientists.|https://www.open-systems-pharmacology.org/|
|Pumas (Julia Ecosystem)|Accelerates massive pharmaceutical simulations and deep-learning integrated NLME modeling via GPU parallelization, modeling complex dosing regimens and adaptive antibiotic therapies.|Advanced computational pharmacologists and clinical development biostatisticians.|https://pumas.ai/|
|PKSmart|Deploys machine learning algorithms utilizing molecular structural fingerprints and physicochemical properties to predict human pharmacokinetics from in silico data.|Medicinal chemists and early-stage drug discovery teams screening structural libraries.|https://srijitseal.com/PKSmart/|

## How to Contribute

We welcome contributions from academic and inductry collaborators! To suggest a tool, database, or protocol:

1. Open a new request under the **[Issues](../../issues)** tab.
2. Provide the resource name, category, brief description, and publication/source link.

## Contact and Governance

**Initiative Lead:** Dr. Reema Singh

**Organization:** Global Alliance for Antimicrobial Discovery Special Interest Group (GAAD SIG)
