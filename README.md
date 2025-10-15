# pakistani_people_fake_dataset
A synthetic dataset of 1000  fake Pakistani people for AI &amp; data analysis projects.

# 🇵🇰  People fake Dataset (Synthetic)  
![License: CC0](https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg)
![Made with 💙 in Pakistan](https://img.shields.io/badge/Made%20with-%F0%9F%92%99%20in%20Pakistan-green)

A **synthetic dataset** of **1,000 Pakistani individuals**, created for use in **AI, data science, and machine learning** projects.  
This dataset reflects realistic Pakistani demographic patterns — while containing **no personal or real data** — making it completely safe and open for educational, academic, and research purposes.

---

## 📊 Dataset Overview

| Attribute | Description |
|------------|-------------|
| **id** | Unique numeric identifier |
| **full_name** | Randomly generated Pakistani name |
| **gender** | Male / Female |
| **age** | Age between 18 and 65 years |
| **city** | Major cities (Karachi, Lahore, Islamabad, etc.) |
| **province** | Province corresponding to the city |
| **occupation** | Common Pakistani professions |
| **education** | Matric, Intermediate, Bachelor, Master, PhD |
| **phone_number** | Synthetic Pakistani-format phone (+92...) |
| **email** | Fake but valid-format email |
| **income** | Estimated monthly income in PKR |
| **marital_status** | Single / Married |
| **language** | Regional language (Urdu, Punjabi, etc.) |

---

## 🧠 Purpose

This dataset is ideal for:

- 🧩 Machine Learning model testing  
- 📈 Data visualization and analysis  
- 🧮 Statistics and probability exercises  
- 🧠 AI/NLP training (synthetic profiles)  
- 🎓 Educational projects and data handling practice  

---

## 🧾 Example Rows

| id | full_name | gender | age | city | province | occupation | income |
|----|------------|---------|-----|--------|-----------|------------|--------|
| 1 | Adeel Khan | Male | 29 | Rawalpindi | Punjab | Software Engineer | 120000 |
| 2 | Sara Ahmed | Female | 24 | Karachi | Sindh | Teacher | 65000 |
| 3 | Usman Malik | Male | 33 | Lahore | Punjab | Doctor | 150000 |

---

## 🧩 File Information

**File Name:** `pakistani_people_dataset.csv`  
**Records:** 1,000  
**File Type:** CSV (comma-separated values)  
**Encoding:** UTF-8  

---

## ⚙️ How to Use

### 🔹 In Python (Pandas)

```python
import pandas as pd

url="https://raw.githubusercontent.com/CM-Kali/pakistani_people_fake_dataset/main/pakistani_people_dataset.csv"
df = pd.read_csv(url)

print(df.head())
print(df.info())
