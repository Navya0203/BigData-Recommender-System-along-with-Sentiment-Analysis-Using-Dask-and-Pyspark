# Advanced E-Commerce Recommendation System

## Overview

This repository develops an advanced recommendation system to enhance the e-commerce shopping experience by automating product suggestions and analyzing user preferences through machine learning techniques.

## Repository Structure

### `alternative_implementations`
Contains notebooks with methodologies evaluated but not selected for the final implementation.

### `final_implementation`
This directory houses the core notebooks essential for understanding and replicating the recommendation system:
- **Language Detection**: `Final_BigData_Language Detection.ipynb`
- **Sentiment Analysis**: `Final_Dask_Sentiment_Analysis-2.ipynb`
- **Exploratory Data Analysis**: `Final_EDA_BigData.ipynb`
- **Recommendation System**: `Final_RecommenderSystem_SVD.ipynb`

## Technologies

Utilizes Python and Jupyter Notebook, with libraries including Pandas, Numpy, Matplotlib, Seaborn, Scikit-learn, and Dask.

## Getting Started

To set up this project locally, run the following commands:

```bash
git clone https://github.com/yourusername/your-repository-name.git
cd your-repository-name
pip install -r requirements.txt

```

### Setting Up the Data

Prepare the dataset:
- **Download the necessary data files.**
  https://www.kaggle.com/datasets/cynthiarempel/amazon-us-customer-reviews-dataset?select=amazon_reviews_us_Baby_v1_00.tsv
- **Place them into the archive/ folder on your Google Drive Home directory**

### Running the Notebooks
Navigate to the final_implementation directory:
```bash
cd final_implementation
```
#### Execute the notebooks:
**Data Visualization and EDA**: Open and run `Final_EDA_BigData.ipynb` to visualize and explore the data.
**Language Detection**: Continue with `Final_BigData_Language Detection.ipynb` to detect the language of the reviews and you will have an output file in Big Data Project/ named language.parquet/
**Sentiment Analysis**: Proceed with Final_Dask_Sentiment_Analysis-2.ipynb for analyzing sentiments using Dask and you will have an output file in Big Data Project/ named senti.parquet
**Recommendation System**: Finish by running Final_RecommenderSystem_SVD.ipynb to see how the SVD-based recommender system performs.
