# Gene Expression Analysis using Python

## Overview

This project performs **differential gene expression analysis** using a small RNA-Seq dataset. It identifies differentially expressed genes (DEGs) between **control** and **treated** samples, computes statistical significance, and visualizes the results using a **Volcano Plot**.

## Features

- **Loads gene expression data** (simulated dataset for demonstration).
- **Computes mean expression levels** for control and treated groups.
- **Performs t-test** to identify differentially expressed genes.
- **Calculates Log2 Fold Change (LFC)**.
- **Generates a Volcano Plot** to visualize significant genes.
- **Outputs results to CSV**.

## Installation

To run this project, you need **Python 3.x** and the following libraries:

```bash
pip install pandas numpy matplotlib seaborn scipy
```

## Usage

Run the Python script:

```bash
python gene_expression_analysis.py
```

OR, if using Jupyter Notebook:

```python
%run gene_expression_analysis.py
```

## Example Output

- **CSV Output:** `gene_expression_results.csv`
- **Visualization:**
  - Volcano Plot showing significantly differentially expressed genes.

## Repository Structure

```
GoLicense
```

This project is open-source and licensed under the **MIT License**.
