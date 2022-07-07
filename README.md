# How to: MR-EvE and literature data queries in EpiGraphDB 

This repository contains basic examples for querying MR-EvE and literature data in EpiGraphDB. This code is made available alongside the analysis published in the article _"Integrating Mendelian randomization and literature-mined evidence for breast cancer risk factors"_ on [MedRxiv (link to be added)]() 

The main development repo of this project is [https://github.com/mvab/epigraphdb-breast-cancer](https://github.com/mvab/epigraphdb-breast-cancer). The examples presented here may be helpful for understanding and/or replicating EpiGraphDB queries that were used in that project, or applying them to study your disease of interest. 

The basic examples of querying EpiGraphDB with `epigraphdb-r` R package are provided in the ["Getting started"](https://mrcieu.github.io/epigraphdb-r/articles/getting-started-with-epigraphdb-r.html) guide.


### Scripts 

* `01_mr-eve_exposure_to_outcomes.ipynb` - collect all risk factors for a disease outcome from MR-EvE

* `02_query_mediators_between_traits.ipynb` - identify potential mediators between exposure and outcome using MR-EvE

* `03_extract_trait_literature_space.ipynb` - extract literature-mined relationships related to a (GWAS) trait of interest

