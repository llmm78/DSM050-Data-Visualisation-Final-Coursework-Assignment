# DSM050-Data-Visualisation-Final-Coursework-Assignment
Repository for the DSM050 Data Visualisation final coursework

This project performs an analysis of the celiac disease *ontological space*, as defined by the disease-disease network (taxonomic space) 
and disease-function network both derived from the Stanford Biomedical Network Dataset Collection. 
The analysis is conducted in Python and is based on the use of NetworkX.


## Data Access
The **datasets** used in this project are publicly available and are distributed under the BSD license.

Marinka Zitnik Rok Sosič, Sagar Maheshwari and J. Leskovec, “BioSNAP Datasets: Stanford Biomedical Network Dataset Collection.” Aug. 2018. [Online]. Available: http://snap.stanford.edu/biodata

Two supporting ontology files are sourced separately:

- `doid.obo` — Human Disease Ontology, licensed under CC0 1.0 (public domain). Available: https://disease-ontology.org
  
  L. M. Schriml et al., “The Human Disease Ontology 2022 update,” Nucleic Acids Res., vol. 50, no. D1, pp. D1255–D1261, Jan. 2022, doi: 10.1093/nar/gkab1063.
  
- `go-basic.obo` — Gene Ontology, licensed under CC BY 4.0 (attribution required). Available: http://purl.obolibrary.org/obo/go/go-basic.obo
  
  The Gene Ontology Consortium, “The Gene Ontology knowledgebase in 2026,” Nucleic Acids Res., p. gkaf1292, 2025, doi: 10.1093/nar/gkaf1292.
  
### Required Files

1. `DD-Miner_miner-disease-disease.tsv.gz`
2. `D-DoMiner_miner-diseaseDOID.tsv.gz`
3. `D-MeshMiner_miner-disease.tsv.gz`
4. `doid.obo`
5. `DF-Miner_miner-disease-function.tsv.gz`
6.  `go-basic.obo` — too large for GitHub (>25MB); download directly from [Gene Ontology](http://purl.obolibrary.org/obo/go/go-basic.obo)

---

## Repository Structure
* `data/` : Local folder for the downloaded tsv and obo files.
* `notebook.ipynb` : The Jupyter Notebook containing all data processing and visualizations.
*  `outputs/` :  Appendices generated from the analysis (Excel files).
* `.gitignore` : Excludes local temporary files and raw data.
* `LICENSE` : MIT License.
