# Movie Performance Analysis with TMDB Data

This repository contains the final project for **Big Data Technology**, focusing on the analysis of movie and TV show performance using data from the [TMDB API](https://developer.themoviedb.org/docs). The project builds a **data ingestion pipeline**, organizes the data into a **relational database**, and explores insights through **Jupyter notebooks** and **Tableau dashboards**.

---

## Repository Contents

- **full_data.zip** – Dataset (stored with Git LFS, ~182 MB).  
- **DATA_EXTRACTION.ipynb** – Notebook for TMDB API extraction.  
- **DATA TRANSFORMATIONS AND CLEANING.ipynb** – Notebook for data cleaning and transformations.  
- **Graphs.ipynb** – Notebook for exploratory data analysis and visualizations.  
- **Movies_database.sql** – PostgreSQL schema and table creation.  
- **Report.pdf** – Full project report with methodology, results, and conclusions.  
- **.gitattributes** – Git LFS configuration.  

---

## Project Overview

- **Objective**: Identify the main factors that drive movie and TV show performance, and provide data-driven insights for decision-making in the film industry.  
- **Approach**:  
  - Data extraction from the TMDB API.  
  - Data cleaning, preprocessing, and transformation.  
  - Database normalization and schema design in PostgreSQL.  
  - Exploratory analysis and visualization of genres, budgets, casting, language, and timing.  
  - Tableau dashboards for interactive insights.  

---

## Key Insights

- **Genre**: Adventure and Sci-Fi dominate revenue, while Thrillers provide consistent ROI.  
- **Runtime**: The optimal movie length lies between 80–120 minutes.  
- **Casting**: Analysis highlights both established stars and emerging low-risk talent.  
- **Language**: Non-English markets (e.g., Korean, Telugu) often outperform in ROI efficiency.  
- **Budget**: Allocation strongly influences revenue but does not guarantee profitability.  

---

## Usage

1. **Clone the repository**  
```bash
   git clone https://github.com/pilarguerreromorales/Movie-Performance-Analysis-with-TMDB-data.git
   cd Movie-Performance-Analysis-with-TMDB-data/big-data-technology
```

2. **Clone the repository** 
The dataset full_data.zip is stored with Git LFS.
Run:

```bash
git lfs install
git lfs pull
```
Then extract full_data.zip inside the big-data-technology/ folder.

3. Open notebooks in Jupyter

 ```bash
jupyter notebook
  ```
Open the relevant .ipynb files to explore extraction, transformation, and analysis steps.

## Dashboards
Interactive dashboards were created in Tableau, covering:

- Genre and story selection
- Timing and runtime analysis
- Financial performance (budget vs ROI)
- Casting and talent performance
- Language strategy

## Authors
- Bernarda Andrade
- Matias Arevalo
- Pilar Guerrero
- Moritz Goebbels
- Tomás Lock
- Allan Stalker
