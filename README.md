# Bioinformatica

[![Book Badge](https://img.shields.io/badge/BOOKS-8A2BE2)](#books) [![Pipelines Badge](https://img.shields.io/badge/PIPELINES-8A2BE2)](#pipelines) [![Databases Badge](https://img.shields.io/badge/DATABASES-8A2BE2)](#databases) [![Tutorials Badge](https://img.shields.io/badge/TUTORIALS-8A2BE2)](#tutorials) [![Resources Badge](https://img.shields.io/badge/RESOURCES-8A2BE2)](#resources) [![Courses Badge](https://img.shields.io/badge/COURSES-8A2BE2)](#courses) [![Tools Badge](https://img.shields.io/badge/TOOLS-8A2BE2)](#tools) [![Techniques Badge](https://img.shields.io/badge/TECHNIQUES-8A2BE2)](#techniques) [![Algorithms Badge](https://img.shields.io/badge/ALGORITHMS-8A2BE2)](#algorithms)

## Table of contents
- [Bioinformatica](#bioinformatica)
  - [Table of contents](#table-of-contents)
- [Top Bioinformatics Journals](#top-bioinformatics-journals)
- [Resources](#resources)
  - [Databases](#databases)
  - [Web Resources](#web-resources)
- [Tools](#tools)
  - [Programming](#programming)
    - [Languages](#languages)
    - [Environment and Package Management](#environment-and-package-management)
  - [Data Tools](#data-tools)
    - [Downloading](#downloading)
    - [Compressing](#compressing)
  - [Sequence and Alignment](#sequence-and-alignment)
  - [Single-Cell and Spatial Omics](#single-cell-and-spatial-omics)
  - [Structural Biology and Molecular Modeling](#structural-biology-and-molecular-modeling)
- [Techniques](#techniques)
  - [Data Processing](#data-processing)
    - [Bioinformatics One-liners](#bioinformatics-one-liners)
  - [Command Line Operations](#command-line-operations)
  - [Disease Databases](#disease-databases)
  - [Interaction Databases](#interaction-databases)
- [Books](#books)
- [Pipelines](#pipelines)
- [Algorithms](#algorithms)
  - [Basics](#basics)
- [Tutorials](#tutorials)
- [Courses](#courses)

# Top Bioinformatics Journals
> A curated list of top bioinformatics and computational biology journals

1. [Nature Methods](https://www.nature.com/nmeth/) | Impact Factor - 36.1 | Premier journal for novel computational and experimental methods across the life sciences
2. [Nature Biotechnology](https://www.nature.com/nbt/) | Impact Factor - 33.1 | High-impact computational biology, genome engineering, and biotechnology advances
3. [Nucleic Acids Research](https://academic.oup.com/nar) | Impact Factor - 15.0 | Flagship molecular biology journal, home of the annual Database and Web Server issues
4. [Genome Biology](https://genomebiology.biomedcentral.com/) | Impact Factor - 12.3 | High-impact open-access genomics, computational methods, and biological insights
5. [Briefings in Bioinformatics](https://academic.oup.com/bib) | Impact Factor - 7.3 | Comprehensive reviews and critical evaluations of bioinformatics tools and databases
6. [Genomics, Proteomics & Bioinformatics](https://academic.oup.com/gpb) | Impact Factor - 7.2 | Official journal of the Beijing Institute of Genomics (CAS), published by Oxford Academic
7. [GigaScience](https://academic.oup.com/gigascience) | Impact Factor - 7.2 | Open-access journal dedicated to big data, reproducibility, and workflow sharing
8. [Bioinformatics](https://academic.oup.com/bioinformatics) | Impact Factor - 5.5 | Leading specialized journal for computational algorithms and software in biology (ISCB affiliated)
9. [PLOS Computational Biology](https://journals.plos.org/ploscompbiol/) | Impact Factor - 3.7 | Official open-access journal of the International Society for Computational Biology (ISCB)
10. [Database: The Journal of Biological Databases and Curation](https://academic.oup.com/database) | Impact Factor - 3.4 | Dedicated to the design, curation, and utility of biological data resources
11. [BMC Bioinformatics](https://bmcbioinformatics.biomedcentral.com/) | Impact Factor - 3.0 | Widely referenced open-access journal for computational biology tools and pipelines
12. [Bioinformatics Advances](https://academic.oup.com/bioinformaticsadvances) | Open Access | Gold open-access journal published by Oxford University Press in partnership with ISCB

> Additional Resources
1. [bioRxiv Bioinformatics](https://www.biorxiv.org/collection/bioinformatics) | Preprints in bioinformatics and computational biology
2. [F1000Research Bioinformatics Gateway](https://f1000research.com/gateways/bioinformatics) | Rapid open research publishing including Bioconductor and Galaxy channels

# Resources

## Databases
> Core primary and secondary biological repositories

1. [NCBI (National Center for Biotechnology Information)](https://www.ncbi.nlm.nih.gov/) | Central US repository for biomedical data including GenBank, RefSeq, PubMed, and BLAST
2. [Ensembl](https://www.ensembl.org/) | Comprehensive vertebrate genome browser with integrated gene annotations, comparative genomics, and BioMart
3. [UniProt](https://www.uniprot.org/) | Universal Protein Resource providing high-quality, manually curated (Swiss-Prot) and computationally analyzed (TrEMBL) protein sequence and functional records
4. [RCSB PDB (Protein Data Bank)](https://www.rcsb.org/) | Archive of 3D experimental structures of proteins, nucleic acids, and complex biological assemblies
5. [AlphaFold Protein Structure Database](https://alphafold.ebi.ac.uk/) | EMBL-EBI open database with over 200 million predicted protein structures modeled by AlphaFold
6. [GEO (Gene Expression Omnibus)](https://www.ncbi.nlm.nih.gov/geo/) | High-throughput functional genomics repository supporting microarray, RNA-seq, and single-cell datasets
7. [SRA (Sequence Read Archive)](https://www.ncbi.nlm.nih.gov/sra) | The world's largest repository for raw next-generation high-throughput sequencing data
8. [ENA (European Nucleotide Archive)](https://www.ebi.ac.uk/ena/browser/home) | European comprehensive record of nucleotide sequencing information spanning raw reads, assemblies, and annotations
9. [UCSC Genome Browser](https://genome.ucsc.edu/) | Interactive visual browser and download portal for vertebrate genome assemblies and annotation tracks
10. [GTEx Portal](https://gtexportal.org/) | Genotype-Tissue Expression project cataloging human tissue-specific gene expression and eQTL regulation
11. [GDC (Genomic Data Commons / TCGA)](https://portal.gdc.cancer.gov/) | NCI unified data system providing harmonized clinical and molecular cancer genomics data across TCGA and TARGET
12. [CELLxGENE](https://cellxgene.cziscience.com/) | Interactive explorer and standardized repository of millions of single-cell transcriptomics profiles curated by CZI

## Web Resources
> Online interactive analysis platforms, servers, and community portals

1. [Biostars](https://www.biostars.org/) | Leading global Q&A community for computational biology, sequencing analysis, and bioinformatics workflows
2. [Galaxy Project](https://usegalaxy.org/) | Open, web-based platform for reproducible, code-free bioinformatics data analysis with thousands of accessible tools
3. [NCBI BLAST](https://blast.ncbi.nlm.nih.gov/Blast.cgi) | Web interface to find regions of similarity between biological sequences against GenBank and RefSeq
4. [cBioPortal](https://www.cbioportal.org/) | Open-access web resource for visual exploration of multidimensional cancer genomics data
5. [ExPASy](https://www.expasy.org/) | Swiss Institute of Bioinformatics resource portal providing tools across proteomics, genomics, and structural biology
6. [STRING](https://string-db.org/) | Interactive web resource for exploring known and predicted protein-protein interaction networks and functional enrichment
7. [DAVID Functional Annotation](https://david.ncifcrf.gov/) | Integrated database and tools for biological gene list enrichment, GO terms, and pathway mapping
8. [Nextstrain](https://nextstrain.org/) | Real-time pathogen tracking and phylodynamic visualization of viral and bacterial evolution

# Tools
> Bioinformatics Tools and Software List
---

## Programming
### Languages
1. [Python](https://www.python.org/) | Dominant language for scientific computing, machine learning, and bioinformatics pipelines (BioPython, Scanpy, PyTorch)
2. [R](https://www.r-project.org/) | Standard language and environment for statistical analysis, differential expression, and visualization via Bioconductor and CRAN
3. [Bash / Shell](https://www.gnu.org/software/bash/) | Core scripting language for Linux environments, HPC job scheduling, and high-throughput command piping
4. [Rust](https://www.rust-lang.org/) | Modern systems language chosen for high-performance, memory-safe bioinformatics tools (e.g., noodles, sourmash)
5. [C / C++](https://isocpp.org/) | Foundational high-performance language behind core aligners and indexers (samtools, BWA, minimap2)
6. [Nextflow DSL](https://www.nextflow.io/) | Specialized workflow scripting language built on Groovy for distributed, scalable genomics pipelines
7. [Julia](https://julialang.org/) | High-performance dynamic language for numerical and computational biology (BioJulia)

### Environment and Package Management
1. [Anaconda](https://www.anaconda.com/) | Enterprise and desktop distribution of Python and R for data science
2. [Miniconda](https://docs.anaconda.com/free/miniconda/index.html) | Minimal installer for Conda package management without bloat
3. [Pixi](https://pixi.sh/) | Ultrafast, reproducible package management workflow tool based on Conda ecosystems and lockfiles
4. [Micromamba](https://mamba.readthedocs.io/en/latest/user_guide/micromamba.html) | Tiny, standalone, pure C++ executable for managing conda environments at maximum speed
5. [Bioconda](https://bioconda.github.io/) | Channel for conda package manager maintaining over 9,000 biological software packages
6. [RStudio Desktop](https://posit.co/download/rstudio-desktop/) | Leading integrated development environment for R and statistical programming
7. [Visual Studio Code](https://code.visualstudio.com/) | Extensible source code editor with rich extensions for Python, R, Nextflow, Docker, and remote HPC servers
8. [Docker](https://www.docker.com/) | Software containerization platform enabling portable, isolated bioinformatics environments
9. [Apptainer (Singularity)](https://apptainer.org/) | Secure container platform designed specifically for multi-tenant High-Performance Computing (HPC) clusters

---
## Data Tools
---

### Downloading
1. [SRA Toolkit / fasterq-dump](https://github.com/ncbi/sra-tools) | High-speed multi-threaded extraction of FASTQ files directly from NCBI SRA accessions
2. [aria2](https://aria2.github.io/) | Lightweight multi-protocol and multi-source command-line download utility (HTTP/HTTPS, FTP, BitTorrent)
3. [curl](https://curl.se/) | Command-line tool and library for transferring data using network protocols
4. [wget](https://www.gnu.org/software/wget/) | Non-interactive command-line tool for downloading files via HTTP, HTTPS, and FTP
5. [Aspera Connect (ascp)](https://www.ibm.com/products/aspera) | High-speed FASP protocol client used by ENA and NCBI for high-throughput genomic data transfers
6. [Kingfisher](https://github.com/wwood/kingfisher) | Flexible CLI to search and download sequencing files from SRA, ENA, and AWS Open Data

---
### Compressing
1. [pigz](https://zlib.net/pigz/) | Parallel implementation of gzip that fully leverages modern multi-core processors for fast compression
2. [bgzip / Tabix](http://www.htslib.org/doc/bgzip.html) | Block-compression tool creating BGZF format files that allow indexing and random access via Tabix
3. [zstd (Zstandard)](https://facebook.github.io/zstd/) | Fast lossless compression algorithm offering tunable high compression ratios and real-time decompression
4. [gzip](https://www.gnu.org/software/gzip/) | Standard GNU compression utility used globally for `.fastq.gz` and `.vcf.gz` files
5. [pbzip2](http://compression.ca/pbzip2/) | Parallel implementation of the bzip2 block-sorting file compressor for multi-threaded systems

---
## Sequence and Alignment
1. [minimap2](https://github.com/lh3/minimap2) | Versatile pairwise aligner for genomic DNA and spliced RNA, optimized for long reads (Oxford Nanopore, PacBio) and short reads
2. [BWA-MEM2](https://github.com/bwa-mem2/bwa-mem2) | Accelerated version of the BWA-MEM Burrows-Wheeler aligner with AVX-512 vectorization
3. [Bowtie2](https://bowtie-bio.sourceforge.net/bowtie2/index.shtml) | Fast and memory-efficient tool for aligning sequencing reads to long reference genomes
4. [STAR](https://github.com/alexdobin/STAR) | Ultrafast universal RNA-seq aligner capable of discovering spliced junctions and chimeric transcripts
5. [Samtools](http://www.htslib.org/) | Essential utilities for manipulating, sorting, filtering, and indexing SAM, BAM, and CRAM alignments
6. [Bedtools](https://bedtools.readthedocs.io/) | Comprehensive suite of utilities for genomic arithmetic and feature interval operations
7. [fastp](https://github.com/OpenGene/fastp) | Ultra-fast all-in-one FASTQ preprocessor providing quality profiling, adapter trimming, and polyG clipping
8. [MultiQC](https://seqera.io/multiqc/) | Modular reporting tool that parses bioinformatics logs across dozens of tools into a single summary HTML report
9. [GATK (Genome Analysis Toolkit)](https://gatk.broadinstitute.org/) | Gold-standard variant discovery toolkit developed by the Broad Institute for germline and somatic mutations
10. [DeepVariant](https://github.com/google/deepvariant) | High-accuracy germline variant caller based on deep convolutional neural networks developed by Google
11. [BCFtools](http://www.htslib.org/) | Fast utilities for variant calling and manipulating VCF and BCF files

---
## Single-Cell and Spatial Omics
1. [Scanpy](https://scanpy.readthedocs.io/) | Scalable Python toolkit for analyzing single-cell gene expression data, clustering, and trajectory inference
2. [Seurat](https://satijalab.org/seurat/) | Comprehensive R package for single-cell RNA-seq analysis, multimodal integration, and spatial transcriptomics
3. [AnnData](https://anndata.readthedocs.io/) | Standardized Python data structure for annotated multidimensional single-cell data matrices
4. [scvi-tools](https://scvi-tools.org/) | Deep probabilistic modeling framework for single-cell omics (scVI, scANVI, TotalVI)
5. [Squidpy](https://squidpy.readthedocs.io/) | Spatial single-cell analysis toolkit in Python built on AnnData and Scanpy for spatial transcriptomics

---
## Structural Biology and Molecular Modeling
1. [AlphaFold](https://github.com/google-deepmind/alphafold) | Groundbreaking deep learning system by Google DeepMind that predicts 3D protein structures from amino acid sequence
2. [ESMFold](https://github.com/facebookresearch/esm) | Evolutionary Scale Modeling framework by Meta AI for fast single-sequence protein structure prediction
3. [RFdiffusion](https://github.com/RosettaCommons/RFdiffusion) | Generative diffusion model developed by the Baker Lab for de novo protein structure and binder design
4. [Boltz-1](https://github.com/jwohlwend/boltz) | Open-source biomolecular foundation model for predicting 3D complex structures of proteins, RNA, DNA, and small molecules
5. [PyMOL](https://pymol.org/) | Leading molecular graphics system for rendering high-resolution 3D macromolecular structures
6. [UCSF ChimeraX](https://www.cgl.ucsf.edu/chimerax/) | Next-generation molecular visualization program for large biological assemblies, density maps, and cryo-EM data
7. [AutoDock Vina](https://vina.scripps.edu/) | High-speed, accurate open-source molecular docking engine for virtual screening and drug discovery

# Techniques
> Some useful techniques in the Bioinformatics workflow

## Data Processing
> Methods to extract, Analyze, and Preprocess Data

### Bioinformatics One-liners
> Oneliner terminal commands to make life easier

1. [Bioinformatics One-liners (Stephen Turner)](https://github.com/stephenturner/oneliners) | Curated collection of bash, awk, sed, sort, and cut one-liners for genomics files
2. **Count reads in a FASTQ file:**
   ```bash
   zcat reads.fastq.gz | echo $((`wc -l`/4))
   ```
3. **Inspect the first read of a gzipped FASTQ file:**
   ```bash
   gzip -dc reads.fastq.gz | head -n 4
   ```
4. **Count mapped reads in a BAM file:**
   ```bash
   samtools view -c -F 4 aligned.bam
   ```
5. **Extract chrom, start, end from a BED file and convert to 1-based coordinates:**
   ```bash
   awk -F'\t' '{print $1, $2+1, $3}' OFS='\t' regions.bed
   ```
6. **Filter VCF for PASS variants with quality >= 30 using bcftools:**
   ```bash
   bcftools view -f PASS -i 'QUAL>=30' input.vcf.gz -O z -o filtered.vcf.gz
   ```
7. **Calculate summary statistics of a FASTA file using SeqKit:**
   ```bash
   seqkit stats assembly.fasta
   ```
8. **Extract sequences by ID or region from a FASTA file with Samtools:**
   ```bash
   samtools faidx genome.fasta chr1:1000-2000
   ```

## Command Line Operations
> Core shell operations and HPC patterns for computational biology

1. **High-Performance Cluster Job Submission (SLURM):**
   ```bash
   sbatch --cpus-per-task=8 --mem=32G --time=04:00:00 --wrap="nextflow run nf-core/rnaseq -profile slurm"
   ```
2. **Parallel Execution Across Multiple Samples (GNU Parallel):**
   ```bash
   find raw_data/ -name "*_1.fastq.gz" | parallel -j 4 'fastp -i {} -I {//}/{/._1.fastq.gz}_2.fastq.gz -o clean/{/}'
   ```
3. **Disk Space and Directory Size Auditing:**
   ```bash
   du -sh * | sort -h
   ```
4. **Persistent Sessions on Remote Servers:**
   ```bash
   tmux new -s bioinfo_run
   # Detach with: Ctrl+B then D; Re-attach with: tmux attach -t bioinfo_run
   ```
5. **Secure High-Speed File Syncing:**
   ```bash
   rsync -avzP --partial user@cluster.edu:/data/projects/ ./local_dir/
   ```

## Disease Databases
> Primary repositories linking human genes, variants, and clinical phenotypes

1. [DisGeNET](https://www.disgenet.org/) | Comprehensive discovery platform containing one of the largest collections of human gene-disease and variant-disease associations
2. [OMIM (Online Mendelian Inheritance in Man)](https://www.omim.org/) | Authoritative compendium of human genes and genetic phenotypes focusing on mendelian disorders
3. [ClinVar](https://www.ncbi.nlm.nih.gov/clinvar/) | Public archive of reported relationships among human variations, classifications, and phenotypes with supporting clinical evidence
4. [COSMIC (Catalogue of Somatic Mutations in Cancer)](https://cancer.sanger.ac.uk/cosmic) | World's most extensive curated resource for exploring the impact of somatic mutations in human cancer
5. [GWAS Catalog](https://www.ebi.ac.uk/gwas/) | NHGRI-EBI catalog of published genome-wide association studies mapping variants to traits
6. [Orphanet](https://www.orpha.net/) | International portal for rare diseases and orphan drugs with clinical nomenclature and epidemiological data
7. [MalaCards](https://www.malacards.org/) | Integrated clinical disease database synthesizing clinical, molecular, and therapeutic annotations

## Interaction Databases
> Molecular pathways, protein-protein, and chemical-target interaction networks

1. [STRING](https://string-db.org/) | Database of known and predicted physical and functional protein-protein interactions with cross-species confidence scores
2. [BioGRID](https://thebiogrid.org/) | Curated biological repository of physical and genetic interactions in model organisms and humans
3. [IntAct](https://www.ebi.ac.uk/intact/home) | EMBL-EBI open-source database of molecular interactions derived from curated literature and direct submissions
4. [Reactome](https://reactome.org/) | Open-source, curated pathway database providing intuitive biological process maps and pathway enrichment analysis
5. [KEGG (Kyoto Encyclopedia of Genes and Genomes)](https://www.genome.jp/kegg/) | High-level database resource integrating genomic, chemical, and systemic functional information
6. [STITCH](http://stitch.embl.de/) | Search tool for interactions between chemicals and proteins, integrating metabolic and phenotypic associations
7. [DrugBank](https://go.drugbank.com/) | Comprehensive database combining detailed molecular drug data with drug target, mechanism, and interaction records

# Books
1. [The Biostar Handbook: 2nd Edition](https://www.biostarhandbook.com/)|The Biostar Handbook is a comprehensive guide to bioinformatics, bridging biology, computer science, and statistical data analytics for genomic information processing. Developed over half a decade in a research university, it serves as a vital resource in accredited Ph.D. level training programs
2. [Bioinformatics: Sequence and Genome Analysis by David W. Mount](https://www.amazon.in/Bioinformatics-Sequence-Analysis-David-Mount/dp/0879697121)|This book provides a comprehensive introduction to bioinformatics, covering sequence alignment, gene prediction, molecular evolution, and other key topics.
3. [Introduction to Protein Architecture: The Structural Biology of Proteins](https://www.amazon.in/Introduction-Protein-Architecture-Structural-Proteins/dp/0198504748)|Introduction to Protein Architecture explains the general characteristics of proteins that underlie the very great variety of folding patterns observed in nature. For specialists in structural biology.
4. [Bioinformatics and Functional Genomics](https://www.wiley.com/en-us/Bioinformatics+and+Functional+Genomics,+3rd+Edition-p-9781118581780)|This book serves as an excellent single-source textbook for advanced undergraduate and beginning graduate-level courses in the biological sciences and computer sciences.
5. [Bioinformatics Algorithms: An Active Learning Approach by Phillip Compeau & Pavel Pevzner](https://www.bioinformaticsalgorithms.org/)|Groundbreaking textbook introducing the algorithmic principles behind bioinformatics with hands-on coding challenges and Rosalind integration.
6. [Biological Sequence Analysis: Probabilistic Models of Proteins and Nucleic Acids by Durbin, Eddy, Krogh & Mitchison](https://www.cambridge.org/core/books/biological-sequence-analysis/AA4A5599E985552E4BE4D116DFA40A0F)|The classic reference text covering probabilistic models, Hidden Markov Models (HMMs), and sequence alignment theory.
7. [Statistical Analysis of Next Generation Sequencing Data by Somnath Datta & Daniel S. Nettleton](https://link.springer.com/book/10.1007/978-3-319-07212-8)|Covers statistical methodology, experimental design, differential expression, and high-throughput sequencing data analysis.
8. [Orchestrating Single-Cell Analysis with Bioconductor (OSCA)](https://bioconductor.org/books/release/OSCA/)|Comprehensive, open-source book teaching end-to-end workflows for single-cell RNA sequencing data analysis in R.
9. [Deep Learning for the Life Sciences by Bharath Ramsundar et al.](https://www.oreilly.com/library/view/deep-learning-for/9781492039822/)|Practical guide explaining how to apply deep learning architectures to genomics, molecular modeling, and drug discovery.

# Pipelines
> Production-grade, reproducible bioinformatics workflows and frameworks

1. [nf-core](https://nf-core.com/) | Community-driven collection of high-quality, peer-reviewed Nextflow pipelines for genomics, transcriptomics, and proteomics
2. [nf-core/rnaseq](https://nf-core.com/rnaseq) | Standardized Nextflow pipeline for RNA sequencing analysis from raw FASTQ to gene counts and quality control reports
3. [nf-core/sarek](https://nf-core.com/sarek) | Comprehensive pipeline for germline and somatic variant detection across WGS, WES, and targeted panels
4. [Snakemake Workflow Catalog](https://snakemake.github.io/snakemake-workflow-catalog/) | Official catalog of modular, reproducible, and standardized Snakemake pipelines across diverse omics fields
5. [GATK Best Practices Workflows](https://gatk.broadinstitute.org/hc/en-us/sections/360007226651-Best-Practices-Workflows) | Industry-standard pipelines by the Broad Institute for germline SNPs/Indels, somatic mutations, and structural variants
6. [Nextflow](https://www.nextflow.io/) | Scalable, reproducible workflow orchestrator supporting Docker, Singularity, SLURM, and major cloud providers
7. [Snakemake](https://snakemake.readthedocs.io/) | Python-based workflow management engine designed to create reproducible and scalable data analysis pipelines

# Algorithms
> Core computational biology algorithms and sequence processing foundations

## Basics
1. [Global Alignment - Needleman Wunsch](https://www.youtube.com/watch?v=ipp-pNRIp4g&ab_channel=Bioinformatica) | Dynamic programming algorithm for optimal end-to-end alignment of two biological sequences
2. [Local Alignment - Smith Waterman](https://en.wikipedia.org/wiki/Smith%E2%80%93Waterman_algorithm) | Dynamic programming algorithm for identifying optimal conserved regions and local similarities
3. [BLAST Heuristic Alignment](https://blast.ncbi.nlm.nih.gov/Blast.cgi) | Seed-and-extend heuristic search algorithm for rapid querying against large sequence databases
4. [Burrows-Wheeler Transform (BWT) & FM-Index](https://en.wikipedia.org/wiki/Burrows%E2%80%93Wheeler_transform) | Reversible string compression and indexing technique enabling ultra-fast exact matching in modern aligners (BWA, Bowtie)
5. [de Bruijn Graphs](https://en.wikipedia.org/wiki/De_Bruijn_graph) | Graph representation based on k-mer overlaps used extensively for de novo genome and transcriptome assembly
6. [Hidden Markov Models (HMMs)](https://en.wikipedia.org/wiki/Hidden_Markov_model) | Statistical Markov models used for gene prediction, profile alignments, and protein domain classification (HMMER)
7. [Phylogenetic Tree Reconstruction](https://en.wikipedia.org/wiki/Phylogenetic_tree) | Distance-based (Neighbor-Joining, UPGMA) and probabilistic methods (Maximum Likelihood, Bayesian) for evolutionary history

# Tutorials
> Practical, hands-on learning resources and guided walkthroughs

1. [Rosalind](https://rosalind.info/) | Hands-on platform for learning bioinformatics and programming through graded computational problem solving
2. [Harvard Chan Bioinformatics Core (HBC) Training](https://hbctraining.github.io/main/) | In-depth modular training materials on RNA-seq, single-cell analysis, ChIP-seq, and command-line genomics
3. [The Carpentries - Data Carpentry Genomics](https://datacarpentry.org/genomics-workshop/) | Accessible, structured curriculum introducing the Unix shell, data wrangling, and variant discovery
4. [Scanpy Single-Cell Tutorials](https://scanpy.readthedocs.io/en/stable/tutorials.html) | Step-by-step walkthroughs for single-cell clustering, trajectory inference, and data integration in Python
5. [Seurat PBMC 3k Guided Tutorial](https://satijalab.org/seurat/articles/pbmc3k_tutorial.html) | Canonical tutorial for QC, dimensional reduction (PCA, UMAP), clustering, and marker identification in R
6. [Biostars Tutorials Forum](https://www.biostars.org/t/Tutorials/) | Practical computational biology tutorials and recipes curated and vetted by community experts
7. [GATK Best Practices Tutorials](https://gatk.broadinstitute.org/hc/en-us/categories/360002310591-Tutorials) | Official practical guides and walkthroughs for implementing variant discovery pipelines

# Courses
> Premier university and institute courses in bioinformatics and computational biology

1. [Bioinformatics Specialization - UC San Diego (Coursera)](https://www.coursera.org/specializations/bioinformatics) | Taught by Pavel Pevzner and Phillip Compeau, covering algorithmic foundations from sequence alignment to genome assembly
2. [Genomic Data Science Specialization - Johns Hopkins University (Coursera)](https://www.coursera.org/specializations/genomic-data-science) | Comprehensive specialization covering Galaxy, Python, R, Bioconductor, and command-line genomics tools
3. [EMBL-EBI Online Training](https://www.ebi.ac.uk/training/) | Free self-paced courses and webinars covering biological data management, APIs, and analytical tools
4. [MIT 6.047/6.878: Computational Biology (MIT OpenCourseWare)](https://ocw.mit.edu/courses/6-047-computational-biology-fall-2015/) | Comprehensive lectures on algorithms for genomics, epigenomics, regulatory networks, and population genetics
5. [HarvardX: Data Analysis for Life Sciences (edX)](https://www.edx.org/certificates/professional-certificate/harvardx-data-analysis-for-life-sciences) | Statistical foundations and computational methods for analyzing genomics and high-throughput biological data
