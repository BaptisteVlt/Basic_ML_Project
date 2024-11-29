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