# **UCSC Cell Browser Activty**

# Assigned Gene and Disease
**Gene:** SOD1 (Superoxide Dismutase 1)  
**Associated Disease:** ALS (Amyotrophic Lateral Sclerosis)

# Organ/Tissue Choice and Dataset Information
**Dataset:** Human Neural Organoid Cell Atlas (HNOCA) – Disease Atlas  
**Cells:** ~409,277 single cells  
**Relevance:** The dataset is relevant because it contains neural organoid-derived cells, allowing SOD1 expression to be examined across different neural and glial cell populations. However, because the dataset is based on organoid models rather than patient-derived brain or spinal-cord tissue, the observed expression patterns may not fully represent SOD1 expression in individuals with ALS.

# Understanding the Cell Map
**Type of visualization:**  
The visualization uses a UMAP (Uniform Manifold Approximation and Projection) layout, a dimensionality-reduction method used to represent high-dimensional single-cell transcriptomic data in a lower-dimensional space based on similarities in gene-expression profiles.

**What does one dot represent?**  
Each dot represents one individual cell captured in the dataset. The position of each cell reflects its transcriptomic similarity to other cells based on their gene-expression profiles.

**What do the clusters represent?**  
The clusters represent groups of cells with similar gene-expression signatures. In this dataset, the clusters correspond to distinct neural and glial cell populations derived from organoids, such as neurons, astrocytes, and oligodendrocyte progenitor cells (OPCs).

**Cell-type or cluster labels visible in the dataset:**  
- Astrocyte  
- Oligodendrocyte Progenitor Cell (OPC)  
- Microglia  
- Dorsal Telencephalic Neuron  
- Non-telencephalic Neuron  

# Assigned Gene Expression
**Assigned gene symbol:** SOD1 (Superoxide Dismutase 1)  
**Dataset used:** Human Neural Organoid Cell Atlas (HNOCA) – Disease Atlas (~409,277 cells)  

**Is expression widespread, restricted, or low/undetected?**  
Widespread. SOD1 expression is detectable across a large proportion of cells and is observed across multiple cell clusters, although expression intensity varies among cell populations.

**Which cluster(s) appear to contain cells with stronger expression?**  
Stronger SOD1 expression appears in the Astrocyte, Glioblast, and Choroid Plexus (CP) clusters, as indicated by the greater concentration of cells with higher expression intensity.

**Which cluster(s) appear to contain little or no detectable expression?**  
Little or no detectable SOD1 expression appears in the Microglia, Non-telencephalic NPC/Non-telencephalic Neuron, and Neural Crest (NC) Derivatives clusters, where many cells show low or undetected expression.


# Cell Types and Clusters
**Cell type/cluster with the strongest visible expression:**  
Astrocyte, with Glioblast and Choroid Plexus (CP) also showing relatively strong SOD1 expression, based on the higher concentration of dark-colored expression signals.

**Another cell type/cluster with detectable expression:**  
Dorsal Telencephalic Neuron, which shows detectable and relatively moderate SOD1 expression across multiple cells.

**Cell type/cluster with relatively low or undetected expression:**  
Microglia, with NC Derivatives and Non-telencephalic NPC also showing relatively low or undetected SOD1 expression in many cells.

**Is the expression pattern broad or cell-type restricted?**  
The expression pattern appears broad or widespread, with SOD1 detected across multiple cell types rather than being restricted to a single cellular population.

**Biological interpretation:**  
Based on the selected HNOCA Disease Atlas dataset, SOD1 shows broad expression across neural and glial cell populations, which is consistent with its role in cellular antioxidant defense through the detoxification of superoxide radicals. The relatively stronger expression observed in astrocytes may reflect differences in cellular metabolism and oxidative-stress management; however, this is an interpretation of the selected organoid dataset and does not by itself establish a cell-type-specific biological mechanism. Low or undetected expression in some clusters may also be influenced by technical dropout inherent to single-cell RNA sequencing rather than complete absence of SOD1 transcripts.


# Expression Plot
**Which cells/cluster did you select?**  
The selected cell group was the Dorsal Telencephalic Neuron cluster. The expression plot was then examined to compare SOD1 expression in this selected population with other cell groups in the dataset.

**Does your selected group show higher, lower, or similar expression compared with the comparison cells?**  
The Dorsal Telencephalic Neuron cluster shows moderate SOD1 expression. Based on the available dot plot, its expression appears lower than the higher-expressing Glioblast and Choroid Plexus (CP) clusters, but higher than clusters such as Microglia and EC, which show lower expression signals.  
The dot plot provides two measurements: dot color represents mean expression, while dot size represents the proportion of cells with detectable/non-zero expression, according to the plot legend. The Dorsal Telencephalic Neuron cluster has a relatively large dot with moderate color intensity, indicating that SOD1 is detected in a substantial proportion of cells, with moderate mean expression.

**What does the expression plot add that was not obvious from the UMAP/t-SNE map?**  
The expression plot provides a more direct comparison of expression level and the proportion of cells expressing SOD1 across cell types. While the UMAP shows the spatial distribution of individual cells and their relative expression, the dot plot summarizes each cluster using two measures: mean expression and the fraction of cells with detectable expression. This helps distinguish whether a cluster's signal reflects broad detection across many cells or relatively limited detection within the population.


# Marker Genes
**Cluster/cell type examined:** Astrocyte  
**Marker gene 1:** CLU  
**Marker gene 2:** B2M  
**Marker gene 3:** PTN  

