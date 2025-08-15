#### This project was done under IIT Roorkee.

---



# Alzheimer's Disease Detection Using Machine Learning

This project was completed as part of an internship at IIT Roorkee, running from June 1 to June 30, 2024. The primary objective was to develop a machine learning model to detect Alzheimer's disease. The model was built using a dataset obtained from Kaggle, and several machine learning techniques were employed to optimize the performance.

## Project Overview

Alzheimer's disease is a progressive neurological disorder that leads to memory loss and cognitive decline. Early detection is crucial for timely intervention, and machine learning models can assist in diagnosing the disease from medical data.

### Key Features:

- **Exploratory Data Analysis (EDA):** A thorough analysis was conducted to understand the dataset and the relationships between variables.
- **Machine Learning Models:** Five different models were implemented:

  1. K-Nearest Neighbors (KNN)
  2. Random Forest Classifier
  3. Support Vector Machine (SVM)
  4. Decision Tree
  5. Neural Networks
- **Train-Test Splits:** Multiple train-test ratios (90:10, 80:20, 70:30, 60:40, 50:50) were tested to evaluate model performance.
- **Model Evaluation:** The Random Forest model with an 80:20 train-test split was found to be the most accurate, with the best F1 score.
- **Explainable AI (XAI):** The model's decisions were explained using the LIME technique, providing insights into the decision-making process.

For more details, please refer to the report file located in the `findings` folder.

## Dataset

The dataset used in this project was sourced from Kaggle and includes a variety of features that are relevant to Alzheimer's diagnosis.

## Installation and Usage

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your-username/alzheimers-disease-detection.git
   cd alzheimers-disease-detection
   ```
2. **Install Dependencies:**
   Make sure you have Python installed. Install the required packages using:

   ```bash
   pip install -r requirements.txt
   ```
3. **Run the Jupyter Notebooks:**
   The analysis, model training, and evaluation are documented in Jupyter Notebooks. Open them in Jupyter Notebook or Jupyter Lab.
4. **Explore the Findings:**
   The detailed report with all the findings is available in the `findings` folder.

## Results

The Random Forest model with an 80:20 train-test split achieved the highest accuracy and F1 score. The results of other models and splits are also documented in the report.

## Conclusion

This project demonstrates the application of machine learning techniques to detect Alzheimer's disease using publicly available data. The use of XAI methods like LIME further adds value by making the model's predictions interpretable.

## Acknowledgments

- Thanks to IIT Roorkee for providing the opportunity to work on this project.
- Special thanks to the Kaggle community for providing the dataset.

