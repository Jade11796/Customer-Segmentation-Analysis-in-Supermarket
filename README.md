# Customer Segmentation Analysis

Customer segmentation analysis for a supermarket chain using unsupervised machine learning techniques. This project identifies distinct customer segments from loyalty card data to enable targeted marketing strategies.

## Overview

This analysis processes a dataset of 2,000 customers collected through loyalty cards, examining demographic variables including age, gender, annual income, education, occupation, and settlement size. Two clustering algorithms (k-Means and Hierarchical) are applied to identify customer segments with similar characteristics.

## Features

- Exploratory data analysis with statistical summaries and visualizations
- Customer segmentation using k-Means clustering
- Customer segmentation using Hierarchical clustering
- Comparative analysis of clustering methods
- Cluster interpretation and profiling
- Data visualization for distribution and relationship analysis

## Dataset

The dataset contains 2,000 customer records with the following variables:

- **ID**: Unique customer identifier
- **Sex**: Gender (Male/Female)
- **Marital Status**: Single/Non-single
- **Age**: Customer age in years
- **Education**: Education level (Other/Unknown, High School, University, Graduate School)
- **Income**: Annual income in US dollars
- **Occupation**: Occupation category (Unemployed/Unskilled, Skilled Employee/Official, Management/Self-employed/Highly Qualified)
- **Settlement Size**: City size (Small City, Mid-sized City, Big City)

## Installation

### Prerequisites

- Python 3.7 or higher
- pip package manager

### Setup

1. Clone the repository:
```bash
git clone https://github.com/yourusername/Customer-Segmentation-Analysis.git
cd Customer-Segmentation-Analysis
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

## Usage

1. Ensure the data file is located in the `data/` directory:
   - `data/data.csv`

2. Open and run the Jupyter notebook:
```bash
jupyter notebook customer_segmentation_analysis.ipynb
```

3. Execute cells sequentially to perform the analysis.

## Methodology

### Exploratory Data Analysis
- Data cleaning and preprocessing
- Summary statistics
- Distribution analysis for all variables
- Correlation analysis between variables

### Clustering Techniques

**k-Means Clustering:**
- Elbow method for optimal cluster number determination
- k-Means algorithm implementation
- Cluster centroid analysis

**Hierarchical Clustering:**
- Agglomerative clustering with Ward linkage
- Dendrogram visualization
- Cluster assignment and analysis

### Comparative Analysis
- Side-by-side comparison of clustering results
- Distribution analysis across clusters
- Visualization of cluster characteristics

## Results

The analysis identifies four distinct customer segments:
1. Skilled Middle-age Single Male
2. Unemployed Middle-age Non-single Female
3. Highly Qualified Middle-age Single Male
4. Skilled Middle-age Non-single Female

Each segment exhibits unique characteristics in terms of demographics, income levels, and purchasing behaviors, enabling targeted marketing strategies.

## Technologies Used

- **Python**: Core programming language
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computing
- **Scikit-learn**: Machine learning algorithms (KMeans, AgglomerativeClustering)
- **Matplotlib**: Data visualization
- **Seaborn**: Statistical data visualization
- **SciPy**: Scientific computing (hierarchical clustering)

## Project Structure

```
Customer-Segmentation-Analysis/
├── data/
│   ├── data.csv
│   └── data legend.csv
├── customer_segmentation_analysis.ipynb
├── requirements.txt
├── README.md
└── .gitignore
```

## License

This project is open source and available for educational and research purposes.
