# DSM050-Data-Visualisation-Final-Coursework-Assignment
Repository for the DSM050 Data Visualisation final coursework

This project performs an analysis of the celiac disease *ontological space*, as defined by the disease-disease network (taxonomic space) 
and disease-function network both derived from the Stanford Biomedical Network Dataset Collection. 
The analysis is conducted in Python and is based on the use of NetworkX.


## Data Access
The **datasets** used in this project are publicly available and are distributed under the BSD license.

Marinka Zitnik Rok Sosič, Sagar Maheshwari and J. Leskovec, “BioSNAP Datasets: Stanford Biomedical Network Dataset Collection.” Aug. 2018. [Online]. Available: http://snap.stanford.edu/biodata


### Required Files

1. `DD-Miner_miner-disease-disease.tsv.gz`
2. `D-DoMiner_miner-diseaseDOID.tsv.gz`
3. `D-MeshMiner_miner-disease.tsv.gz`
4. `doid.obo`
5. `DF-Miner_miner-disease-function.tsv.gz`
6.  go-basic.obo` — too large for GitHub (>25MB); download directly from [Gene Ontology](http://purl.obolibrary.org/obo/go/go-basic.obo)

---

## Repository Structure
* `data/` : Local folder for the downloaded tsv and obo files.
* `notebook.ipynb` : The Jupyter Notebook containing all data processing and visualizations.
*  `outputs/` : Excel files and appendices generated from the analysis.
* `.gitignore` : Excludes local temporary files and raw data.
* `LICENSE` : MIT License.
