# Machine Learning: Exoplanet Exploration

![exoplanets.jpg](Images/exoplanets.jpg)

## Background
Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.

This project uses the data they gathered to train four machine learning (ML) models those are intended to classify candidate exoplanets.

## Models
- Logistic Regression (LR)
- Random Forest (RF)
- K Nearest Neighbor (KNN)
- Support vector Machine (SVM)

### Model Design Approach
- Build a base model using the original dataset and all its 40 features.
- Use the base model to evaluate feature importance.
- Tune the model parameters using *GridSearchCV*.
- Build the final model using the tuned parameters.

## Model Comparison
The RF model was the more accurate of the four by a small margin.

![models_eval](Images/eval.PNG)

## Conclusions
Evidently, given the relatively high accuracy of the RF model, I believe it to be a reasonable predictor of exoplanet candidacy.
