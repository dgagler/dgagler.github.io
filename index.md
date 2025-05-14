# Dylan C. Gagler
Computational Biologist | Incoming PhD Student @ AMNH

[CV](https://github.com/dgagler/dgagler/blob/master/dgagler_CV_2024.pdf)

[LinkedIn](https://www.linkedin.com/in/dylan-gagler-4a0a68191/) 

# Research Portfolio
Below you can view various research projects that I have worked on, which highlight my skills in data analysis, visualization, and communication across a wide range of topics relating to the natural sciences and human health. 

# [Single-cell multiomic analysis of Waldenstrom's macroglobulinemia]
Waldenstrom's macroglobulinemia (WM) is a rare hematological malignancy clinically characterized by aberrant secretion of monoclonal IgM and the accumulation of lymphoplasmacytic cells in the bone marrow, in addition to a recurrent mutation at the L265P locus of the MYD88 gene. Note the above phrase lymphoplasmacytic, which implies that these cells are characterized by both lymphocytic and plasmacytic features. WM is known to present a melange of characteristics between the 2 cell types, both morphologically and immunologically, and recent studies have identified 2 subtypes of WM, Memory B-cell (MBC)-like and Plasma cell (PC)-like, based on DNA methylation data. The biological and clinical differences between these 2 subtypes, however, remains unclear. As such, this study set out to identify the transcriptional, epigenetic, and B-cell differentiation states of the malignant cell populations in MYD88-mutated WM. The results establish that WM comprises a clonal expansion of MBC with variable capacities for PC differentiation, supporting the existence of the MBC-like and PC-like subtypes. We identified SPI1/SPIB and XBP1 as potentially key transcription factors regulating the aberrant B-cell differentiation state of WM cells and further show that the subtypes exhibit differences in their use of key molecular disease pathways, including NF-kB signaling, BCR signaling, and protein homeostasis. These results suggest that it could be useful to utilize different treatment methods for distinct WM subtypes.

[GitHub](https://github.com/dgagler/WM_scMultiomeAnalysis)


# [Single-cell RNA Analysis of the Bone Marrow Stromal Compartment in a 5TGM1 Mouse Model]
The stromal compartment, including mesenchymal stromal cells, osteocytes, and endothelial cells, among others, plays a significant role in the support of normal stem cell growth and development. How this compartment changes in response to multiple myeloma, to support growth of the myeloma cell niche, is not fully understood. This project helps to elucidate the role of the stromal compartment in multiple myeloma pathogenesis by using single-cell RNA sequencing on flow-sorted stromal cell populations derived from the bone marrows of mice injected with multiple myeloma. Data analyzed in R.

# [Single-cell RNA Analysis of the Bone Marrow Microenvironment in Response to 4-Drug Treatment Regimens]
4-drug treatment regimens have proved to be highly effective at treating myeloma but a substantial minority patients are resistant to these treatment regimens and quickly relapse. The bone marrow cellular dynamics driving treatment resistance in high-risk patients, however, remain unclear. This project develops our understanding of these cellular dynamics by using single-cell RNA sequencing on flow-sorted immune cell populations derived from the bone marrows of multiple myeloma patients before and after receiving a 4-drug treatment regimen. Data analyzed in R.

# [Patterns in life's use of major enzymatic reaction classes](https://nbviewer.jupyter.org/github/dgagler/dgagler.github.io/blob/master/enzyme_demo.ipynb)

**Data retrieval, cleaning, analysis, and visualization in Python.** A driving question in astrobiology is whether the structure and diversity of life we see on Earth is the result of chemical and evolutionary contingency, or the manifestation of underlying organizational principles. The realization of such principles would inform attempts at synthesizing life in the laboratory, searching for life in the universe, and understanding the origin of life on Earth. For this project, I leverage large amounts of publically available genetic and enzymatic data for organisms across the tree of life in tandem with biochemical reaction data to uncover patterns in life's use of enzyme reaction classes across domains and levels of organization.

# [Microbial Exploration of Spirea Creek, Yellowstone National Park](https://nbviewer.jupyter.org/github/dgagler/spirea/blob/master/spirea_sequencing_demo.ipynb)

**Microbiological fieldwork, DNA extraction and PCR amplification, sequence analysis and taxonomic classification using QIIME 2, and data visualization in Python.** Yellowstone National Park (YNP) is one of the premier locations to study the intersection of geochemistry and microbiology. For this project, I collected microbial samples from a set of previously uncharacterized geochemical hot springs in YNP. DNA was extracted from these samples, amplified via PCR, and subsequently sequenced. I analyzed the sequence data using QIIME 2 and visualized the results using python. This project explores the biology of diverse hot spring ecosystems.

# [Exploring microbial diversity and composition with DADA2 and phyloseq in R](https://nbviewer.jupyter.org/github/dgagler/dgagler.github.io/blob/master/mouse_microbiome_dada2phyloseq.ipynb)

**Denoising, filtering, trimming, dereplicating, sample inference, taxonomic characterization, and visualization of murine microbiome data using the DADA2 and phyloseq packages in R.** Analyzing the bacterial composition of a publically available dataset. The data is from a longitudinal study of the fecal samples of 12 mice over the first year of life which investigated the development and stabilization of the murine microbiome following weaning. In this workflow, we will start with raw reads and end with an assessment of the taxonomic diversity and composition of these samples.

# [Taxonomic Exploration and Phylogenetic Tree Visualization of Hot Spring Microbiomes from Spirea Creek, YNP](https://nbviewer.jupyter.org/github/dgagler/dgagler.github.io/blob/master/qiime_to_phyloseq_spirea.ipynb)

**Importing, denoising, and generating feature tables and rooted phylogenetic trees in QIIME 2. Generating phyloseq objects and importing data into R for visualization.** 
