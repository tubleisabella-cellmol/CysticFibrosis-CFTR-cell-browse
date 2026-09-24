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

### Identify the Cell Types Expressing Your Gene

a. Cell type/cluster with the strongest visible expression: Club_P3 and Alveolar Epithelial Type 2_P3 (including "Signaling" AT2_P3) show the highest density of orange/red-colored cells.

b. Another cell type/cluster with detectable expression: Goblet_P3 and Ionocyte_P3 show some scattered detectable expression, though less dense than Club/AT2.

c. Cell type/cluster with relatively low or undetected expression: Alveolar Epithelial Type 1_P3 and Ciliated_P3/Proximal Ciliated_P3 show almost entirely pale blue (undetected) coloring.

d. Expression pattern: Cell-type restricted, concentrated within the airway/alveolar epithelial compartment rather than broad across all lung cell types.

**Interpretation based on the selected dataset**

CFTR's concentration in Club cells and Alveolar Epithelial Type 2 cells may reflect these cells' roles in secretory and surfactant-related functions, which could involve fluid and ion transport processes that CFTR, as a chloride channel, would support. The relatively low signal in Ciliated and Alveolar Epithelial Type 1 cells is consistent with their more structural/gas-exchange roles, which may rely less on CFTR-mediated chloride transport. However, since the well-known "ionocyte-dominant" CFTR pattern from other studies wasn't the clearest signal here, this may reflect differences in sequencing depth, capture efficiency, or the specific population sampled in this particular dataset rather than a contradiction of the broader biology.

