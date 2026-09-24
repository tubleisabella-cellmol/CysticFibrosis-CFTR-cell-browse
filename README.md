# UCSC Cell Browser Activity

###Open the UCSC Cell Browser and Choose a Dataset

**Dataset name:** Krasnow Lung datasets — 10x (Human Lung Cell Atlas, Travaglini et al.)

**Dataset URL:** https://cells.ucsc.edu/?ds=stanford-czb-hlca+droplet

**Organism:** Human (H. sapiens)

**Platform:** 10x Genomics (droplet-based scRNA-seq), 66k cells

**Organ/tissue relevance to CFTR/Cystic Fibrosis:**

CFTR is most directly associated with cystic fibrosis, a disease that primarily affects the lungs and airway epithelium. I selected a human lung/airway single-cell atlas because CFTR is expressed in airway epithelial cells, where it functions as a chloride channel that regulates mucus hydration. This dataset includes annotated airway epithelial cell types (basal, ciliated, club, mucous cells), making it well-suited to examine where CFTR is expressed at the single-cell level.

**Publication/Study:**

Travaglini et al., "A molecular cell atlas of the human lung from single cell RNA sequencing," *Nature* (2020) — Krasnow Lab, Stanford.

### Understanding the Cell Map

a. Visualization type: UMAP

b. One dot = one cell (in this case, one cell from the 10x droplet-based sequencing).

c. Clusters represent distinct cell types identified in the human lung (epithelial, immune, endothelial, stromal cell types)

d. Example cluster labels observed: Basal, Ciliated, Club, Mucous, Alveolar Epithelial Type 1, Alveolar Epithelial Type 2

### Assigned Gene Expression

a. Gene symbol: CFTR

b. Dataset: Krasnow Lung datasets – 10x (Human Lung Cell Atlas, Travaglini et al.)

c. Is expression widespread, restricted, or low/undetected?

Expression is low/restricted overall. According to the Cell Browser's expression frequency legend, 98% of all cells (n=65,662) show zero detectable CFTR expression, and only ~2% of cells show any signal at all. Where expression is detectable, it is concentrated in the airway epithelial region of the map rather than spread evenly across all cell types.

d. Which cluster(s) appear to contain cells with stronger expression?

The strongest signal (warm orange coloring) appears concentrated in the epithelial cluster region, particularly near the Proximal Basal, Goblet, and Serous/Mucous clusters (P3 patient group) — an area that also appears to include an annotated Ionocyte cluster, consistent with the known biology that rare pulmonary ionocytes are the dominant CFTR-expressing cell type in the airway.

e. Which cluster(s) appear to contain little or no detectable expression?

Nearly all non-epithelial clusters show little to no detectable expression, including capillary/vascular cells (Capillary, Artery, Vein, Bronchial Vessel), stromal cells (Pericyte, Fibroblast, Myofibroblast), and immune cells (T cells, B cells, Monocytes, Macrophages, Dendritic cells).

