Resume Screening using NLP

This project is an resume screening tool built with Natural Language Processing (NLP) and an interactive Streamlit web app.
It helps automatically determine the domain (or job category) a candidate belongs to, based on the skills listed in their resume.

📌 Project Overview

Recruiters often spend significant time manually reviewing resumes to determine the right domain for a candidate.
This project automates that process using a Category–Skill mapping approach:

Dataset: Contains two columns:

category → Job domain (e.g., Data Science, Web Development, Cloud Computing, etc.)

skills → Key skills associated with that category (e.g., Python, Django, AWS, TensorFlow).

Goal:
Given the skills extracted from a candidate's CV, predict the domain/category they are most likely suited for.

⚙️ How It Works

Data Preprocessing

Clean and normalize the skills dataset.

Map skills to their respective categories.

Skill Extraction from Resume

Extract text from uploaded resumes (supports .pdf files).

Identify skills from the extracted text using NLP techniques.

Category Prediction

Match extracted skills with the dataset’s mapping.

Predict the most probable category/domain for the resume.

Streamlit Web App

Upload your resume via the app interface.

View the detected skills.

Get the predicted job domain instantly.

🖥️ Tech Stack

Python

NLP: nltk

Data Handling: pandas, numpy

File Processing: python-docx, PyPDF2

Web App: Streamlit

🚀 Features

Upload .pdf resumes.

Automatic skill extraction.

Skill-to-category mapping using dataset.

Instant domain prediction.

Clean, interactive Streamlit UI.
