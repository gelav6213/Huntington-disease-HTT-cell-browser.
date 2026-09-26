# UCSC Cell Browser Activity — HTT and Huntington Disease

## PART B. Open the UCSC Cell Browser and Choose a Dataset

Dataset name: Comparative analysis of the cellular landscape in mammalian striatum

Organ/tissue: Human Dorsal Striatum (Caudate Nucleus & Putamen)

Why you selected it for your assigned gene/disease:

- Although Huntington's disease itself is not explicitly listed in the dataset name, this dataset profiles the human caudate nucleus and putamen, the exact regions of the basal ganglia selectively degenerated in Huntington's disease. Examining this healthy baseline dataset allows us to see which cell types, such as spiny projection neurons, naturally express the HTT gene.

Publication/study name: Comparative analysis of the cellular landscape in mammalian striatum

Dataset URL:  
https://cells.ucsc.edu/?org=Human+(H.+sapiens)&bp=caudate+nucleus

---

## PART C. Understand the Cell Map

 a. What type of visualization is being shown?

It is a UMAP (Uniform Manifold Approximation and Projection) plot. UMAP is a 2D dimensionality-reduction layout used by the UCSC Cell Browser to group cells with similar gene-expression profiles.

 b. What does one dot represent?

One single dot represents one measured cell or single nucleus sequenced from the brain/striatum sample.

 c. What do the clusters represent in this particular dataset?

The clusters represent distinct brain cell types or cell populations in the striatum. Cells that share similar gene-expression profiles group close together into colored clusters, separating different biological cell types such as neurons, glia, and support cells.

 d. List at least three cell-type or cluster labels visible in the dataset.

- D1 SPN — D1 Spiny Projection Neurons
- Astrocyte
- MOL — Mature Oligodendrocytes

---

## PART D. Search for Your Assigned Gene

 a. Assigned gene symbol: HTT

 b. Dataset used: Adult Mammalian Striatum - All Cell Types

 c. Is expression widespread, restricted, or low/undetected?

- The expression of HTT is widespread across the dataset. Reddish/pink dots are distributed throughout almost every cluster rather than being strictly confined to one isolated group.

 d. Which cluster(s) appear to contain cells with stronger expression?

- The clusters with the densest reddish color, indicating stronger expression, are the neuronal clusters, particularly D1 SPN, D2 SPN, and eSPN.

 e. Which cluster(s) appear to contain little or no detectable expression?

- The MOL (Mature Oligodendrocytes) cluster appears mostly pale blue/gray, indicating low or undetected expression in the vast majority of its cells compared with the neuronal clusters.

---

## PART E. Identify the Cell Types Expressing Your Gene

 a. Cell type/cluster with the strongest visible expression

- D1 SPN and D2 SPN (Spiny Projection Neurons). These two clusters display the highest concentration of dark reddish-pink dots, showing the strongest visible HTT expression.

 b. Another cell type/cluster with detectable expression

- Astrocyte, Interneuron, or eSPN. Each of these clusters contains visible pinkish-orange dots indicating detectable HTT expression.

 c. Cell type/cluster with relatively low or undetected expression

- MOL (Mature Oligodendrocytes). This large cluster remains mostly pale blue/gray, showing very low or undetectable expression across the vast majority of its cells.

 d. Is the expression pattern broad or cell-type restricted?

- The expression pattern is relatively broad or widespread across multiple brain cell types, although it shows higher intensity in neuronal clusters such as SPNs compared with some non-neuronal cells like oligodendrocytes.

 e. Possible biological explanation

- Based on this selected dataset, HTT is broadly expressed across various brain cell types but appears enriched in medium spiny neurons, particularly D1 and D2 SPNs, of the striatum. This expression pattern is relevant to Huntington's disease because D1 and D2 SPNs are among the neuronal populations affected by the disease. This interpretation is based strictly on the observations from this single-nucleus dataset.

---

## PART F. Select Cells and Examine a Violin Plot

 a. Which cells/cluster did you select?

- I selected the neuronal clusters, specifically focusing on D1 SPN, D2 SPN, and eSPN in the striatum dataset. The expression plot displays HTT gene expression across the listed cell types, including these spiny projection neuron populations.

 b. Does your selected group show higher, lower, or similar expression compared with the comparison cells?

- The selected D1 SPN, D2 SPN, and eSPN neuronal groups show higher expression compared with non-neuronal groups such as Microglia or MOL. They display darker pink dots, indicating higher average expression, and larger dot sizes, indicating a higher percentage of expressing cells.

 c. What does the expression plot add that was not obvious from the UMAP/t-SNE map?

- The expression plot separates the average expression level represented by dot color from the proportion of expressing cells represented by dot size. This makes it easier to compare how strongly and consistently HTT is expressed across different cell types than by looking only at overlapping dots on the UMAP.

