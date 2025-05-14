# Research Portfolio
- Interdisciplinary natural scientist with extensive bioinformatic and field experience
- Peer-reviewed first author publications in astrobiology and cancer biology
- Incoming PhD student at the American Museum of Natural History interested in sea slug photosymbiosis

This portfolio showcases previous research experience in astrobiology and cancer biology which demonstrates proficiency in bioinformatic analysis of NGS data and general academic computational biology wherehow. 

[Google Scholar](https://scholar.google.com/citations?user=6l3aYEoAAAAJ&hl=en&oi=sra)

[CV](https://github.com/dgagler/dgagler/blob/master/dgagler_CV_2024.pdf)

[LinkedIn](https://www.linkedin.com/in/dylan-gagler-4a0a68191/) 

# A multiomic analysis of Waldenstrom's macroglobulinemia defines distinct disease subtypes

This study (*Gagler* et al., 2025, Blood) is now published in Blood! Check out the [manuscript](https://ashpublications.org/blood/article-abstract/doi/10.1182/blood.2024028164/537142/A-multiomic-analysis-of-Waldenstrom?redirectedFrom=fulltext) and [GitHub](https://github.com/dgagler/WM_scMultiomeAnalysis) for more details.

![Visual Abstract](https://github.com/dgagler/dgagler.github.io/blob/master/WM_visualAbstract.png)

## Brief summary
Waldenstrom's macroglobulinemia (WM) is a rare hematological malignancy clinically characterized by aberrant secretion of monoclonal IgM and the accumulation of lymphoplasmacytic cells in the bone marrow, in addition to a recurrent mutation at the L265P locus of the MYD88 gene. Note the above phrase lymphoplasmacytic, which implies that these cells are characterized by both lymphocytic and plasmacytic features. WM is known to present a melange of characteristics between the 2 cell types, both morphologically and immunologically, and recent studies have identified 2 subtypes of WM, Memory B-cell (MBC)-like and Plasma cell (PC)-like, based on DNA methylation data. The biological and clinical differences between these 2 subtypes, however, remains unclear. 

As such, this study set out to identify the transcriptional, epigenetic, and B-cell differentiation states of the malignant cell populations in MYD88-mutated WM. The results establish that WM comprises a clonal expansion of MBC with variable capacities for PC differentiation, supporting the existence of the MBC-like and PC-like subtypes. We identified SPI1/SPIB and XBP1 as potentially key transcription factors regulating the aberrant B-cell differentiation state of WM cells and further show that the subtypes exhibit differences in their use of key molecular disease pathways, including NF-kB signaling, BCR signaling, and protein homeostasis. These results suggest that it could be useful to utilize different treatment methods for distinct WM subtypes.

Analysis performed using R, Python, and bash.

![Header](https://github.com/dgagler/dgagler.github.io/blob/master/WM_header.png)

# Single-cell RNA Analysis of the Bone Marrow Stromal Compartment in a 5TGM1 Mouse Model
This study (Ghamlouch, *Gagler*, et al., 2025, Experimental Hematology & Oncology*) is now published! Check out the [manuscript](https://link.springer.com/article/10.1186/s40164-025-00606-x) and [GitHub](https://github.com/dgagler/5TGM1-Stromal) for more details.

## Brief summary
The stromal compartment of the bone marrow (BM), which includes mesenchymal stromal cells, osteocytes, fibroblasts, and endothelial cells, among others, plays a significant role in the support of normal stem cell growth and development. How this compartment, which putatively changes to support the tumor cell niche in multiple myeloma (MM), however, is not fully understood. This project helps to elucidate the role of the stromal compartment of the BM in multiple myeloma pathogenesis by using single-cell RNA sequencing on flow-sorted stromal cell populations derived from the bone marrows of mice injected with multiple myeloma.

![Stromal UMAP](https://github.com/dgagler/dgagler.github.io/blob/master/Fig2A_StromalCells_UMAP_WithCellCounts.png)

Our results show that the MM cells remodel the stromal microenvironment by altering the amount and function of MSCs and endothelial cells. Through favoring an adipocytic fate of MSCs, endothelial mesenchymal transition and altering the balance between arterial and sinusoidal endothelial cells, MM cells promote an inflammatory environment that contributes to MM development and progression.

# Single-cell RNA Analysis of the Bone Marrow Microenvironment in Response to 4-Drug Treatment Regimens
4-drug treatment regimens have proved to be highly effective at treating myeloma but a substantial minority patients are resistant to these treatment regimens and quickly relapse. The bone marrow cellular dynamics driving treatment resistance in high-risk patients, however, remain unclear. This project develops our understanding of these cellular dynamics by using single-cell RNA sequencing on flow-sorted immune cell populations derived from the bone marrows of multiple myeloma patients before and after receiving a 4-drug treatment regimen. Data analyzed in R.

# Scaling laws in enzyme function reveal a new kind of biochemical universality
This study (*Gagler et al., 2022, PNAS*) is published! Check out the [manuscript](https://www.pnas.org/doi/abs/10.1073/pnas.2106655119) for more details.

## Abstract
All life on Earth is unified by its use of a shared set of component chemical compounds and reactions, providing a detailed model for universal biochemistry. However, this notion of universality is specific to known biochemistry and does not allow quantitative predictions about examples not yet observed. Here, we introduce a more generalizable concept of biochemical universality that is more akin to the kind of universality found in physics. Using annotated genomic datasets including an ensemble of 11,955 metagenomes, 1,282 archaea, 11,759 bacteria, and 200 eukaryotic taxa, we show how enzyme functions form universality classes with common scaling behavior in their relative abundances across the datasets. We verify that these scaling laws are not explained by the presence of compounds, reactions, and enzyme functions shared across known examples of life. We demonstrate how these scaling laws can be used as a tool for inferring properties of ancient life by comparing their predictions with a consensus model for the last universal common ancestor (LUCA). We also illustrate how network analyses shed light on the functional principles underlying the observed scaling behaviors. Together, our results establish the existence of a new kind of biochemical universality, independent of the details of life on Earth’s component chemistry, with implications for guiding our search for missing biochemical diversity on Earth or for biochemistries that might deviate from the exact chemical makeup of life as we know it, such as at the origins of life, in alien environments, or in the design of synthetic life.

# [Patterns in life's use of major enzymatic reaction classes](https://nbviewer.jupyter.org/github/dgagler/dgagler.github.io/blob/master/enzyme_demo.ipynb)

**Data retrieval, cleaning, analysis, and visualization in Python.** A driving question in astrobiology is whether the structure and diversity of life we see on Earth is the result of chemical and evolutionary contingency, or the manifestation of underlying organizational principles. The realization of such principles would inform attempts at synthesizing life in the laboratory, searching for life in the universe, and understanding the origin of life on Earth. For this project, I leverage large amounts of publically available genetic and enzymatic data for organisms across the tree of life in tandem with biochemical reaction data to uncover patterns in life's use of enzyme reaction classes across domains and levels of organization.
