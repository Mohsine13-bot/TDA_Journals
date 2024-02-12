# Topological Analysis of User Logs in OpenEdition Journals Platform

## Overview
This repository contains a Jupyter notebook performing topological analysis on user logs within the OpenEdition Journals platform. The analysis focuses on understanding user navigation paths through a sequence of journal names within the platform. It is inspired by the paper "A Topological Data Analysis of Navigation Paths within Digital Libraries", with the key distinction being the utilization of journal names as sequences instead of themes as in the referenced paper.

## Methodology
The analysis follows these main steps:
1. **Data Preprocessing**: Raw user logs data from the OpenEdition Journals platform is processed and formatted for analysis.
2. **Sequence Generation**: Sequences of journal names are extracted from user logs to represent navigation paths.
3. **Topological Analysis**: Topological data analysis techniques are applied to explore the structure and relationships within the sequences of journal names.
4. **Visualization**: Results of the topological analysis are visualized to aid interpretation and insights.

## Requirements
- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- scikit-learn
- giotto-tda

## Usage
1. Clone the repository to your local machine.
2. Install the required dependencies using pip:
   ```
   pip install -r requirements.txt
   ```
3. Open the Jupyter notebook `tda_journals.ipynb`.
4. Follow the instructions within the notebook to execute each cell and perform the analysis.

## Results
The analysis provides insights into the topological structure of user navigation paths within the OpenEdition Journals platform. This includes identifying frequently visited journal sequences, common patterns in user behavior, and potential clusters or groups of users based on their navigation patterns.