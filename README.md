# Encrypted Traffic Classification Using Machine Learning and Deep Learning

This project is part of the SIT326 - Advanced Network Analytics and Forensics unit at Deakin University. It explores the use of flow-level metadata for classifying encrypted network traffic as benign or malicious using both machine learning and deep learning models.

## 📌 Project Overview

- **Goal:** Detect malicious encrypted traffic without payload inspection
- **Approach:** Use flow-level features (Zeek logs, statistical metadata)
- **Techniques:** Random Forest, SVM, CNN, LSTM
- **Tools:** Zeek, Python (scikit-learn, TensorFlow), Google Colab


## 🧾 Dataset Sources

1. **Mendeley Preprocessed Dataset**  
   Source: https://data.mendeley.com/datasets/ztyk4h3v6s/2  
   Clean, labeled, and balanced statistical flow features.

2. **ENTA Dataset (Zeek-based)**  
   Source: https://doi.org/10.5281/zenodo.14802737  
   Raw PCAP files were processed using Zeek to extract `conn.log` metadata.
