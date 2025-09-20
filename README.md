# 💬 Text Mining for Claims Narratives and Customer Complaints

## 📌 Project Overview
This project applies Natural Language Processing (NLP) techniques to analyze insurance claims narratives and customer complaints. By extracting latent themes, sentiment, and anomalies, it supports fraud detection, customer service triage, and operational insights. The pipeline includes preprocessing, topic modeling, clustering, and visualization.

## 🎯 Objectives
- Clean and structure unstructured text data from claims and complaints
- Identify dominant topics using LDA and NMF
- Cluster narratives to detect patterns and anomalies
- Perform sentiment analysis to flag negative experiences
- Visualize insights for business and operational teams

## 🧠 Methodology

### 1. Data Preprocessing
- Tokenization, stopword removal, lemmatization
- Named Entity Recognition (NER) for extracting entities like dates, locations, and amounts
- TF-IDF vectorization for feature extraction

### 2. Topic Modeling
- Latent Dirichlet Allocation (LDA)
- Non-negative Matrix Factorization (NMF)
- Coherence score optimization for topic selection

### 3. Clustering
- K-Means and DBSCAN for grouping similar narratives
- Dimensionality reduction using PCA and t-SNE

### 4. Sentiment Analysis
- Rule-based (VADER) and ML-based sentiment scoring
- Classification into positive, neutral, and negative buckets

### 5. Visualization
- Word clouds, topic graphs, cluster scatter plots
- Dashboard-ready outputs for BI tools

## 🧰 Tech Stack
- **Languages**: Python
- **Libraries**: NLTK, SpaCy, Gensim, Scikit-learn, Pandas, Matplotlib, Seaborn
- **Visualization**: Plotly, WordCloud
- **Optional BI Integration**: Power BI, Tableau

## 📁 Repository Structure
