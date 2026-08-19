# CSE440-Project
# Multi-Class Text Classification using NLP

## CSE440 - Natural Language Processing II

This project focuses on multi-class text classification of online discussion posts using traditional machine learning, recurrent neural networks, word embeddings, and BERT.

The project uses the **20 Newsgroups dataset**, which contains documents from 20 different discussion categories. We investigate different text preprocessing techniques, word representations, machine learning models, neural architectures, and transformer-based models.

---

## 👥 Team Members

| Name | Student ID | Main Contribution |
|------|------------|-------------------|
| Member 1 |22201895| Dataset, EDA, preprocessing, Word2Vec, GloVe |
| Member 2 |22301693| Naive Bayes, Logistic Regression, Random Forest, SimpleRNN, GRU, LSTM |
| Member 3 |22201914| Bidirectional RNN models, BERT, Ensemble, Ablation Study |

---

## 📌 Project Objectives

The main objectives of this project are:

- Perform exploratory data analysis on a real-world text dataset.
- Apply appropriate text preprocessing techniques.
- Compare different word representation methods.
- Evaluate traditional machine learning classifiers.
- Evaluate recurrent neural network architectures.
- Compare unidirectional and bidirectional recurrent models.
- Evaluate a pretrained BERT model.
- Perform hyperparameter/configuration tuning.
- Compare the performance of all models using Accuracy and Macro F1.
- Perform ensemble learning as a bonus task.
- Perform an ablation study as a bonus task.

---

## 📊 Dataset

We use the **20 Newsgroups dataset** for multi-class text classification.

### Dataset Information

- Number of classes: **20**
- Original number of documents: **18,846**
- Final number of documents after preprocessing: **17,863**
- Language: English

### Classes

The dataset contains the following categories:

- alt.atheism
- comp.graphics
- comp.os.ms-windows.misc
- comp.sys.ibm.pc.hardware
- comp.sys.mac.hardware
- comp.windows.x
- misc.forsale
- rec.autos
- rec.motorcycles
- rec.sport.baseball
- rec.sport.hockey
- sci.crypt
- sci.electronics
- sci.med
- sci.space
- soc.religion.christian
- talk.politics.guns
- talk.politics.mideast
- talk.politics.misc
- talk.religion.misc

---

## 🔄 Project Workflow

```text
20 Newsgroups Dataset
        ↓
Exploratory Data Analysis
        ↓
Text Preprocessing
        ↓
Train / Validation / Test Split
        ↓
Word Representations
   ┌───────────────┐
   │               │
 Word2Vec        GloVe
   │               │
   └───────┬───────┘
           ↓
     Model Training
           ↓
   Hyperparameter Tuning
           ↓
      Model Selection
           ↓
      Test Evaluation
           ↓
   Model Comparison
           ↓
     Bonus 1: Ensemble
           ↓
     Bonus 2: Ablation
