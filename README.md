# Heart Disease Prediction

## This project applies machine learning classification techniques to predict the precense of heart disease based on a patient's medical attributes.

### Problem Definition

The aim of the project is to answer the following question:
- Given clinical parameters about a patient, can we determine whether or not they have heart disease?

## Data

The original data came from https://archive.ics.uci.edu/dataset/45/heart+disease while there is a version of the data available on Kaggle. https://www.kaggle.com/datasets/ketangangal/heart-disease-dataset-uci
The following attributes were used:
1. #3 (age)
2. #4 (sex)
3. #9 (cp)
4. #10 (trestbps)
5. #12 (chol)
6. #16 (fbs)
7. #19 (restecg)
8. #32 (thalach)
9. #38 (exang)
10. #40 (oldpeak)
11. #41 (slope)
12. #44 (ca)
13. #51 (thal)
14. #58 (num) (the predicted attribute)
    
Feel free to read the detailed report(Report.pdf) in the repo if you want to see the full dataset(or you can follow the links above)

# Files
*end-to-end-heart-disease-classification.ipynb*: The jupyter notebook file containing all the code used throughout the project.

*heart-disease.csv*: The csv file containing the data used in this project.

# Tech Stack/ Dependencies
List of the tools and libraries I used:
- Python, Anaconda
- NumPy, Pandas, Matplotlib, Seaborn
- Scikit-learn

# Installation & Usage

### How to set up the environment:

git clone https://github.com/yourusername/heart-disease-project.git

cd heart-disease-project

conda env create -f environment.yml

conda activate heart-disease

### How to run the notebook:

jupyter notebook end-to-end-heart-disease-classification.ipynb

# Results
The final model achieved a testing accuracy of 88.52%

# Future Work
To achieve a higher accuracy, I could
- Try more hyperparameter tuning
- Experimenting with deep learning frameworks such as TensorFlow or PyTorch
- Advanced Feature Engineering
- Model deployment for real world use.


