# Customer Reviews Analysis

## Overview
This project performs a comprehensive analysis of customer reviews to extract insights and visualize data distributions. The analysis includes data cleaning, exploratory analysis, and interactive visualization using Python libraries such as Pandas, Matplotlib, Seaborn, and ipywidgets.

## Dataset

`Raw_Reviews.csv` 
`reviews_with_sentiment.csv`

## Features
- Data cleaning and preprocessing
- Visualizing the distribution of age and ratings
- Counting the frequency of product types and review titles
- Interactive n-gram analysis to explore common phrases in reviews

## Installation
To set up the necessary environment:
1. Clone the repository or download the files.
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3.	Ensure that you have Jupyter Notebook or JupyterLab installed to run the notebook.

## Usage

Open the notebook in Jupyter and run the cells sequentially.

## Interactive Analysis
In the Table of Content section of the `notebook.ipynb`, click on the `UI-ipywidgets for N-gram parameter`. This section can be executed seperately from other parts of the notebook.

Widgets are used for interactive analysis:
- Dropdown to select product types.
- Slider to select n-gram sizes.
- Button to generate n-grams, which displays the top n-grams for the selected settings.
