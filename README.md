# Winter in Data Science (WiDS) Assignment 2: Housing Price Prediction

## What's This Project About?
Built a machine learning model to predict house prices in California using data analysis and regression techniques.

## What I Did

### Step 1: Explored the Data
- Loaded the California Housing dataset locally (due to server issues)
- Checked the dataset structure and basic statistics
- Identified which features had the most variation

### Step 2: Visualized the Data
- Made histograms to see how each feature was distributed
- Created box plots to find outliers
- Built a correlation heatmap to understand relationships between features
- Plotted a map showing house locations (longitude vs latitude) colored by price

### Step 3: Feature Engineering
- Removed latitude and longitude (they weren't useful for predicting prices)
- Converted categorical data (ocean_proximity) into numerical format

### Step 4: Applied PCA (Principal Component Analysis)
- Scaled all data first (important because PCA is sensitive to feature scale)
- Reduced data to 2 main components (PC1 and PC2)
- Visualized the compressed data

### Step 5: Built the Model
- Used Multiple Linear Regression
- Split data: 30% for training, 70% for testing
- Trained the model and made predictions

### Step 6: Checked Model Performance
- Calculated R² Score, Mean Absolute Error, and Mean Squared Error
- Plotted predicted vs actual prices
- Analyzed residuals (prediction errors) to see if the model was working well

## Why I Removed Latitude & Longitude
Used correlation analysis to show they had almost zero relationship with house prices, so they weren't helpful for predictions.

