# Student Math Score Prediction Project
## Overview
This project focuses on predicting students' **math scores** based on various features such as 
- gender
- ethnicity
- parental_level_of_education
- lunch
- test_preparation_course
- writing_score
- reading_score

  This project implements machine learning algorithms to predict math scores based on relevant features. The goal is to build a predictive model that can assist in understanding the factors influencing math performance.
![output1](https://github.com/NextIn035846/MLProject/assets/72642100/08fa05e0-8442-41c6-a076-7a4ae4b44702)
![output2](https://github.com/NextIn035846/MLProject/assets/72642100/6ce1e83e-a73d-4353-8198-643f0e5fbbcf)
![output3](https://github.com/NextIn035846/MLProject/assets/72642100/2062283b-78f1-4720-89c9-973445f7b1cd)
## Project Structure

```bash
|-- MLProject
    
    |-- notebooks
        |-- data
          |-- stud.csv               # Raw data file
        |-- EDA Student.ipynb        # Data ingestion and exploration notebook
        |-- model_training.ipynb     # Model training and evaluation notebook
    |-- src
        |-- components                 # Model training module
            |-- data ingestion.py              # Load the data
            |-- data_transformation.py         # do the Feature engineering
            |-- model_trainer.py               # Model training module

        |-- Pipline               # creat the end to end pipline
            |-- predit_pipline.py
           
        |-- exception.py         # Custome Exception
        |-- loger.py             # creating logs
        |-- utils.py             # make common code

    |-- app.py                   # Flask application for prediction
    |-- requirements.txt             # Project dependencies
    |-- README.md                    # Project documentation
```

## Requirements
- Python 3.x
- Jupyter Notebook (optional, for interactive development)
- Required Python packages listed in requirements.txt
  Installation
## Clone the repository:
git clone
```bash
https://github.com/NextIn035846/MLProject.git
cd MLProject.git
```
## Install dependencies:

```bash
pip install -r requirements.txt
```


## Flask Application:

Implement the Flask application for prediction using the trained models in the app.py file.

Run the Flask app with the command: python app.py.

Access the prediction endpoint at http://localhost:5000/predictdata with the required input parameters.


## Benefits
**Early Intervention:**
Identify students at risk of lower math scores early on, enabling timely intervention and support.

**Resource Optimization:**
Allocate resources efficiently by targeting specific groups or individuals based on predicted performance.

**Data-Driven Decision-Making:**
Empower educators and administrators with data-driven insights to enhance educational strategies.

**Continuous Improvement:**
Continuously refine and improve the model based on new data and evolving educational dynamics.
