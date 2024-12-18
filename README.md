# Titanic Survival Prediction

## Project Overview
This is a machine learning project to predict passenger survival on the Titanic using a Random Forest Classifier. The goal is to build a model that can predict which passengers survived the tragic sinking based on various features.

## Dataset
The project uses the classic Titanic dataset, which contains information about passengers aboard the Titanic, including:
- Passenger Class (Pclass)
- Sex
- Number of Siblings/Spouses Aboard (SibSp)
- Number of Parents/Children Aboard (Parch)

## Prerequisites
- Python 3.x
- pandas
- numpy
- scikit-learn

## Installation
1. Clone the repository
2. Install required libraries:
```bash
pip install pandas numpy scikit-learn
```

## Project Structure
- `train.csv`: Training dataset
- `test.csv`: Test dataset
- `submission.csv`: Predictions output file

## Model Details
- Algorithm: Random Forest Classifier
- Parameters:
  - Number of trees: 100
  - Max depth: 5
  - Random state: 1

## Feature Preprocessing
- One-hot encoding used for categorical features
- Features used: Passenger Class, Sex, Siblings/Spouses, Parents/Children

## How to Run
```bash
python titanic_survival_prediction.py
```

## Output
The script generates a `submission.csv` file with two columns:
1. PassengerId
2. Survived (0 = Did not survive, 1 = Survived)

## Score
The model acheived a 70% percent accuracy score on kaggle submission


## Potential Improvements
- Add more features
- Try different machine learning algorithms
- Implement cross-validation
- Handle missing data more comprehensively

## Acknowledgments
- Dataset source: Kaggle Titanic: Machine Learning from Disaster competition

## License
This project is open-source. Please include appropriate attribution if you use the code.
