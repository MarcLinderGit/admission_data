# Predicting Graduate Admissions with Machine Learning

In this project, I delve into the realm of predictive analytics to forecast the likelihood of admission for graduate students based on various factors. The dataset, sourced from Kaggle, includes essential parameters like GRE score, TOEFL score, university rating, statement of purpose (SOP), letter of recommendation (LOR), CGPA, and research experience.

### Project Context

Cardiovascular diseases (CVDs) stand as the leading global cause of death, accounting for millions of lives annually. Heart failure, often stemming from CVDs, underscores the importance of early detection. This dataset, with its 400 entries and 8 features, provides an excellent opportunity to employ machine learning for predicting graduate admission.

### Dataset Overview

- **Number of Entries:** 400
- **Features:** GRE Score, TOEFL Score, University Rating, SOP, LOR, CGPA, Research, Chance of Admit
- **Target Variable:** Chance of Admit

### Significance

As cardiovascular diseases continue to be a major health concern, early detection and intervention are crucial. In the context of graduate admissions, a machine learning model can aid in identifying key factors influencing admission chances, facilitating strategic decision-making.

### Model Training

I've trained a neural network model using features such as GRE score, TOEFL score, and CGPA. The model's performance is evaluated on both the training and validation sets, with a focus on the Mean Absolute Error (MAE) and R-squared value as key metrics.

### Hyperparameter Tuning

To enhance model performance, I conducted hyperparameter tuning, optimizing parameters like batch size, dropout rate, and learning rate. The best hyperparameters were identified to maximize the model's predictive capability.

### Final Model Performance

After 100 epochs of training, the main model achieved an R-squared value of approximately 71.46%, indicating a good fit to the data. Additionally, a separate visualization displays the validation loss and MAE over the training epochs.