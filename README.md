## data
Contains wrangled/cleaned data. 'uncontacted_lead_predictions' is the result from the model

## models
Contains model information and specifications for book keeping

## Notebooks

#### 02_JDS_SVG_MC_data_wrangling.ipynb
Initial data analysis. Looked at format/columns of data. Removed any columns that have significant amount of missing/nonsense data.

#### 03_JDS_SVG_MC_exploratory_data_analysis.ipynb
Began statistical analysis on the data. Found feature relationships and prepped key ones for model.

#### 04_JDS_SVG_MC_preprocessing_and_training.ipynb
Built a pipeline for a KNN model. Divided data into training and testing set. Fitted model and tested with cross validation. Found best K-values and measured with confusion matrix metric.

#### 05_JDS_SVG_MC_modeling.ipynb
Ran model through rest of the data. Output predictions into 'uncontacted_lead_predictions.csv'

## raw_data
Contains original data file

## JDS_Presentation
Powerpoint presentation and overview of project and answers.

## JDS_Report
Essentially an extension of comments in my code. Details my thought process and description of each Notebook.