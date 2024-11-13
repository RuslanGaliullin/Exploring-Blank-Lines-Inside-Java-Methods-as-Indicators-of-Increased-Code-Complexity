[![DOI](https://zenodo.org/badge/887105764.svg)](https://zenodo.org/badge/latestdoi/887105764)
# Exploring-Blank-Lines-Inside-Java-Methods-as-Indicators-of-Increased-Code-Complexity

## Project Structure

- **`/cam`** — This directory contains a script used to collect methods and metrics related to code complexity. It includes tests and usage instructions. This folder is a modified fork of the [cam-0.9.3](https://github.com/yegor256/cam) repository, tailored for method-specific data collection.

- **`/aggregated_data_for_paper`** — This directory holds pre-collected, compressed data used in the accompanying paper.

- **`main.ipynb`** — A Jupyter notebook used for data analysis.

## Steps to Reproduce the Results

0. **[Optional] Regenerate the Dataset**:  
   To recreate the dataset of repositories, methods, and their associated metrics from scratch, follow the instructions in the `README.md` file located in the script directory. Once generated, copy the resulting dataset into a folder at the same level as `main.ipynb`.

1. **Download the Data**:  
   Download the pre-collected metrics [data.zip](https://github.com/RuslanGaliullin/Blank-Lines-as-Indicators-of-Increased-Code-Complexity/releases/download/0.0.1/data.zip) and unzip it into a folder at the same level as `main.ipynb`.

2. **Set Up Python Environment**:  
   Install Python version 3.10 or above and create a virtual environment called `.venv`:
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```

3. **Install Required Packages**:  
   Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Jupyter Notebook**:  
   Launch Jupyter Notebook and open `main.ipynb` to begin the analysis.

## How to cite this work
tbd. https://zenodo.org/doi/
