# **Accelerating BERT for Rumor Detection – A Parallel Processing Approach**  

## 📌 Overview  
This project focuses on optimizing **BERT-based rumor detection** by leveraging **parallel processing techniques** to enhance efficiency without compromising accuracy. By implementing **multi-threading and mixed precision training**, we achieved a **2.95x speedup** compared to traditional sequential BERT execution.  

## 🗂 Dataset Information  
We used the **PHEME** dataset, a widely recognized benchmark for rumor detection.  

- **Source**: Social media posts (mainly Twitter)  
- **Dataset Link**: [PHEME Dataset](https://www.kaggle.com/datasets/nicolemichelle/pheme-dataset-for-rumour-detection)  
- **Labels**:  
  - **Rumor (1)** – Misinformation or unverified claims  
  - **Non-Rumor (0)** – Verified factual information  
- **Features**:  
  - **Text**: Content of the post/tweet  
  - **User Metadata**: Optional user-related information  
  - **Engagement Data**: Optional retweets, replies, likes  
- **Preprocessing**:  
  - Removed missing or duplicate entries  
  - Tokenized text for BERT embeddings  
  - Converted labels into binary classification format  

## 🚀 Key Features  
- **Sequential BERT Classifier**: Implements a standard BERT-based model for rumor detection.  
- **Parallel BERT Processing**: Utilizes **multi-threading and CUDA acceleration** to speed up inference.  
- **Comparative Analysis**: Benchmarks performance against **traditional ML models** (KNN, Random Forest, SVC, PAC) and an **existing BERT + MLP classifier**.  
- **High Accuracy**: Achieved **92.39% accuracy** with significantly faster training and inference.  

## 🛠️ Technologies Used  
- **Python**  
- **PyTorch**  
- **Hugging Face Transformers**  
- **Scikit-learn**  
- **CUDA**  
