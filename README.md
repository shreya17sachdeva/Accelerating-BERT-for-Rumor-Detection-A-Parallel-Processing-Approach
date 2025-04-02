# **Accelerating BERT for Rumor Detection – A Parallel Processing Approach**  

## 📌 Overview  
This project focuses on optimizing **BERT-based rumor detection** by leveraging **parallel processing techniques** to enhance efficiency without compromising accuracy. By implementing **multi-threading and mixed precision training**, we achieved a **2.95x speedup** compared to traditional sequential BERT execution.  

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
- **Multiprocessing**  

## 📊 Results  
| Model                | Accuracy | Speedup Factor |
|----------------------|----------|---------------|
| Sequential BERT      | 92.33%   | 1x            |
| Parallel BERT       | 92.39%   | 2.95x         |
| BERT + MLP (Research Paper) | 86.9% | N/A |
