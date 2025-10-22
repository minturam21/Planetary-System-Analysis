
# Exoplanet Data Analysis

## Description
This project analyzes NASA's Planetary Systems dataset to explore the properties of exoplanets and their host stars. 
It includes data cleaning, visualization, and basic analysis to find patterns and insights about planets and their discovery methods.

## Dataset
- Dataset: NASA Exoplanet Archive – Planetary Systems Table
- Columns included: Planet name, Host star, Radius, Mass, Orbital period, Star temperature, Star radius, Discovery method, System distance
- Source: [NASA Exoplanet Archive](https://exoplanetarchive.ipac.caltech.edu)

## Project Structure
```

cosmic-exoplanet-analysis/
├── data/                 # Raw and cleaned CSV files
│   └── PS_2025.10.22_16.03.59.csv
├── notebooks/            # Jupyter notebook with analysis
│   └── exoplanet_analysis.ipynb
└── README.md             # Project description

````

## Steps to Run
1. Install required libraries:
```bash
   pip install pandas matplotlib seaborn
```

2. Open Jupyter Notebook:

   ```bash
   jupyter notebook
   ```
3. Open `exoplanet_analysis.ipynb` in the `notebooks/` folder.
4. Run the notebook cells step by step to see data loading, cleaning, visualization, and analysis.

## Key Analysis & Insights

* Most planets were discovered by the Transit method.
* Planet radius and mass show a positive correlation.
* Larger stars tend to host larger planets.
* Further analysis can explore habitability or compare planets by orbital period.

