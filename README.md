# A-Spark-Based-Big-Data-Analytics-Framework-for-Competitive-Intelligence

This project implements a big data analytics pipeline using PySpark to analyze and extract insights from a large dataset of research papers. Specifically, it focuses on Topic Modeling using Latent Dirichlet Allocation (LDA) and Latent Semantic Analysis (LSA) to identify trends and key themes within the blockchain domain.

## 🚀 Overview

The framework processes academic metadata (titles and abstracts) to:

Ingest data from HDFS or local storage using PySpark.

Clean and preprocess text data (tokenization, stop-word removal).

Vectorize text using TF-IDF (Term Frequency-Inverse Document Frequency).

Extract topics using the LDA algorithm.

Analyze semantic relationships through LSA and visualize results with word clouds and scatter plots.

## 🛠️ Tech Stack

Language: Python

Big Data Framework: Apache Spark (PySpark)

Machine Learning: Spark MLlib, Scikit-learn

Visualization: Matplotlib, Seaborn, WordCloud

Environment: Jupyter Notebook / Anaconda

## 📁 Project Structure

TopicModeling.ipynb: The main notebook containing the analysis pipeline.

Dataset/: Contains the Blockchain_Dataset_1984-2020.csv (used for competitive intelligence).

run.bat: A batch script to initialize the Spark environment and launch the notebook.

requirements.txt: List of necessary Python libraries.

## 📊 Key Features & Visualizations

1. Data Analysis - 
The script identifies the top publishers and the growth of research papers over the years (peaking significantly around 2018-2019).

2. Topic Extraction (LDA) - 
The model identifies clusters of words that define specific research areas, such as:

  Topic 1: Smart contracts, tokens, and multifractal analysis.

  Topic 2: Bitcoin, market time, and financial risk.

3. Semantic Analysis & Word Cloud - 
Using LSA, the project maps semantically similar words and generates a word cloud to visualize the most prominent terms in the dataset.

## ⚙️ How to Run

Prerequisites: Ensure you have Apache Spark and Anaconda installed.

Install Dependencies:

Bash
pip install -r requirements.txt

Launch the Project:

Run the run.bat file or execute the following in your terminal:

Bash
jupyter notebook TopicModeling.ipynb

## 📌 Results

The framework effectively identifies "Competitive Intelligence" by highlighting which institutions and publishers are leading in blockchain research and which sub-topics (like "Cryptocurrency" or "Privacy") are gaining the most academic traction.
