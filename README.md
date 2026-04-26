link : https://colab.research.google.com/drive/1RVb9gxtn4cG_JzYJ7bnVpFHbtgH3xocd?usp=sharing#scrollTo=K3Ff6znWFE-G
# Machine Learning Project: Adult Income Prediction

## Project Goal
The goal of this project is to automate the process of predicting whether an individual's income exceeds $50K per year based on census data. This replaces manual review with a data-driven Machine Learning solution.

## ML Task
- **Type:** Binary Classification.
- **Library used:** AutoGluon (Tabular Predictor).

## Dataset
The dataset used in this project is the **Adult Income Dataset** (also known as the "Census Income" dataset). It contains demographic and socio-economic information.
You can find and download the dataset from the following sources:
- [UCI Machine Learning Repository - Adult Dataset](https://archive.ics.uci.edu/ml/datasets/adult)
- [Kaggle - Adult Census Income](https://www.kaggle.com/datasets/uciml/adult-census-income)

## Data Quantity and Quality
- **Quantity:** The dataset contains 32,561 records and 14 features.
- **Quality:** The data is consistent. Missing values (marked as '?') were handled automatically by the AutoGluon preprocessing pipeline during the training phase.

## Key Insights (Predictive Power)
Based on the Feature Importance analysis:
- **Top Predictors:** `Relationship`, `Education-num`, and `Age` are the most influential features.
- **Fairness:** Demographic features like `Race` and `Native-country` have minimal impact, ensuring a more merit-based prediction.

## Model Performance
- **Success Criteria:** Accuracy > 85%.
- **Metrics:** The model achieved high accuracy and F1-score, meeting the project requirements.

## Deployment
The project includes an interactive local deployment using `ipywidgets`, allowing users to input data and get real-time predictions directly within the notebook.

## Setup and Usage
1. Clone this repository.
2. Install dependencies: `pip install autogluon ipywidgets`.
3. Open `Untitled5.ipynb` in Google Colab or Jupyter Notebook.
4. Run all cells to train the model and launch the interactive app.

   ##Project Resources

1. Primary Dataset Source:
UCI Machine Learning Repository: Adult Income Dataset.
Link: https://archive.ics.uci.edu/dataset/2/adult
Description: The original source for the census data used to train the model, containing demographic features and income labels.
2. Data Documentation & Feature Analysis:
Kaggle - Adult Census Income: Detailed Feature Explanation.
Link: https://www.kaggle.com/datasets/uciml/adult-census-income
Description: Provides insights into variable definitions, including technical terms like Capital Gain and its socioeconomic impact.
3. Deployment & UI Framework:
Gradio Documentation: Building Machine Learning Interfaces.
Link: https://www.gradio.app/docs/
Description: Technical guide used to develop the interactive user interface (UI) for model inference and testing.


