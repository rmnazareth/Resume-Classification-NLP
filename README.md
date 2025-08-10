# Resume Classification Model

## Overview

This project aims to automate the categorization of resumes using Natural Language Processing (NLP) and Machine Learning. It leverages a supervised ML model trained to classify resumes into various job categories based on their content. The project also features a web-based UI built with [Streamlit](https://streamlit.io/), allowing users to easily upload resumes and view their predicted categories.

### What’s Inside

- **ML Model:**
  An ML model trained using classic classifiers, which are Logistic Regression, Multinomial Naive Bayes, and SVM, to predict the job category of a given resume.
- **Streamlit Web Page:**
  An interactive web application for uploading resumes, viewing predictions, and exploring the model’s capabilities.

## Web UI 

<img width="1918" height="866" alt="1" src="https://github.com/user-attachments/assets/4592554d-9455-4cb1-948c-c093c933cdc7" />

<img width="1912" height="863" alt="2" src="https://github.com/user-attachments/assets/5b43aaa1-f73e-4784-8f4e-0bd6e72f7724" />

## Local Quickstart

Follow these steps to set up and run the project on your machine.

### 1. Clone the repository

```bash
git clone https://github.com/rmnazareth/Resume-Classification-NLP.git
cd Resume-Classification-NLP
```

### 2. Install dependencies

If you don’t have [Streamlit](https://docs.streamlit.io/library/get-started/installation) installed, you can install it using pip:

```bash
pip install streamlit
```

### 3. Run the Streamlit web page

Assuming your Streamlit app is in a file like `app.py` (adjust filename as needed):

```bash
streamlit run app.py
```

*This will launch the web interface in your browser.*

## Additional Notes

- **Model Files:** The trained ML model and TF-IDF vectorizer are saved as `model.pkl` and `tfidf.pkl` for reuse.
- **Dataset:** The main dataset used is `UpdatedResumeDataSet.csv`.
- **Customization:** You can retrain the model or adjust categories using the provided Jupyter notebook.