**Does your assigned gene behave like a cell-type marker in this dataset? Explain briefly.**  
No. SOD1 does not appear to behave as a cell-type-specific marker in this dataset because its expression is detected across multiple cell populations, including neuronal and glial clusters, rather than being uniquely associated with the Astrocyte cluster. Although SOD1 has an important biological role in antioxidant defense and cellular protection against oxidative stress, its broad expression pattern does not make it a specific marker for one cell type in this dataset.


# Disease Gene vs. Marker Gene
**Assigned disease gene:** SOD1  
**Marker gene:** CLU  

**Which gene shows a more cell-type-restricted expression pattern?**  
CLU shows a more cell-type-restricted expression pattern in the selected dataset, with stronger expression associated with the Astrocyte cluster.

**Which gene appears more broadly expressed?**  
SOD1 appears more broadly expressed, with detectable expression across multiple neural and glial cell populations rather than being concentrated in one cell type.

**What does this comparison teach you about the difference between a disease-associated gene and a cell-type marker gene?**  
This comparison shows that a disease-associated gene does not necessarily function as a cell-type marker. SOD1 is associated with disease because variants in the gene can contribute to SOD1-related ALS, but its broad expression means it is not specific to one cell type in this dataset. In contrast, CLU shows a more cell-type-associated expression pattern and can therefore help characterize the Astrocyte population. The comparison is based specifically on the expression patterns observed in the selected HNOCA Disease Atlas dataset.


# Connection to Genome Browser and ClinVar

**On which chromosome is your assigned gene located?**  
The SOD1 gene is located on chromosome 21. In the GRCh38/hg38 genome assembly, it is located at approximately chr21:31,659,693-31,668,931 on the positive strand.

**What disease-associated variant did you examine previously?**  
The variant examined was NM_000454.5(SOD1):c.272A>C (p.Asp91Ala/D91A). This is a single-nucleotide substitution in the coding sequence that changes the amino acid aspartic acid (Asp/D) to alanine (Ala/A) at position 91 of the SOD1 protein. The corresponding ClinVar record is Variation ID 14766 (VCV000014766.81), which has conflicting classifications of pathogenicity.

**In the current Cell Browser dataset, which cell type(s) express the gene?**  
In the selected HNOCA Disease Atlas dataset, SOD1 shows broad expression across multiple neural and glial cell populations. Detectable expression was observed in cell types including Astrocytes, Dorsal Telencephalic Neurons, Glioblast, and Choroid Plexus (CP), although the apparent expression level varies among clusters.

**Does the observed cell expression make biological sense based on what you already know about the gene's function or associated disease?**  
Yes. The broad expression pattern is biologically plausible because SOD1 encodes superoxide dismutase 1, an enzyme involved in cellular antioxidant defense by converting superoxide radicals into less reactive molecules. Because oxidative stress can affect many cell types, SOD1 would not necessarily be expected to be restricted to one neural cell population. The expression observed in both neuronal and glial populations therefore provides cellular context for the gene's general biological function; however, the stronger expression observed in particular clusters should not be interpreted as proof that those cell types are specifically responsible for SOD1-related disease.

**Can this single Cell Browser dataset prove that the gene causes the disease? Explain why or why not.**  
No. A Cell Browser dataset primarily shows the distribution of gene expression among cell populations and cannot by itself establish disease causation. Demonstrating that a gene or variant causes disease requires additional genetic, clinical, functional, and experimental evidence. In this case, the Cell Browser provides information about where SOD1 is expressed, while the previous genome activity provides information about the gene's genomic location, structure, and the c.272A>C (p.Asp91Ala) variant.


# Reflection
**What did the UCSC Cell Browser show you that the UCSC Genome Browser could not?**  
The Cell Browser showed the distribution of SOD1 expression across different cell populations, allowing expression patterns to be examined at the cellular level. In contrast, the Genome Browser showed the gene's genomic location, exon-intron structure, transcript models, sequence conservation, and annotated variants. Therefore, the Cell Browser provided cellular expression context that was not apparent from the genomic view alone.

**Why can the same gene have different expression levels among different cell types?**  
Different cell types have distinct physiological functions and therefore require different sets and amounts of proteins. Differences in transcriptional regulation, cellular state, and metabolic requirements can result in different levels of gene expression among cell populations.

**Why should you be careful when interpreting a gene that shows zero or very low expression in single-cell data?**  
Zero or very low expression in single-cell RNA-sequencing data does not necessarily mean that the gene is completely absent from the cell. Technical dropout, low transcript abundance, sequencing depth, and other technical factors can cause transcripts to go undetected. Therefore, it is more appropriate to describe the result as low or undetectable expression in the dataset rather than definitive biological absence.

**Why is it useful to combine information about genomic location, genetic variants, and cell-specific gene expression?**  
Combining these types of information provides a more complete understanding of a gene, from its genomic organization and sequence variation to its cellular expression pattern. For SOD1, this connects its location on chromosome 21 and gene structure with the c.272A>C (p.Asp91Ala) variant and its broad expression across neural and glial populations. These complementary observations provide biological context, although they do not independently establish disease causation.

**What was the most interesting observation you made about your assigned gene?**  
The most interesting observation was that SOD1 showed broad expression across multiple neural and glial cell populations rather than being restricted to a single cell type. This was particularly interesting because the previous genome activity focused on a specific coding variant, p.Asp91Ala, demonstrating how genomic information about a disease-associated variant can be connected with the cellular expression pattern of the same gene.

# References and Link
- UCSC Cell Browser dataset: [HNOCA – Disease Atlas]([https://cells.ucsc.edu/?ds=hnoca&gene=SOD1]))  
