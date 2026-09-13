# BT Akademi - Data Science Training

## Table of Contents

- [Project Overview](#project-overview)
- [Training Topics](#training-topics)
- [Projects and Assignments](#projects-and-assignments)
- [Data Analysis and Visualization](#data-analysis-and-visualization)
- [Machine Learning](#machine-learning)
- [Deep Learning](#deep-learning)
- [Web Scraping and Data Collection](#web-scraping-and-data-collection)
- [Data Sources](#data-sources)
- [Required Dependencies](#required-dependencies)
- [Project Structure](#project-structure)
- [How to Run](#how-to-run)
- [Notes](#notes)
- [Author](#author)

---

## Project Overview

This repository contains the **course exercises, assignments, applications, and project studies** I completed during my Data Science training at **BT Akademi**.

Throughout the training, I worked with Python and various data science libraries to gain practical experience in data analysis, data visualization, machine learning, deep learning, web scraping, and working with different data sources.

The repository brings together the work completed throughout the training process, including individual exercises, datasets, Jupyter Notebooks, assignments, and project-based applications.

### Main Areas Covered

- Data Analysis
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Data Visualization
- Regression
- Classification
- Clustering
- Machine Learning
- Deep Learning
- Artificial Neural Networks
- Web Scraping
- Asynchronous Data Collection
- Working with Kaggle datasets
- Working with Hugging Face datasets

---

## Training Topics

The training covered both theoretical concepts and practical implementations.

### Data Science

- Data loading and inspection
- Data cleaning
- Data preprocessing
- Exploratory Data Analysis
- Statistical analysis
- Feature analysis
- Data visualization
- Working with CSV and JSON files

### Machine Learning

- Linear Regression
- Support Vector Machines (SVM)
- K-Means Clustering
- XGBoost
- Model training and testing
- Model evaluation
- Working with training and test datasets

### Deep Learning

- Artificial Neural Networks
- Deep Learning
- Model training
- Model evaluation
- Saving and loading trained models
- TensorFlow and Keras

### Data Collection

- Web scraping
- HTTP requests
- HTML parsing
- Parallel and asynchronous data collection
- Working with online datasets
- Kaggle and Hugging Face datasets

---

## Projects and Assignments

This repository contains several studies completed during the training.

### Cigarette and Mortality Rate Analysis

The `sigara_olumOranı` folder contains analysis and machine learning studies based on cigarette consumption and mortality rate data.

The studies include:

- Exploratory data analysis
- Data visualization
- Statistical examination
- Data interpretation
- K-Means clustering

Related notebooks:

- `sigara_analysis.ipynb`
- `sigara_olum_orani_analysis.ipynb`
- `sigara_olum_orani_kmeans.ipynb`

---

### Renault Clio Data Analysis

The `reno_clio` folder contains the Renault Clio dataset used during the training.

The dataset was used for data analysis and machine learning exercises.

---

### Legal Question-Answer Data Collection

The `hukuksorucevap` folder contains studies focused on collecting and preparing legal question-answer data.

The project includes:

- Web data collection
- HTML parsing
- Data extraction
- Question-answer dataset creation
- Asynchronous data collection

Related notebooks:

- `vericek_sorucevap.ipynb`
- `vericek_sorucevap_paralel.ipynb`

---

### IETT and Deep Learning Studies

The `iett` folder contains studies related to IETT data and deep learning applications.

The folder includes:

- Deep learning notebooks
- IETT-related applications
- HTML files
- Trained neural network models

The trained models are stored in:

- `sign_language_model.h5`
- `sign_language_model.keras`

---

### Trendyol Data Study

The `trendyol_.ipynb` notebook contains a data-related study using Trendyol data.

The study focuses on working with collected data and applying data analysis techniques.

---

### Kaggle and Hugging Face Data

The `veri_kullanma_kaggle_hf.ipynb` notebook contains exercises related to accessing and using datasets from external data platforms.

The study includes working with:

- Kaggle datasets
- Hugging Face datasets

---

## Data Analysis and Visualization

Data analysis is an important part of the studies included in this repository.

The datasets are examined using techniques such as:

- Descriptive statistics
- Missing value analysis
- Data filtering
- Grouping and aggregation
- Correlation analysis
- Feature examination
- Distribution analysis

### Visualization Libraries

- Matplotlib
- Seaborn
- Plotly

Different visualization techniques include:

- Histograms
- Scatter plots
- Box plots
- Distribution plots
- Correlation visualizations
- Interactive visualizations

---

## Machine Learning

Several machine learning algorithms were implemented during the training.

### Linear Regression

Linear Regression was studied for predicting continuous numerical values and understanding the relationship between independent and dependent variables.

Notebook:

`lineer_regresyon.ipynb`

### Support Vector Machine

Support Vector Machine (SVM) was studied as a supervised machine learning algorithm for classification tasks.

Notebook:

`svm.ipynb`

### K-Means Clustering

K-Means was used to explore unsupervised learning and group observations based on their similarities.

Notebooks:

- `kmeans.ipynb`
- `sigara_olum_orani_kmeans.ipynb`

### XGBoost

XGBoost was studied as a gradient boosting algorithm for machine learning prediction tasks.

Notebook:

`xgboost.ipynb`

### Artificial Neural Networks

Artificial Neural Networks were studied as part of the machine learning and deep learning training.

Notebook:

`yapay_sinir_agi.ipynb`

---

## Deep Learning

Deep learning studies were performed using **TensorFlow and Keras**.

The studies include:

- Neural network architecture
- Model creation
- Model training
- Model evaluation
- Saving trained models
- Loading trained models

The `iett` folder contains trained model files in both H5 and Keras formats.

---

## Web Scraping and Data Collection

Web scraping and automated data collection were also covered during the training.

The following technologies were used:

- Requests
- BeautifulSoup
- aiohttp
- asyncio

These tools were used to retrieve, parse, and process data from web pages.

Asynchronous approaches were also explored to improve the efficiency of data collection processes.

---

## Data Sources

Different data sources and formats were used throughout the training.

These include:

- CSV files
- JSON files
- Web-based data
- Kaggle datasets
- Hugging Face datasets

The repository contains both the notebooks used for analysis and several of the datasets used during the exercises.

---

## Required Dependencies

The main Python libraries used throughout the repository are:

- Python 3.8+
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Plotly
- Scikit-learn
- XGBoost
- TensorFlow
- Requests
- BeautifulSoup4
- aiohttp
- KaggleHub
- Hugging Face Datasets

You can install the required packages with:

```bash
pip install numpy pandas matplotlib seaborn plotly scikit-learn xgboost tensorflow requests beautifulsoup4 aiohttp kagglehub datasets
```

---

## Project Structure

```text
BT_AKADEMI_VERI_BILIMI_EGITIMI/
│
├── firebase_javascript/
│
├── hukuksorucevap/
│   ├── hukuksorucevap.csv
│   ├── vericek_sorucevap.ipynb
│   └── vericek_sorucevap_paralel.ipynb
│
├── iett/
│   ├── deep_learning.ipynb
│   ├── get.html
│   ├── iett.ipynb
│   ├── post.html
│   ├── sign_language_model.h5
│   └── sign_language_model.keras
│
├── reno_clio/
│   └── reno_clio.csv
│
├── sigara_olumOranı/
│   ├── sigara_analysis.ipynb
│   ├── sigara_olum_orani_analysis.ipynb
│   ├── sigara_olum_orani_kmeans.ipynb
│   └── sigara_olumOranı_dataset.csv
│
├── data.json
├── df.csv
├── df_etiketli.csv
├── hafta_2.1.ipynb
├── kmeans.ipynb
├── lineer_regresyon.ipynb
├── svm.ipynb
├── trendyol_.ipynb
├── veri_kullanma_kaggle_hf.ipynb
├── xgboost.ipynb
├── yapay_sinir_agi.ipynb
├── .gitignore
└── README.md
```

---

## How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/dilberkrtl/BT_AKADEMI_VERI_BILIMI_EGITIMI.git
```

### 2. Navigate to the Project Directory

```bash
cd BT_AKADEMI_VERI_BILIMI_EGITIMI
```

### 3. Install the Required Libraries

```bash
pip install numpy pandas matplotlib seaborn plotly scikit-learn xgboost tensorflow requests beautifulsoup4 aiohttp kagglehub datasets
```

### 4. Start Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook you want to examine and run the cells sequentially.

---

## Notes

This repository represents my learning process during the **BT Akademi Data Science Training**.

The notebooks and projects are composed of:

- Course exercises
- Assignments
- Data analysis studies
- Machine learning applications
- Deep learning studies
- Data collection exercises
- Project-based applications

The repository is intended to document my practical experience and development throughout the training.

---

## Author

**Dilber Kartal**

Data Science Training - BT Akademi
