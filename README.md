# Lung Cancer Patient Dataset

This dataset contains health and lifestyle information of patients along with lung cancer diagnosis labels. It is designed for building and evaluating machine learning models to predict lung cancer risk.

---

## 📦 Dataset Overview

- **Rows:** 309 patients
- **Columns:** 16 features (including target label)
- **Target Variable:** `LUNG_CANCER` (`YES` / `NO`)

### 📝 Features

| Feature                | Description                                       | Type    |
|-----------------------|---------------------------------------------------|---------|
| GENDER                | Patient gender (`M` = Male, `F` = Female)         | Categorical |
| AGE                   | Age of the patient                                | Numeric     |
| SMOKING               | Smoking status (`1`=No, `2`=Yes)                  | Binary      |
| YELLOW_FINGERS        | Presence of yellow fingers (`1`=No, `2`=Yes)      | Binary      |
| ANXIETY               | Anxiety symptom presence (`1`=No, `2`=Yes)        | Binary      |
| PEER_PRESSURE         | Peer pressure experience (`1`=No, `2`=Yes)        | Binary      |
| CHRONIC DISEASE       | Presence of chronic disease (`1`=No, `2`=Yes)     | Binary      |
| FATIGUE               | Fatigue symptom presence (`1`=No, `2`=Yes)        | Binary      |
| ALLERGY               | Allergy symptom presence (`1`=No, `2`=Yes)        | Binary      |
| WHEEZING              | Wheezing symptom presence (`1`=No, `2`=Yes)       | Binary      |
| ALCOHOL CONSUMING     | Alcohol consumption status (`1`=No, `2`=Yes)      | Binary      |
| COUGHING              | Coughing symptom presence (`1`=No, `2`=Yes)       | Binary      |
| SHORTNESS OF BREATH   | Symptom of shortness of breath (`1`=No, `2`=Yes)   | Binary      |
| SWALLOWING DIFFICULTY | Swallowing difficulty symptom (`1`=No, `2`=Yes)   | Binary      |
| CHEST PAIN            | Presence of chest pain (`1`=No, `2`=Yes)          | Binary      |

---

## 🎯 Target Variable

| Label | Meaning         |
|-------|-----------------|
| YES   | Lung cancer diagnosed |
| NO    | No lung cancer       |

---

## 📊 Use Cases

- Binary classification tasks
- Predictive analytics in healthcare
- Feature importance and correlation studies
- Exploratory data analysis (EDA)

---

## 📁 Files

| File Name               | Description                    |
|-------------------------|----------------------------------|
| `cancer_preprocessed.csv` | Preprocessed dataset for ML use|
| `original_dataset.csv`     | Raw dataset as downloaded      |

---

## 🔗 Source

Original dataset: [Kaggle - Lung Cancer Patient Data](https://www.kaggle.com/datasets/mysarahmadbhat/lung-cancer)
