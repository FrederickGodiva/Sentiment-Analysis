<h1 align="center">Sentiment Analysis</h1>

---

# Table of Contents

- [Overview](#overview)
- [Project Structure](#project-structure)
- [Tech Stack](#tech-stack)
- [Usage](#usage)

# Overview

This project aims to build a sentiment analysis model for user reviews of the [DBS digibank mobile application](https://play.google.com/store/apps/details?id=com.dbs.id.pt.digitalbank&hl=id). The pipeline involves collecting raw review data, cleaning and processing it, extracting meaningful features, and training a neural network model to classify user sentiment.

# Project Structure

```
├── 1 - Data Scraping.ipynb             # notebook for scraping raw app review data 
├── 2 - Data Preprocessing.ipynb        # notebook for cleaning and preprocessing the raw data
├── 3 - Data Preparation.ipynb          # notebook for formatting and organizing data for training
├── 4 - Feature Extraction.ipynb        # notebook for extracting meaningful features from the data
├── 5 - Neural Network Modelling.ipynb  # notebook for modelling and inferencing the model
├── app_review.csv                      # original raw app review dataset
├── app_review_labeled.csv              # dataset with labels applied
├── app_review_translated.csv           # dataset translated into English
├── model.keras                         # saved Keras model file containing the trained neural network
├── my_dir                              # directory containing hyperparameter configurations
├── processed_objects                   # serialized preprocessing objects
├── requirements.txt                    # dependencies used in the project
├── README.md                           # documentation for this project
```

# Tech Stack

<a href="https://www.python.org/"><img src="https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue" /></a>
<a href="https://pandas.pydata.org/"><img src="https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white"/></a>
<a href="https://numpy.org/"><img src="https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white"/></a>
<a href="https://scikit-learn.org/"><img src="https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"/></a>

<a href="https://www.tensorflow.org/"><img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=TensorFlow&logoColor=white"/></a>
<a href="https://keras.io/"><img src="https://img.shields.io/badge/Keras-FF0000?style=for-the-badge&logo=keras&logoColor=white"/></a>
<a href="https://jupyter.org/"><img src="https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white"/></a>
<a href="#"><img src="https://img.shields.io/badge/Shell_Script-121011?style=for-the-badge&logo=gnu-bash&logoColor=white"/></a>

# Usage

1. Clone this repository

   ```bash
   git clone https://github.com/FrederickGodiva/Air-Quality-Dashboard.git
   ```

2. Install Python Virtual Environment Library

   ```bash
   pip install virtualenv
   ```
   
3. Create Python Virtual Environment

   Linux / Mac:
   ```bash
   python3 -m virtualenv venv
   ```

   Windows:
   ```bash
   python -m virtualenv venv
   ```
   
4. Activate the Environment

   Linux / Mac:
   ```bash
   source venv\bin\activate
   ```

   Windows:
   ```bash
   venv\Scripts\activate
   ```
   
5. Install all the requirements

   ```bash
   pip install -r requirements.txt
   ```
   
6. Open each notebook and run each cell code

---

Copyright &copy; 2025 - Frederick Godiva
