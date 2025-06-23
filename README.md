# Skimlit Project - Medical Abstract Classification and Highlighting 📖

Welcome to the **Skimlit Project**, a Natural Language Processing (NLP) project that classifies sentences in medical abstracts and highlights them as Background, Objective, Method, or Result.

This project is inspired by the SkimLit paper and aims to build a model that can automatically parse, classify, and label sentences within scientific abstracts, focusing on medical literature.

## 📄 Project Overview

The **Skimlit Project** provides:

* Sentence classification in medical abstracts.
* Highlighting sections like Background, Objective, Method, and Result.
* A practical demonstration of sequence classification in NLP.

## 💪 Tech Stack

* **Python 3**
* **TensorFlow/Keras** (for model training)
* **NumPy**
* **Pandas**
* **Matplotlib**
* **NLP Libraries** (like `scikit-learn`, `tensorflow_hub` if required)

## 🚀 Features

* End-to-End Medical Abstract Classifier.
* Preprocessing and visualization of datasets.
* Training using Bidirectional LSTM (or similar sequence models).
* Supports sentence highlighting based on classification labels.

## ⚙️ Requirements

You need the following Python packages:

* `numpy`
* `pandas`
* `matplotlib`
* `tensorflow`
* `scikit-learn`

Install them using:

```bash
pip install numpy pandas matplotlib tensorflow scikit-learn
```

## 🚀 How to Run

### 📥 Clone the Repository

```bash
git clone https://github.com/SrijaaimeenakshiM/Skimlit-project.git
```

### 🔢 Navigate to the Project Folder

```bash
cd Skimlit-project
```

### 📦 Install the Required Packages

```bash
pip install numpy pandas matplotlib tensorflow scikit-learn
```

### 💻 Open the Notebook

```bash
jupyter notebook skimlit_project.ipynb
```

Run the cells step by step to process the dataset, train the model, and test classification outputs.

## 📈 Dataset

The dataset used is a tokenized and labeled set of medical abstracts where each sentence is categorized as Background, Objective, Method, or Result.

You can customize the dataset or use a publicly available tokenized medical abstract dataset.

## 📂 Project Structure

```plaintext
Skimlit-project/
│
├── README.txt              # Project documentation
├── skimlit_project.ipynb   # Jupyter Notebook containing the full project
└── dataset/                # Folder to store datasets if required
```

---
