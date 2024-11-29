# Student Performance Prediction Project

## Project Overview
This is a Machine Learning Engineering (MLE) project designed to predict student math performance. The primary objective is to create a robust, reusable project architecture that can be easily adapted to more complex AI projects.

## Project Architecture
Basic_ML_Project/
│
├── artifacts/                # Stored model and transformation artifacts
│   ├── model.pkl
│   └── preprocessor.pkl
│
├── logs/                     # Log files for tracking pipeline execution
│
├── notebook/                 # Jupyter notebooks for exploration
│   ├── data/
│   ├── EDA.ipynb
│   └── Model_training.ipynb
│
├── src/                      # Source code
│   ├── components/           # ML pipeline components
│   │   ├── data_ingestion.py
│   │   ├── data_transformation.py
│   │   └── model_trainer.py
│   │
│   ├── pipeline/             # End-to-end pipelines
│   │   ├── predict_pipeline.py
│   │   └── train_pipeline.py
│   │
│   ├── exception.py          # Custom exception handling
│   ├── logger.py             # Logging configuration
│   └── utils.py              # Utility functions
│
├── templates/                # Web application templates
│   ├── home.html
│   └── index.html
│
├── app.py                    # Flask application
├── requirements.txt          # Project dependencies
└── setup.py                  # Package setup configuration

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
git clone https://github.com/your-username/student-performance-project.git
cd student-performance-project