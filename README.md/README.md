
# DSA 2040A Mid-Semester ETL Project
Student Name: Arlen  
Student ID (last 3): 855  



##  Project Overview

A complete ETL pipeline that extracts, transforms, and loads Breast Cancer dataset CSV files into structured formats for analysis. The project includes data cleaning, enrichment, and structural transformations, followed by loading the processed data into SQLite databases for querying and review.



## ETL Phases

- etl_extract.ipynb: Loads, previews, and inspects raw and incremental data. Observes data structure, missing values, and duplicates.
- etl_transform.ipynb: Cleans, enriches, and restructures data with at least 4 meaningful transformations, including handling missing values, replacing diagnosis codes, removing duplicates, and adding calculated fields.
- etl_load.ipynb: Loads transformed data into SQLite databases and verifies successful storage by querying the tables.



## Tools Used

- Python  
- Pandas  
- SQLite3  
- Google Colab  


##  How to Run the Project

1. Upload `raw_data.csv` and `incremental_data.csv` into the `/content/` directory in Google Colab.
2. Open and run etl_extract.ipynb to load, inspect, and document observations about the data.
3. Open and run etl_transform.ipynb to perform all required data transformations and save the processed files.
4. Open and run etl_load.ipynb to load the transformed data into SQLite databases and preview the results.
5. Check the `/content/` directory in Colab for the generated `.db` files and data preview outputs.



##  Project Structure

```
ETL_Midterm_Arlen_855/
├── data/
│   ├── raw_data.csv
│   └── incremental_data.csv
├── transformed/
│   ├── transformed_full.csv
│   └── transformed_incremental.csv
├── loaded/
│   ├── full_data.db
│   └── incremental_data.db
├── etl_extract.ipynb
├── etl_transform.ipynb
├── etl_load.ipynb
├── README.md
└── .gitignore
```

