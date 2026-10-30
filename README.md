# GEX BCR Integration

This repository contains code and analysis pipelines for single-cell transcriptomic and B cell receptor (BCR) profiling of publicly available data. The code is primarily organized as R Markdown (RMD) notebooks, with supporting R, Python, and shell scripts. You can convert RMD notebooks to R scripts using `knitr::purl()`.

The R package [athanor](https://github.com/eba28/athanor) was developed and used by the authors to do the main part of the analysis.

Please cite [Cell-level integration of gene expression and B cell receptor data captures complementary B cell information](https://www.biorxiv.org/content/10.64898/2026.10.16.759689v1). Data analyzed in the paper is publicly available on GEO ([Diabetes Nicholas (GSE270142)](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE270142), [Lupus Siu (GSE193869)](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE193869)).

For questions or comments, contact the Kleinstein Lab at Yale University or open an issue on GitHub.

*The full code will be made available upon journal publication.*

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/Kleinstein-Lab/gex-bcr-integration.git
   cd gex-bcr-integration
   ```
2. Review the README for environment setup and pipeline instructions.
	- A lot of details were included within the notebooks.
	- *primary_analysis/style.css* is just included to make the HTML files prettier; it isn't necessary.
3. Most analyses require R (≥3.6). Some may involve Python (≥3.7).