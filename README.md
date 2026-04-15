# Spark-Based-Clustering-Search-PageRank

This repository contains my solutions for Assignment 4 of the course *Machine Learning with Big Data (MLBD)*.

The assignment focuses on implementing core algorithms using PySpark and understanding their behavior on real datasets.

---

## 📌 Overview

The repository is divided into three main parts:

### 1. Clustering
- Implemented k-center algorithm
- Implemented k-means++ initialization
- Compared objective function values
- Dataset used: `spam.csv`

---

### 2. Search Engine
- Built an inverted index from multiple text files
- Implemented query search functionality
- Calculated TF-IDF scores
- Dataset files:
  - stack_datastructure_wiki
  - stack_cprogramming
  - stack_oracle
  - stackoverflow
  - stacklighting
  - stackmagazine

---

### 3. PageRank
- Implemented PageRank algorithm using PySpark
- Tested on:
  - small graph (small.txt)
  - large graph (whole.txt)
- Displayed top and bottom ranked nodes

---

## ⚙️ How to Run

### Step 1: Setup
Make sure you have:
- Python installed
- PySpark installed

Install PySpark using:
pip install pyspark

---

### Step 2: Run Notebooks

Open Jupyter Notebook or Google Colab and run the following files:

- clustering.ipynb
- search_engine.ipynb
- pagerank_final.ipynb

---

### Step 3: Dataset Placement

Ensure all dataset files are in the same directory as the notebooks.

---

## 📊 Output

Each notebook produces:
- Proper console output
- Results for each algorithm
- Screenshots can be taken directly from output cells

---

## 🛠 Technologies Used
- Python
- PySpark
- Jupyter Notebook / Google Colab

---

## 👤 Author
Divyansh Rawat

---

## 📎 Notes
- Iterations in PageRank may be reduced for faster execution
- Output correctness is maintained even with fewer iterations
