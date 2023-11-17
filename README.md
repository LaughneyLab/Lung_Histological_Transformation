# LUAD --> SCLC Histological Transformation

Repository for main single-cell RNA-seq analyses for the lung cancer histological transformation paper:

https://www.biorxiv.org/content/10.1101/2023.06.21.545980v1

Raw and processed data are available on GEO under accession TBD:

<GEO_Link>

## Dependencies

1. Python 3+
2. Jupyter Notebooks
3. luad_sclc_ht.tar docker container

### Docker:

The relevant docker container is available on dockerhub:

`docker pull eearlie/luad_sclc_ht`

See [Docker Pull](https://docs.docker.com/engine/reference/commandline/pull/) for more details.


## Notebooks

**TEC_Lineage_Probability_Archetype_Visualization.ipynb:**

  * Jupyter notebook for analyzing lung epithelial lineage probabilities.
  * This notebook includes computing and visualizing the lineage probability archetypes.


**Histological_Transformation_Subset_Trajectory_Computation.ipynb:**

  * Jupyter notebook for re-computing CellRank trajectory results for the histological transformation dataset.


**Histological_Transformation_Subset_Trajectory_Visualization.ipynb:**

  * Jupyter notebook for visualizing the histological transformation trajectory results and reproducing published figures.


### Data

  * Small files used in the above Jupyter Notebooks are available in the data directory of this repository.
  * Sequencing data are available through the GEO accession listed above.
