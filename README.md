# COVID_mda5

**Computational analysis of MDA5 driven innate immune signaling in COVID 19 and its convergence with idiopathic pulmonary fibrosis.**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)](https://jupyter.org/)

## Overview

This repository contains the analysis code accompanying our study on shared molecular pathology between severe COVID 19 and idiopathic pulmonary fibrosis (IPF). We identify an MDA5 anchored viral sensing and interferon program that appears in both diseases and use Boolean implication networks to derive a testable therapeutic hypothesis.

## Repository contents

* `*.ipynb` — analysis notebooks in publication order
* `Reg_R_*.txt`, `Reg_p_*.txt` — regression outputs for each public dataset
* `composite_dataframe*.txt` — merged, harmonized feature tables
* `bone.py` — utility module for signature scoring

## Reproducing the analysis

1. Clone the repo and install dependencies
2. Download public datasets from GEO: GSE157103, GSE168400, GSE177025
3. Run notebooks in this order:
   1. `composit-dataframe.ipynb`
   2. `coorelation.ipynb`
   3. `MV_MDA5.ipynb`
   4. `COVID_MDA5_BUBBLE.ipynb`

## Publication

> Sinha S, et al. Dysregulated MDA5 and interferon signaling underlies shared pathology in COVID 19 and IPF. *eBioMedicine*.

## Contact

Saptarshi Sinha, Ph.D. · sasinha@health.ucsd.edu · PreCSN, UC San Diego

## License

MIT License.
