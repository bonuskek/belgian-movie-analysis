# Belgian Movie Analysis

## Project Overview
This project aims to analyze the Belgian movie industry over the last three decades, focusing on worldwide recognition, genre popularity, and the impact of multilingualism.

## Data Sources
- **IMDB**: Scraped data on Belgian movies including awards, nominations, genres, directors, languages, and IMDb scores.

## ETL Process
- **Extraction**: Data was scraped from IMDB using Octoparse.
- **Transformation**: Data cleaning, normalization, and transformation were performed using pandas.
- **Loading**: The cleaned data was loaded into a SQL Server database.

## Analysis
The analysis was conducted using Python and Power BI, focusing on:
- Trends in awarded and nominated Belgian movies.
- Popular genres and directors.
- Language preferences and their impact on success.

## Visualizations
Visualizations were created in Power BI to provide insights into the analysis.

## How to Run
1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/belgian-movie-analysis.git
    cd belgian-movie-analysis
    ```
2. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```
3. **Run the ETL script**:
    ```bash
    python scripts/etl.py
    ```
4. **Open the Jupyter notebooks**:
    ```bash
    jupyter notebook notebooks/data_cleaning.ipynb
    ```

## Requirements
- Python 3.8+
- pandas
- numpy
- scikit-learn
- sqlalchemy
- pyodbc
- jupyter

