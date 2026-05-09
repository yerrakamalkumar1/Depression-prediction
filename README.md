# Depression Prediction from Social Media Activity

Machine learning project by **Kamal Kumar** for predicting depression risk from synthetic social media activity data.

## Resume Summary

This project demonstrates practical experience in data science, machine learning, natural language processing, and model evaluation. It combines behavioral social media features with synthetic text data, builds classification pipelines, and evaluates model performance using standard ML metrics and visualizations.

## Project Overview

The goal of this project is to explore how machine learning can identify patterns associated with possible depression indicators in social media activity. The dataset used here is fully synthetic and includes posting behavior, sentiment-style features, interaction patterns, and generated text posts.

**Important:** This project is for educational and research experimentation only. It is not a clinical tool and should not be used for diagnosis.

## Skills Highlighted

- Python programming
- Data generation and preprocessing
- Machine learning classification
- Natural language processing with TF-IDF
- Feature engineering
- Model evaluation and visualization
- Logistic Regression and Random Forest modeling
- Pandas, NumPy, scikit-learn, Matplotlib, and Seaborn

## Key Features

- Generates a synthetic social media depression dataset
- Creates numerical behavior-based features such as posting frequency, night posting ratio, sentiment variation, and interaction rate
- Generates synthetic text posts using positive, negative, and neutral vocabulary
- Builds ML pipelines with numeric scaling and TF-IDF text vectorization
- Trains Logistic Regression and Random Forest classifiers
- Evaluates models using accuracy, ROC AUC, classification report, and confusion matrix
- Saves ROC curve, confusion matrix, and feature importance visualizations

## Repository Structure

```text
.
├── predict_depression_from_social_media.py
├── synthetic_depression_dataset.xlsx
├── Preview__Predicting-Depression-from-Social-Media-Activity__first_200_rows_.csv
└── README.md
```

## Tech Stack

```text
Python
NumPy
Pandas
scikit-learn
Matplotlib
Seaborn
TF-IDF Vectorization
Logistic Regression
Random Forest
```

## How to Run

Install the required dependencies:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn openpyxl
```

Run the main script:

```bash
python predict_depression_from_social_media.py
```

The script generates synthetic data, trains the models, prints evaluation results, and saves plots in an `outputs/` directory.

## Example Outputs

The project produces:

- ROC curve comparison for Logistic Regression and Random Forest
- Confusion matrix visualizations
- Text feature importance chart for Logistic Regression
- Synthetic dataset for experimentation

## Learning Outcomes

Through this project, I practiced building an end-to-end machine learning workflow:

- Designing a synthetic dataset for a sensitive use case
- Combining structured behavioral data with unstructured text data
- Building reusable scikit-learn pipelines
- Comparing multiple classifiers
- Interpreting model behavior through metrics and visualizations
- Documenting ethical limitations clearly

## Limitations

- The dataset is synthetic and may not reflect real-world social media behavior.
- The model is not suitable for medical, psychological, or clinical decision-making.
- Real-world work in this area requires consent, privacy protection, bias evaluation, and ethical approval.

## Author

**Kamal Kumar**  
Email: yerrakamalkumar1@gmail.com  
GitHub: [yerrakamalkumar1](https://github.com/yerrakamalkumar1)
