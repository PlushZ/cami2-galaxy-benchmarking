cami2-galaxy-benchmarking
================

# Usage

## Requirements

- [conda](https://conda.io/miniconda.html)
- Create the conda environment:

    ```
    $ conda env create -f environment.yaml
    ```

## Benchmarking analysis of assembly results

- Launch the conda environment

    ```
    $ source activate galaxy-training-material-stats
    ```

- Generate a Personal access tokens on GitHub (in Setting)
- Launch Jupyter

    ```
    $ jupyter notebook
    ```

- Open [http://localhost:8888](http://localhost:8888)
- Open:
    - [`src/quast-results-analysis.ipynb` Notebook](http://localhost:8888/notebooks/src/quast-results-analysis.ipynb) to analyse QUAST results