---

## PART G. Explore Marker Genes

 a. Cluster/cell type examined: D1 SPN
 b. Marker gene 1: ANO3
 c. Marker gene 2: SYT1
 d. Marker gene 3: GNAL

 e. Does your assigned gene behave like a cell-type marker in this dataset?

- No, HTT does not appear to behave as a cell-type marker in this dataset. Its expression is not clearly specific to one cell type because HTT can be observed across different cell groups. Therefore, HTT alone would not be sufficient to identify one particular cell type.

---

## PART H. Compare Your Assigned Gene With One Marker Gene

 a. Assigned disease gene: HTT
 b. Marker gene: ANO3
 c. Which gene shows a more cell-type-restricted expression pattern?
- The marker gene ANO3 shows a more cell-type-restricted expression pattern because its high expression is concentrated primarily in the spiny projection neuron clusters, particularly D1 SPN and D2 SPN, while remaining much lower in non-neuronal cells.

 d. Which gene appears more broadly expressed?
- My assigned disease gene HTT appears more broadly expressed because detectable expression is distributed across multiple distinct cell populations, including neurons and glia.

 e. What does this comparison teach you about the difference between a disease-associated gene and a cell-type marker gene?
- This comparison demonstrates that cell-type marker genes can help identify distinct cell populations through more localized expression, whereas disease-associated genes can be expressed across many cell types while still being associated with tissue-specific disease phenotypes.

---

## PART I. Connect the Cell Browser Result to Your Previous Genome Activity

 1. On which chromosome is your assigned gene located?
- The HTT gene is located on chromosome 4 (chr4) in the human genome. In the UCSC Genome Browser, it is shown on the GRCh38/hg38 assembly.

 2. What disease-associated variant did you examine previously?
- The variant I examined was NM_001388492.1(HTT):c.122C>A (p.Pro41Gln). ClinVar reports this variant as having uncertain significance and associates it with Huntington disease.

 3. In the current Cell Browser dataset, which cell type(s) express the gene?
- HTT is expressed across multiple cell types in the human striatum, including D1 SPN, D2 SPN, eSPN, Astrocytes, and Interneurons. The expression appears stronger in the D1 SPN and D2 SPN neuronal clusters, while it is lower or less detectable in cells such as MOL.

 4. Does the observed cell expression make biological sense based on what you already know about the gene's function or associated disease?
- Yes, the observed expression pattern makes biological sense because HTT is broadly expressed but shows stronger expression in striatal neuronal populations such as D1 and D2 SPNs. The striatum is important in Huntington disease because these neuronal populations are among the cells affected by the disease. The Cell Browser result therefore provides a useful connection between HTT expression and the brain region involved in Huntington disease. However, this interpretation is based only on the selected dataset and does not by itself explain why these cells are particularly vulnerable.

 5. Can this single Cell Browser dataset prove that the gene causes the disease?
- No, a single Cell Browser dataset cannot prove that HTT causes Huntington disease. It only shows the gene's expression pattern in the cells included in that particular dataset. Other evidence, such as genetic, clinical, functional, and disease studies, is needed to establish a causal relationship between the gene and the disease.

---

## PART J. Short Reflection

 1. What did the UCSC Cell Browser show you that the UCSC Genome Browser could not?

- The UCSC Cell Browser showed me which specific cell types express HTT and how strongly it is expressed in those cells. In contrast, the Genome Browser mainly showed the gene's genomic location, structure, variants, and conservation.

 2. Why can the same gene have different expression levels among different cell types?

- The same gene can have different expression levels because different cell types have different functions and therefore need different amounts of certain proteins. For HTT, the Cell Browser showed stronger expression in neuronal groups such as D1 SPN and D2 SPN than in some other cell types.

 3. Why should you be careful when interpreting a gene that shows zero or very low expression in single-cell data?

- Zero or very low expression does not always mean that the gene is completely inactive in that cell type. It can also result from technical limitations of single-cell sequencing, such as low RNA capture or dropout. Therefore, the result should be interpreted together with the overall dataset and other evidence.

 4. Why is it useful to combine information about genomic location, genetic variants, and cell-specific gene expression?

- Combining these types of information gives a more complete understanding of how a gene may be related to a disease. The genomic location shows where the gene and variant are found, while cell-specific expression shows which cells express the gene and may help explain where its biological effects occur.

 5. What was the most interesting observation you made about your assigned gene?

- The most interesting observation was that HTT is broadly expressed across several cell types but appears more strongly expressed in D1 SPN and D2 SPN neurons. This was interesting because the striatum and its neuronal populations are important in Huntington disease, connecting the gene's expression pattern with the tissue affected by the disease.
