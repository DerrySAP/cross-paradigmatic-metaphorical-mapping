# Cross-Paradigmatic Metaphorical Mapping: Indonesian MAJU vs MUNDUR

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/DerrySAP/cross-paradigmatic-metaphorical-mapping/blob/main/dsaputra_meaning_preserving_script.ipynb)

This repository contains the open-access dataset and reproducible R scripts used for the quantitative corpus analysis in the paper: **"Cross-paradigmatic Metaphorical Mapping: A case of Indonesian MAJU vs MUNDUR"** (Putra, 2026). 

The study operates within a usage-based Construction Grammar framework to empirically test the Meaning-Preserving Hypothesis (MPH) and the Invariance Hypothesis (IH) by analyzing the semantic distribution of metaphorical spatial antonyms across active and passive voice constructions.

## Repository Contents

* `cross-paradigmatic-metaphorical-mapping_data.csv`: The dataset containing 810 tokens of the target applicative verbs (*memajukan*, *dimajukan*, *memundurkan*, *dimundurkan*) extracted from the `ind_news_2024_1M` corpus. It includes the manual semantic domain coding (e.g., 'quality', 'time', 'political nomination') and grammatical voice classifications.
*  `dsaputra_meaning_preserving_script.ipynb`: A Jupyter Notebook (R kernel) containing the exact statistical analysis. It includes the exact regular expression parameters used for data retrieval via the [`corplingr`](https://github.com/gederajeg/corplingr) package (developed by Gede Primahadi Wijaya Rajeg) and the code for the Pearson's chi-square tests used to evaluate semantic specialization.

## Reproducibility

To ensure full methodological transparency, the statistical analysis can be reproduced directly in the cloud without needing to install R locally. 

1. Click the **"Open in Colab"** badge at the top of this page.
2. The script will open in a temporary Google Colab environment.
3. Click **Runtime > Run all** (or run the cells sequentially). The script is pre-configured to automatically fetch the `.csv` dataset directly from this repository and output the statistical charts and p-values discussed in the paper.

Alternatively, researchers may download the `.csv` and `.ipynb` files to execute the analysis in a local R environment.

## Citation

If you utilize this dataset or methodology in your own research, please cite the repository as follows:

> Putra, D. S. A. (2026). *cross-paradigmatic-metaphorical-mapping* [Data set and source code]. GitHub. https://github.com/DerrySAP/cross-paradigmatic-metaphorical-mapping

## ⚖️ License

This project is licensed under the [MIT License](LICENSE) - see the LICENSE file for details.
