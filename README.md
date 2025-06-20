# Eskalate ML/Data Science Interview Project

- **Candidate**: Adane Moges
- **Date**: June 20, 2025  
- **Project Title**: Airbnb Data Analysis for Host and Pricing Insights  

## Overview

This project is part of the Eskalate ML/Data Science Interview, showcasing data cleaning, transformation, analysis, and machine learning skills using Airbnb datasets (`listings_2_reduced.csv` and `reviews_2_reduced.csv`). The tasks are implemented in a Google Colab notebook, structured into two main parts and a bonus challenge, with interactive visualizations and robust error handling to demonstrate technical proficiency and analytical rigor.

The project addresses four key objectives:
1. **Challenge 1: Superhost Pricing Gap by Neighborhood** – Identify the neighborhood with the largest median price difference between Superhost and non-Superhost listings.
2. **Challenge 2: Correlation Between Review Scores and Price** – Determine which review score metric is most correlated with listing price.
3. **Challenge 3: Room Type Analysis – Price vs. Rating** – Analyze how average price and rating vary by room type.
4. **Bonus Challenge: Predict Superhost Status** – Build a machine learning model to predict Superhost status from listing features.

## Repository Contents

- **Eskalate_ML_Interview_[YourName].ipynb**: The main Google Colab notebook containing all code, Markdown explanations, and interactive visualizations.
- **README.md**: This file, providing project overview and instructions.

## Datasets

The analysis uses two datasets, loaded directly from Google Cloud Storage URLs:
- **Listings**: `https://storage.googleapis.com/public-data-337819/listings%202%20reduced.csv` (~87,946 rows, containing listing details like price, room type, and Superhost status).
- **Reviews**: `https://storage.googleapis.com/public-data-337819/reviews%202%20reduced.csv` (containing review details linked to listings).

## Notebook Structure

The Colab notebook is organized as follows:
1. **Introduction**: Overview of the project, candidate details, and objectives.
2. **Part 1: Short Answer Questions**:
3. **Dataset Loading**:
4. **Part 2: Coding Challenges**:
   - **Challenge 1**: Cleans `price` and `host_is_superhost`, computes median price differences by neighborhood, and visualizes results with an interactive dropdown for top N neighborhoods.
   - **Challenge 2**: Calculates Pearson correlations between review scores and price, with an interactive dropdown to highlight metrics in a bar plot.
   - **Challenge 3**: Computes average price and rating by room type, visualized with an interactive scatter plot.
   - **Bonus Challenge**: Trains a Logistic Regression model to predict `host_is_superhost`, with diagnostics for class imbalance, interactive metric selection, confusion matrix, and feature importance plot.


## Key Features

- **Interactive Visualizations**: Uses `ipywidgets` for dropdowns to dynamically explore results (e.g., top neighborhoods, review score correlations, room types, and model metrics).
- **Robust Error Handling**: Try-except blocks and diagnostics ensure the notebook handles missing data, incorrect formats, or single-class issues gracefully.
- **Data Cleaning and Transformation**: Extensive preprocessing (e.g., standardizing `price`, imputing missing values, harmonizing categoricals) to ensure data quality.
- **Professional Presentation**: Collapsible Markdown sections with emojis (📊, 🚀) for clarity and engagement.

## Setup and Running Instructions

### Option 1: Run in Google Colab
1. Access the notebook via the shared Colab link: [Insert Colab link here, set to "Anyone with the link can view"].
2. Run all cells sequentially:
   - Start with the dataset loading cell and click the "Load Datasets" button.
   - Proceed through Part 1 (short answers) and Part 2 (challenges).
   - Interact with dropdown widgets to explore visualizations.
3. Ensure an internet connection to load datasets from the provided URLs.

### Option 2: Download and Run Locally
1. Clone this repository or download `Eskalate_ML_Interview_[YourName].ipynb`.
2. Upload the notebook to Google Colab or open it in Jupyter Notebook.
3. Install required Python libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn ipywidgets
4. Run the notebook cells as described above.

### Option 3: View Static Output
- View the notebook’s rendered output via nbviewer by uploading the `.ipynb` file or providing the GitHub URL.
- Note: Interactive widgets require running in Colab or Jupyter for full functionality.
### Troubleshooting
- **Dataset Loading Errors:** Ensure the URLs are accessible. If they fail, check network connectivity or contact the interview organizers for alternative dataset access.


### Submission Details
- **Google Colab Link**: https://colab.research.google.com/drive/1otmIM0W-qT-fRaZqb47P04fLW7fm5QyS?usp=sharing
- **GitHub Repository**: https://github.com/habeshaethiopia/Eskalate-ML-Interview_Adane
- **Contact**: Adane Moges (adanemoges6@gmail.com)

Thank you for reviewing my work! I’m excited to showcase my data science skills and look forward to your feedback. 🚀