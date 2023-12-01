# TB-drug-resistance

## About
In order to achieve a more effective antibiotic treatment, accurate prediction for antimicrobial resistance (AMR) is important. Existing methods for predicting Mycobacterium tuberculosis (MTB) drug resistance uses genome sequencing data and achieves varying results, where most methods have high accuracy on only a few antibiotics but low performance on others. 
Here, we have built models to accurately predict the resistance of tuberculosis drugs from genome sequencing data across multiple antibiotics, focusing on eleven drugs. We designed three ways of data preprocessing in order to handle problems such as missing values and class imbalance. We proposed an ensemble approach based on Super Learner Ensemble (SLE), as well as comparing other traditional machine learning methods such as logistic regression, support vector machines. We demonstrate high predictive capabilities (average AUCROC and F1-score of ~0.92 and ~0.95) amongst the traditional machine learning models and showcase more stable predictions over an ensemble of such methods in comparison to the current state of the art (average F1-score of 0.92 to 0.96).

## Usage
Each model is in a different ipynb. To run them, download test data and result folder first, and change file path accordingly. 
