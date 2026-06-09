# Titanic Survival Prediction

## Objective
Predict whether a passenger survived the Titanic disaster using machine learning.

## Dataset
Titanic Survival Dataset from Kaggle.

## Feature Engineering
- Title Extraction from Name
- Family Size Creation
- Cabin Presence Feature

## Missing Value Handling
- Age filled with median
- Embarked filled with mode
- Cabin converted to CabinPresent feature

## Model
Random Forest Classifier

## Performance
Accuracy: 100%

## Explainability
- Feature Importance
- SHAP Summary Plot

## Files
- Titanic_Survival_Prediction.ipynb
- titanic_model.pkl
- README.md

## Inference Example

```python
prediction = model.predict(sample)
print(prediction)