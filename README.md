![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

---

# King County House Sale Price Prediction

## Overview
This project aims to analyze and predict the sale prices of houses in King County, including Seattle, spanning from May 2014 to May 2015. The dataset consists of various attributes related to the houses, such as number of bedrooms, bathrooms, square footage, and more. Using Python, we perform exploratory data analysis (EDA), model building, and predictive analytics to understand the factors influencing house prices.

### Mission
- **Objective**: Delve into a real estate dataset and predict house sale prices based on various factors.
- **Tools and Libraries**: Python, Pandas, Matplotlib, Seaborn, Scikit-learn, Jupyter Notebooks.
- **Outcome**: Build a machine learning model to predict house sale prices and uncover key features that affect pricing in the real estate market.

## Dataset Information
The dataset consists of 21 columns related to house sales over a one-year period (from May 2014 to May 2015):

| Column Name         | Description                                                      |
|---------------------|------------------------------------------------------------------|
| id                  | Unique identifier for each house                                |
| date                | Date of the house sale                                          |
| price               | Sale price of the house (target variable)                       |
| bedrooms            | Number of bedrooms                                               |
| bathrooms           | Number of bathrooms                                             |
| sqft_living         | Square footage of the living space                              |
| sqft_lot            | Square footage of the land space                                |
| floors              | Number of floors in the house                                   |
| waterfront          | Whether the house has a waterfront view                         |
| view                | Number of times the house has been viewed                       |
| condition           | Condition rating of the house                                   |
| grade               | Grade rating based on the King County grading system            |
| sqft_above          | Square footage of the house above the basement                  |
| sqft_basement       | Square footage of the basement                                  |
| yr_built            | Year the house was built                                        |
| yr_renovated        | Year the house was renovated (if applicable)                    |
| zipcode             | ZIP code of the house                                           |
| lat                 | Latitude of the house                                           |
| long                | Longitude of the house                                          |
| sqft_living15       | Square footage of living space for the 15 nearest neighbors in 2015 |
| sqft_lot15          | Square footage of land space for the 15 nearest neighbors in 2015 |
  
The target variable for prediction is the **price** of the house.

### Key Focus
- Understand the impact of different features on house prices.
- Analyze properties valued at $650K and above for deeper insights.

## Project Timeline

### Day 1 (Wednesday): Introduction and Data Loading
- **Tasks**: Download the dataset, load it into Python, and perform initial exploration and visualization to understand the data.

### Day 2 (Thursday): Analysis and Model Building
- **Tasks**: Perform deeper data analysis, clean the data, handle missing values, and start building a machine learning model to predict house prices.

### Day 3 (Friday): Finalization and Presentation
- **Tasks**: Refine the model, evaluate its performance, prepare visualizations and explanations, and compile a mini-presentation summarizing the machine learning process.

## Deliverables

- **Jupyter Notebook**: The main file where the analysis and model for predicting house sales prices are implemented.
- **Mini-Presentation**: A summary of the machine learning process, including key insights and findings from the analysis.
- **README File**: This file, explaining the steps and decisions made during the project.

### Extra Rubric
- A comprehensive presentation and in-depth exploratory data analysis (EDA) will be considered for bonus points.

## Setup and Installation

### Requirements
To run the notebook, you will need the following libraries:
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Scikit-learn

You can install the required libraries using the following command:
```bash
pip install -r requirements.txt
```

### Running the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/Edu-Martinez-91/king-county-house-prices.git
   ```
2. Navigate to the project directory:
   ```bash
   cd king-county-house-prices
   ```
3. Open the Jupyter notebook and run the analysis:
   ```bash
   jupyter notebook
   ```

## Acknowledgements

- This project is inspired by real-world real estate analysis and aims to enhance data analysis and machine learning skills in the domain of real estate finance.
- Thanks to King County for providing the dataset for analysis.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

