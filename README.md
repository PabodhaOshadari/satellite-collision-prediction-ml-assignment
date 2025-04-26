
# satellite-collision-prediction-ml-assignment
4th-year university Machine Learning assignment: Predicting Satellite Collision Risks in Low Earth Orbit using supervised learning (Random Forest and SVM).

# Predicting Satellite Collision Risks in Low Earth Orbit Using Supervised Learning

This project was developed as part of my 4th-year Machine Learning coursework at [Your University Name], focusing on applying supervised learning algorithms to a real-world problem.

## Project Overview

As the number of satellites increases, so does the risk of collisions in Low Earth Orbit (LEO). This project aims to use machine learning to predict potential collision risks based on satellite and debris trajectory data.

##  Problem Statement

The growing issue of space debris has raised concerns about satellite safety and the potential for a cascading series of collisions known as the Kessler Syndrome. This project explores how data-driven models can help proactively identify satellites at high risk.

## Algorithms Used

Two supervised learning algorithms were applied and compared:

- **Random Forest**
- **Support Vector Machine (SVM)**

Both were evaluated using performance metrics including accuracy, precision, recall, F1-score, and ROC-AUC.

##  Dataset

- **Source**: [Kaggle - Space Debris Dataset](https://www.kaggle.com/datasets) *(replace with actual link)*
- **Features Included**: Satellite velocity, distance to debris, timestamp, object type, etc.
- **Target Variable**: Binary label indicating risk (1 = collision risk, 0 = safe)

##  Preprocessing Steps

- Handling missing values
- Scaling numerical features
- Encoding categorical data
- Splitting into training and testing sets

##  Results Summary

| Metric        | Random Forest | SVM          |
|---------------|---------------|--------------|
| Accuracy      | XX.XX%        | XX.XX%       |
| Precision     | XX.XX%        | XX.XX%       |
| Recall        | XX.XX%        | XX.XX%       |
| F1 Score      | XX.XX%        | XX.XX%       |
| ROC-AUC Score | XX.XX         | XX.XX        |

*(Replace the XX.XX values with your actual results)*

##  Conclusion

Random Forest slightly outperformed SVM in predicting potential collision events. This project demonstrates the usefulness of supervised learning models in aerospace applications.

##  How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/satellite-collision-prediction-ml.git
   cd satellite-collision-prediction-ml


