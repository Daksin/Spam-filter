# Spam Filter — Python Machine Learning Coursework

This project implements and evaluates multiple machine learning models to classify email text as **spam** or **legitimate**.  
The coursework focuses on **text preprocessing**, **feature engineering**, **model comparison**, and **performance evaluation** using standard NLP and ML techniques.


## Models Implemented
- Naïve Bayes
- Logistic Regression

Both models are trained and tested on the same dataset to allow for direct comparison of performance and trade-offs.


## Text Preprocessing Pipeline
The following preprocessing steps are applied to raw email text:
- Tokenization 
- Stop-word removal  
- Text normalization  
- TF–IDF vectorization using scikit-learn

## Model Optimisation

- Hyperparameters tuned to maximise classification performance  
- Cross-validation used where appropriate  

Final model performance:
- Accuracy: 96%  
- Precision: 94%  
- F1-score: 95% (test dataset)


## Tech Stack
- Python  
- scikit-learn  
- NumPy  
- Pandas  
- Matplotlib / Seaborn

## Author
Dakshit Singhal  
BSc (Hons) Computer Science  
University of Manchester
