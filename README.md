# PM2.5 Air Quality Analysis & Machine Learning Classification (Indiana, 2025) 

Part of a growing portfolio in environmental data analysis, scientific computing, and introductory machine learning using Python.
________________________________________

## Project Overview

This project analyses EPA PM2.5 air pollution data from Indiana (2025) using Python, pandas, matplotlib, and scikit-learn.

The project began as a traditional environmental data analysis pipeline focused on:

•	data cleaning
•	statistical analysis
•	anomaly detection
•	visualisation

It was later expanded into a supervised machine learning classification system using logistic regression.

The workflow now includes:

•	Data cleaning and validation
•	Statistical analysis
•	Visualisation
•	Anomaly detection
•	Feature extraction
•	Train/test dataset splitting
•	Logistic regression classification
•	Confusion matrix evaluation
•	Probability-based prediction analysis
________________________________________

## Key Learning Goals

This project was designed to explore:

•	environmental data analysis workflows
•	statistical reasoning
•	anomaly detection
•	machine learning classification
•	probabilistic prediction systems
•	model evaluation techniques

It also serves as an introduction to:

•	supervised learning
•	classification pipelines
•	ML workflow structure
•	evaluation metrics
________________________________________

## Features

### Environmental Data Analysis

•	Load and clean EPA air quality data
•	Handle missing and invalid values
•	Compute:
o   	average PM2.5 levels
o   	standard deviation
o   	maximum and minimum values
•	Detect extreme pollution anomalies
•	Generate visualisations using matplotlib
•	Export results to JSON and CSV
•	Log pipeline operations and errors
________________________________________

### Machine Learning Classification

The project now includes a logistic regression classification pipeline that predicts whether PM2.5 levels are:

•	Safe (0)
•	Unsafe (1)

using a threshold-based classification system.

#### ML workflow includes:

•	feature extraction
•	label generation
•	NumPy array conversion
•	matrix reshaping for ML compatibility
•	train/test splitting
•	logistic regression training
•	probability prediction
•	confusion matrix evaluation
•	classification accuracy analysis
________________________________________

## Dataset

The dataset contains EPA PM2.5 measurements for monitoring sites across Indiana during 2025.

#### Columns used:

•	Date
•	Site ID
•	Daily Mean PM2.5 Concentration
________________________________________

## Statistical Analysis

The project computes:

•	mean PM2.5 concentration
•	sample standard deviation
•	maximum and minimum measurements
•	extreme anomalies using standard deviation thresholds 

Extreme events are identified when PM2.5 values exceed statistically unusual ranges.
________________________________________ 

## Machine Learning Classification

### Classification Goal

The ML component converts continuous PM2.5 values into categorical labels:

#### PM2.5 Value	Classification

≤ 35 µg/m³	Safe
> 35 µg/m³	Unsafe

The logistic regression model then learns the probability that a PM2.5 measurement belongs to the unsafe category.
________________________________________

## Model Evaluation

The classification system is evaluated using:

•	accuracy score
•	confusion matrix
•	precision
•	recall
•	F1-score

The project also visualises:

•	classification outputs
•	logistic probability curves
•	decision boundary behaviour
________________________________________

## Key Findings

### Environmental Analysis

•	Average PM2.5 levels vary across monitoring sites
•	Most sites remain relatively stable throughout the year
•	Extreme pollution events are rare and concentrated at a small number of sites
•	Site 180890022 showed several unusually high PM2.5 spikes

#### Highest observed PM2.5 value:

143.7 µg/m³
________________________________________

### Machine Learning Findings

•	Logistic regression successfully separated safe vs unsafe pollution categories
•	Most PM2.5 measurements fell within the safe category
•	The classifier demonstrated strong performance on held-back test data
•	Probability outputs provided insight into uncertainty near the classification threshold

The project also demonstrated how classification differs fundamentally from regression:

•	regression predicts numerical values
•	classification predicts category membership probabilities
________________________________________

## Visualisations

The project generates:

### Statistical Plots

•	Average PM2.5 by site
•	PM2.5 variability by site (with standard deviation)
•	PM2.5 time series plots
•	Extreme anomaly investigation plots

### Machine Learning Plots

•	Classification scatter plots
•	Logistic regression probability curves
•	Decision boundary visualisations
________________________________________

## Technologies Used

•	Python
•	pandas
•	NumPy
•	matplotlib
•	scikit-learn
•	Jupyter Notebook
•	Git & GitHub
________________________________________

## Project Structure

The pipeline follows a modular structure:

load_data()
clean_data()
extract_features()
generate_labels()
split_data()
train_model()
evaluate_model()
plot_results()
save_outputs()

This structure mirrors real-world machine learning workflow design.
________________________________________

## How to Run

1.	Clone the repository
2.	Open the notebook:
air_quality_analysis.ipynb
3.	Run all cells
________________________________________

## Conclusions

This project demonstrates the transition from traditional environmental data analysis into introductory machine learning workflows.

The statistical analysis component highlights how air pollution varies across monitoring sites and how extreme events can be identified using anomaly detection techniques.

The machine learning extension demonstrates how environmental measurements can be transformed into classification systems using supervised learning techniques such as logistic regression.

The project also introduces key ML concepts including:

•	train/test splitting
•	probabilistic prediction
•	decision boundaries
•	confusion matrices
•	classification evaluation

More broadly, the project demonstrates how structured data pipelines can evolve into complete end-to-end machine learning systems.
________________________________________

## Future Improvements

Potential future extensions include: 

•	multi-feature pollution prediction
•	weather and seasonal integration
•	wind and atmospheric transport effects
•	time-series forecasting
•	multi-class air quality classification
•	advanced ML models
•	real-time environmental monitoring pipelines


