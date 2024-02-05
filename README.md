# classification-challenge
# Spam Detection Project

## Overview
This spam detection project leverages machine learning to accurately distinguish between spam and non-spam (ham) emails. Utilizing a dataset from the UCI Machine Learning Repository, we explore, preprocess, and apply two different models: Logistic Regression and Random Forest Classifier, to perform the classification task.

## Dataset
The dataset is sourced from the [UCI Machine Learning Library](https://archive.ics.uci.edu/ml/datasets/spambase), containing various features extracted from spam and non-spam emails. Features include the frequency of specific words and characters, as well as statistics on capital letters, among others.

## Requirements
- Python
- pandas
- numpy
- scikit-learn


## Files in the Repository
- `spam-data.csv`: The dataset file.
- `Spam_Detection.ipynb`: Jupyter notebook containing the analysis, model training, and evaluation.


## Models Used
- **Logistic Regression**: A baseline model for binary classification tasks.
- **Random Forest Classifier**: An ensemble method used to improve prediction accuracy.

## Performance
The models were evaluated based on their accuracy scores:
- Logistic Regression achieved an accuracy of approximately 91.97%.
- Random Forest Classifier outperformed with an accuracy of approximately 95.55%.

## Usage
To replicate the analysis and model training:
1. Clone this repository.
2. Ensure you have Jupyter Notebook installed, or use [Google Colab](https://colab.research.google.com/).
3. Run `Spam_Detection.ipynb` notebook.

## Conclusion
The Random Forest Classifier model demonstrated superior performance in detecting spam emails, highlighting its efficacy in handling the complexities and non-linearities of the data.

## Future Work
- Experiment with additional feature engineering and selection techniques.
- Explore more advanced models and ensemble methods.
- Implement hyperparameter tuning to further improve model performance.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
