# Genome Information Analysis Project

## Overview
This project provides an analysis of various genomic datasets, focusing on comparing genome size and GC content across different organism types, including Eukaryotes, Prokaryotes, and Viruses. The project involves loading and exploring these datasets, performing statistical and visual analyses, and interpreting key biological findings.

## Project Structure
- **`Genome_Analysis_Project.ipynb`**: The main Jupyter Notebook file containing all data loading, processing, visualization, and analysis code.
- **`data/`**: A folder containing all CSV files for different genomic datasets:
  - `eukaryotes.csv`
  - `genomes.csv`
  - `organelles.csv`
  - `plasmids.csv`
  - `prokaryotes.csv`
  - `viruses.csv`

## Datasets
The datasets include information about different types of organisms and their genomic properties:
- **Eukaryotes**: Higher organisms with a complex cell structure.
- **Prokaryotes**: Simple, unicellular organisms such as bacteria.
- **Viruses**: Small infectious agents that replicate only inside living cells.

Each dataset provides various features, including:
- **Organism Name**
- **Organism Group** (Eukaryote, Prokaryote, or Virus)
- **Genome Size (Mb)**
- **GC Content (%)**

## Analysis Steps
1. **Data Loading**: Loaded and cleaned the datasets to prepare for analysis.
2. **Exploratory Data Analysis**: Explored genome size and GC content distributions.
3. **Visualization**: Used histograms, box plots, scatter plots, and heatmaps to compare genome characteristics across different organism types.
4. **Statistical Tests**: Performed an ANOVA test to analyze differences in GC content across organism types.

## Key Findings
- **Genome Size Comparison**: Eukaryotes generally have larger genomes than Prokaryotes and Viruses.
- **GC Content Variability**: Prokaryotes showed a higher median GC content and broader variability in GC content compared to other types.
- **Correlation Analysis**: Weak correlation observed between genome size and GC content.
- **Statistical Significance**: ANOVA results confirmed statistically significant differences in GC content among organism types.

## Requirements
The following libraries are required to run the project:
- `pandas`
- `matplotlib`
- `seaborn`
- `scipy`

## Running the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/username/Genome-Information.git
