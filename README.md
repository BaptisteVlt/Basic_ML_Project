# Student Performance Prediction Project

## Project Overview
This is a Machine Learning Engineering (MLE) project designed to predict student math performance. The primary objective is to create a robust, reusable project architecture that can be easily adapted to more complex AI projects.

## Project Architecture
Basic_ML_Project/  
├── artifacts/  
│   ├── model.pkl  
│   └── preprocessor.pkl  
├── logs/  
├── notebook/  
│   ├── data/  
│   ├── EDA.ipynb  
│   └── Model_training.ipynb  
├── src/  
│   ├── components/  
│   │   ├── data_ingestion.py  
│   │   ├── data_transformation.py  
│   │   └── model_trainer.py  
│   ├── pipeline/  
│   │   ├── predict_pipeline.py  
│   │   └── train_pipeline.py  
│   ├── exception.py  
│   ├── logger.py  
│   └── utils.py  
├── templates/  
│   ├── home.html  
│   └── index.html  
├── app.py  
├── requirements.txt  
└── setup.py  

## Technologies and Libraries Used

### Machine Learning
- pandas: Data manipulation
- numpy: Numerical computing
- scikit-learn: Machine learning algorithms and tools
- catboost: Gradient boosting library
- xgboost: Advanced gradient boosting library

### Data Visualization
- seaborn: Statistical data visualization
- matplotlib: Plotting library

### Web Framework
- Flask: Lightweight web application framework

### Serialization
- dill: Advanced serialization library

## Key Features
- Custom exception handling
- Comprehensive logging
- Modular ML pipeline architecture
- Reusable project structure
- Web interface for predictions

## Setup and Installation

1. Clone the repository
```bash
git clone https://github.com/BaptisteVlt/Basic_ML_Project
cd Basic_ML_Project
pip install -r requirements.txt
```
2. Train the model
```bash
python src/pipeline/train_pipeline.py
```
3. Start application
```bash
pyhton app.py
```
http://10.10.1.52:5000/  
http://10.10.1.52:5000/predictdata  

## File to update to personalize the application
1. Data file in notebook/data/stud.csv
2. Research : notebook/EDA.ipynb and notebook/Model training.ipynb  
3. Update the data path file in src/components/data_ingestion.py
4. Update src/components/data_transformation with the transformation that you want to perform on your new data
5. Update src/components/model_trainer with all the models and hyperparameters that you would like to try
6. In src/utils.py update evaluate_models with the metrics that you need for your problem
7. In src/pipeline/predict_pipeline.py and app.py update CustomData so it suits your new datas
8. In template/index.html update the form  


 