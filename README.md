### Hi! I am Wenmin, a data scientist :woman_technologist: with medical training :stethoscope: working on statistical genetics :dna:.

- I am an [IVADO Postdoctoral Fellow](https://ivado.ca/en/research-community/) working with [Dr. Guillaume Lettre](http://www.mhi-humangenetics.org/en/welcome/) at Montreal Heart Institute.
- I obtained my PhD in [Quantitative Life Sciences](https://www.mcgill.ca/qls/) at McGill University supervised by [Dr. Josée Dupuis](https://www.mcgill.ca/epi-biostat-occh/josee-dupuis) and [Dr. Hamed Najafabadi](https://www.mcgillgenomecentre.ca/investigators/hamed-najafabadi/).
- Previously, I obtained my bachelor's degree in preventive medicine and data science from Fudan University.

My research focuses on developing interpretable, efficient, and robust statistical and machine learning methods for large-scale biomedical data. My ultimate goal is to improve health for all through inclusive, reproducible, and actionable research. I have developed several efficient methods for high-dimensional correlated genetic data to improve the accuracy and efficiency of key analyses in statistical genetics:

#### 1.	To identify causal genetic variants for diseases based on statistical associations and functional annotations (fine-mapping)

* We developed SparsePro to address the key challenge of integrating statistical evidence and functional genomic data.
* Software: [SparsePro](https://github.com/zhwm/SparsePro)
* Simulation and real data analyses: [Zhang et al.](https://doi.org/10.1371/journal.pgen.1011104)
* Code to reproduce analyses: [SparsePro_analysis](https://github.com/zhwm/SparsePro_analysis)

#### 2.	To detect shared genetic signals across different phenotypes to identify actionable targets for diseases (colocalization)

*	Built upon SparsePro, we developed SharePro to account for correlation between genetic variants in colocalization analysis. 
*	Software: [SharePro_coloc](https://github.com/zhwm/SharePro_coloc)
*	Simulation and real data analyses: [Zhang et al.](https://doi.org/10.1093/bioinformatics/btae295)
*	Code to reproduce analyses: [SharePro_coloc_analysis](https://github.com/zhwm/SharePro_coloc_analysis)

#### 3.	To characterize genetic effect heterogeneity across populations with different environmental exposures (GxE)

*	We adapted SharePro to reduce multiple testing burden in GxE analysis.
*	Software: [SharePro_gxe](https://github.com/zhwm/SharePro_gxe)
*	Simulation and real data analyses: [Zhang et al.](https://doi.org/10.1038/s41467-024-53818-w)
*	Code to reproduce analyses: [SharePro_gxe_analysis](https://github.com/zhwm/SharePro_gxe_analysis)

#### 4. To perform sensitivity analysis in causal inference
* We used the core gene hypothesis to identify putative core instrument variables to reduce the risk of horizontal pleiotropy in Mendelian randomization
* Software: [MR Corge](https://github.com/zhwm/MRCorge)
* Real data analyses: [Zhang et al.](https://doi.org/10.1093/bioinformatics/btae666)
* Code to reproduce analyses: [HDL->CAD](https://zhwm.github.io/MRCorge/articles/HDL_CAD.html)

#### 5. To perform robust fine-mapping in the presence of linkage disequilibrium mismatch
*	We developed a robust version of SparsePro to account for potential inconsistencies between the GWAS population and the LD reference panel.
*	Software: [RSparsePro_LD](https://github.com/zhwm/RSparsePro_LD)
*	Simulation and real data analyses: [Zhang et al.](https://biorxiv.org/cgi/content/short/2024.10.29.620968v1)
*	Code to reproduce analyses: [RSparsePro_LD_analysis](https://github.com/zhwm/RSparsePro_LD_analysis)

Check out my other projects on [Google Scholar](https://scholar.google.com/citations?user=CvTg6nMAAAAJ&hl=en)!
