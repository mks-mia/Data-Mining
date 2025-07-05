# Phishing URL Detection Using Data Mining Techniques

This project was completed for the **Data Warehousing and Data Mining** course (ICT-324) at Rangsit University. It focuses on building a machine learning model to detect phishing URLs using logistic regression.

>  [Click here to view final project poster](./Group4_PhishingURLsDetection_FinalPoster.pdf)
>  [Click here to view project report](./Group4_PhishingURLsDetection_Report.pdf)

## Objective

Develop a phishing URL detection system using **Logistic Regression**, with a focus on adapting to evolving attack patterns and achieving high real-world accuracy.

## Project Overview

- **Dataset:** Kaggle (benign and malicious URLs) + JPCERT/CC PhishURL list  
- **Features:** URL length, HTTPS, suspicious keywords, subdomains, TLDs  
- **Method:** Year-by-year iterative training (2019–2023), tested on 2024 data  
- **Model:** Logistic Regression  
- **Accuracy:** 94%, balanced F1-score (0.94)

## My Role

As part of the group, I contributed by:

- Search for URL data from Kaggle Dataset
- Cleaning and preparing URL data in CSVs
- Extracting key features (subdomains, special characters, keywords)
- Assisting in model design and iterative training strategy
- Analyzing confusion matrices and supporting the presentation creation

## 🛠️ Tools

- Python, pandas, scikit-learn
- Jupyter/Colab
- CSV processing and visualization libraries

## Key Insight

Iterative training across multiple years improved model adaptability and recall for phishing URLs compared to single-year or combined training approaches.

