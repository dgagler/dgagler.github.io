# Dylan C. Gagler
Computational Biologist | Astrobiologist

[CV](https://github.com/dgagler/dgagler/blob/master/dgagler_CV.pdf)

[LinkedIn](https://www.linkedin.com/in/dylan-gagler-4a0a68191/) 

[Data Visualization Portfolio](https://nbviewer.jupyter.org/github/dgagler/Data-Visualization-Portfolio/blob/master/portfolio%20%281%29.ipynb)

## About Me
I recently graduated with my MS from Arizona State University, where I studied astrobiology and computational biology in the lab of Dr. Sara Imari Walker. I am **fluent in Python, competent in R**, have expertise **analyzing, visualizating, and communicating complex biological data**. My thesis project involved accumulating large amounts of microbial genetic and biochemical data from the Joint Genome Institute's Integrated Microbial Genomes and Microbiomes (JGI IMG/M) to explore the notion of universality in biochemistry and uncover patterns in microbial enzyme distributions. A manuscript is currently in prep. Other relevant research experience single-cell RNA sequencing analysis and microbiome analysis. Prior research experience includes geochemical and microbiological field work in Yellowstone National Park, DNA extraction and amplification, and gas chromatography. Outside of research I love to backpack, be in nature, play table tennis, read, and spend time with my friends and family.

# Projects
Below you can learn more about my research and previous and current projects. Click on the title links to see overviews in Jupyter NBViewer.

# [Patterns in life's use of major enzymatic reaction classes](https://nbviewer.jupyter.org/github/dgagler/dgagler.github.io/blob/master/enzyme_demo.ipynb)

**Data retrieval, cleaning, analysis, and visualization in Python.** A driving question in astrobiology is whether the structure and diversity of life we see on Earth is the result of chemical and evolutionary contingency, or the manifestation of underlying organizational principles. The realization of such principles would inform attempts at synthesizing life in the laboratory, searching for life in the universe, and understanding the origin of life on Earth. For this project, I leverage large amounts of publically available genetic and enzymatic data for organisms across the tree of life in tandem with biochemical reaction data to uncover patterns in life's use of enzyme reaction classes across domains and levels of organization.

# [Microbial Exploration of Spirea Creek, Yellowstone National Park](https://nbviewer.jupyter.org/github/dgagler/spirea/blob/master/spirea_sequencing_demo.ipynb)

**Microbiological fieldwork, DNA extraction and PCR amplification, sequence analysis and taxonomic classification using QIIME 2, and data visualization in Python.** Yellowstone National Park (YNP) is one of the premier locations to study the intersection of geochemistry and microbiology. For this project, I collected microbial samples from a set of previously uncharacterized geochemical hot springs in YNP. DNA was extracted from these samples, amplified via PCR, and subsequently sequenced. I analyzed the sequence data using QIIME 2 and visualized the results using python. This project explores the biology of diverse hot spring ecosystems.

# [Cell-type Identification of Single-Cell RNA Sequencing Data](https://nbviewer.jupyter.org/github/dgagler/scRNA-seq/blob/master/PBMC_analysis.ipynb)


**Quality control, normalization, feature selection, dimensionality reduction, clustering, cell-type annotation, and visualization of single-cell RNA sequencing data using Bioconductor in R.** Peripheral blood mononuclear cells (PBMCs) are blood cells with a round nucleus. These cells are a critical part of the immune system which primarily fight off infection. However, PBMCs consist of multiple cell types and studying the function of the different cell types can be difficult using bulk RNA sequencing methods. As such, single-cell RNA sequencing is a valuable tool for studying the heterogeneity and differential expression of PMBCs. Here, I walk through an analytical pipeline for cell-type identification in a publicaly available 10X Genomics PBMC dataset in R using various Bioconductor packages including scran, scater, and DropUtils.

# [Exploring microbial diversity and composition with DADA2 and phyloseq in R](https://nbviewer.jupyter.org/github/dgagler/dgagler.github.io/blob/master/mouse_microbiome_dada2phyloseq.ipynb)

**Denoising, filtering, trimming, dereplicating, sample inference, taxonomic characterization, and visualization of murine microbiome data using the DADA2 and phyloseq packages in R.** Analyzing the bacterial composition of a publically available dataset. The data is from a longitudinal study of the fecal samples of 12 mice over the first year of life which investigated the development and stabilization of the murine microbiome following weaning. In this workflow, we will start with raw reads and end with an assessment of the taxonomic diversity and composition of these samples.

# [Taxonomic Exploration and Phylogenetic Tree Visualization of Hot Spring Microbiomes from Spirea Creek, YNP](https://nbviewer.jupyter.org/github/dgagler/dgagler.github.io/blob/master/qiime_to_phyloseq_spirea.ipynb)

**Importing, denoising, and generating feature tables and rooted phylogenetic trees in QIIME 2. Generating phyloseq objects and importing data into R for visualization.** 
