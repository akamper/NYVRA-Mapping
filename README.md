# NYVRA-Mapping

**A state law enacted in 2022, the NYVRA (New York Election Law section 17-200) strengthens the voting rights of all New Yorkers, including historically marginalized and disenfranchised communities. The law requires the Office of the Attorney General (OAG) to play a role in enforcing these rights.** The NYVRA removes barriers and protects fair, open, and equal access to the ballot box for all eligible New Yorkers.

This repository contains code and resources for analyzing and visualizing election data in New York City, with a focus on accessibility and equity as mandated by the NYVRA. The analysis aims to identify potential barriers to voting by examining the proximity of poll sites to public transportation and residential areas, and considering language diversity across neighborhoods.

## Features

- **Data Sources:** 
  - Past 4 U.S. Presidential Election results
  - NYC poll sites
  - NYC subway entrances and exits
  - Residential buildings in NYC
  - Household language data

- **Analyses and Visualizations:**
  - Election results by neighborhood and precinct.
  - Accessibility of poll sites based on distance from subway stations.
  - Accessibility of poll sites relative to residential buildings.
  - Examination of language diversity and its potential impact on accessibility to poll sites.

## How to Run the Code

### 1. Run on Google Colab
To simplify execution, a Google Colab notebook is available, allowing you to run the code on the cloud without setting up a local environment. Click the link below to open the notebook:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/akamper/NYVRA-Mapping/blob/main/NYVRA_Mapping.ipynb)

### 2. Run Locally
To run the codebase locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/akamper/NYVRA-Mapping.git
   cd NYVRA-Mapping
   ```

2. **Create and activate a virtual environment (optional but recommended):**
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. **Install required Python packages:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the scripts:**
   Execute the Python scripts in the `src` directory to generate analyses and visualizations.
   ```bash
   python src/analysis.py
   ```


**By examining election accessibility through the lens of transportation, residential proximity, and language diversity, this project seeks to support the goals of the NYVRA in ensuring fair and equal access to the voting process for all New Yorkers.**
