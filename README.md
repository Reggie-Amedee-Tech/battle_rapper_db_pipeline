## Battle Rapper DB Pipeline
An automated end-to-end ETL pipeline designed to programmatically ingest, transform, and store comprehensive data on battle rappers. This project streamlines the process of gathering performance metrics, battle history, and artist details from web sources into a structured database for deep-dive analytics.

## 🚀 Overview
This repository contains a robust data engineering solution that scrapes over 6,000 records from VerseTracker to build a centralized repository of battle rap statistics. By automating the ingestion and cleaning process, this pipeline provides a clean dataset ready for architectural analysis or data science applications.

## 🏗️ Architecture
The pipeline follows a standard ETL (Extract, Transform, Load) workflow:

**Extract:** Programmatically scrapes detailed rapper data and battle records using Python and BeautifulSoup.

**Transform:** Utilizes Pandas and NumPy to clean raw HTML data, handle missing values, and standardize naming conventions and statistics.

**Load:** Structures the processed data into a relational format suitable for SQL-based environments or cloud warehouses.

## 🛠️ Tech Stack
**Language:** Python

**Libraries:** BeautifulSoup4 (Web Scraping), Pandas & NumPy (Data Manipulation)

**Environment:** Jupyter Notebooks

Infrastructure: Architected for integration with SQL (PostgreSQL/MySQL) or Google BigQuery.

## 📊 Key Features
Massive Data Ingestion: Capable of handling 6,000+ unique records.

Automated Data Cleaning: Scripts to handle common web scraping artifacts and inconsistent data formatting.

Scalable Design: The modular nature of the notebook allows for easy updates to the scraping logic or target database.

## 📂 Project Structure
Plaintext
├── BattleRapperDBPipelineComplete.ipynb  # Main ETL logic and execution
├── README.md                             # Project documentation
└── [Data/Output Folders]                 # Generated CSVs or database exports
## ⚙️ Getting Started
Clone the repository:

## Bash 1)
git clone https://github.com/Reggie-Amedee-Tech/battle_rapper_db_pipeline.git
Install dependencies:

## Bash 2)
pip install pandas numpy beautifulsoup4 requests
Run the Pipeline:
Open BattleRapperDBPipelineComplete.ipynb in your preferred Jupyter environment and run the cells to initiate the extraction and transformation process.

## 📝 License
Distributed under the MIT License. See LICENSE for more information.
