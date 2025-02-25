# HR-Job-Role-Recommendation-Project

## Table of Contents
1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

To run this project, ensure you have Python 3 installed. The required libraries can be installed using:

- !pip install imbalanced-learn
- !pip install scikit-learn
- !pip install xgboost
- !pip install kmodes
- !pip install joblib
- !pip install ipywidgets
- !pip install IPython

Apart from this, all necessary installations come with the standard anaconda distribution.

## Project Motivation <a name="motivation"></a>

This project consists of two parts, each targeting a different aspect of job role recommendations in the IT industry.

### **Part I: Data Science Career Insights**
We analyze Stack Overflow's Developer Survey to uncover trends for individuals aiming to break into Data Science. Key questions we explore include:

- How does Data Science differ from the IT sector in terms of education requirements?
- What impact does education have on salaries in IT and Data Science?
- What programming languages, tools, and technologies are most relevant for a Data Scientist?
- What are the main factors affecting salaries in the US IT sector?

### **Part II: HR-Assisted Job Role Classification**
In collaboration with an IT company's HR department, we develop a machine learning model to optimize candidate-role matching based on skill sets. This solution aims to:

- Improve **candidate-role matching accuracy**  
- **Reduce hiring time** by prioritizing best-fit candidates  
- **Optimize resource allocation** during the recruitment process  

## File Descriptions <a name="files"></a>

The repository contains the following key files:

- **Part I - Data Cleaning, EDA, Data Preprocessing.ipynb**: Contains the initial analysis, exploratory data analysis (EDA), and preprocessing of the Stack Overflow survey data.
- **Part II - Model Training & Evaluation - HR Assistance Job Role Classifier.ipynb**: Implements machine learning models for candidate-job role prediction.
- **raw_data**: Contains raw and datasets obtained from [Stack Overflow Developer Survey](https://survey.stackoverflow.co/)
- **cleaned_data**: This folder contains the cleaned and preprocessed files ready for EDA and model training.
- **models**: Contains and stores the models trained in this project.
- **images**: Stores some important images for this file.

## Results <a name="results"></a>

The main insights and findings from this project can be found in the following article:

[**A Career in Data Science & ML: Look Before You Leap!**](https://medium.com/@frasermfernandes/a-career-in-data-science-ml-look-before-you-leap-95dfedc1d250)

## Licensing, Authors, Acknowledgements <a name="licensing"></a>

Credit to **Stack Overflow** for the dataset. Licensing information and dataset details can be found [here](https://survey.stackoverflow.co/). This project was conducted independently, and all code is open-source for further use and adaptation.
