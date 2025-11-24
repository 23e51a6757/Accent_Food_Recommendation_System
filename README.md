#  Accent-Based Food Recommendation System  
Using **HuBERT + MFCC + SVM**

## Overview
This project identifies the **native language accent of Indian English speakers** using speech signals and recommends food based on the predicted region.

The system uses:

- **MFCC Features + Traditional Classifier**
- **HuBERT Embeddings (Self-Supervised Speech Model)**
- **SVM Classifier with 98.33% Accuracy**

---

##  Features

✔ Accent Detection  
✔ Food Recommendation  
✔ HuBERT & MFCC Comparison  
✔ Works on Sentence & Word-Level Speech  
✔ Simple Gradio Demo UI  

---

##  Dataset

Dataset Used: **IndicAccentDb (HuggingFace)**  
Contains recordings from Indian speakers (Telugu, Tamil, Hindi, Malayalam, Kannada, Bengali).

---

## Model Performance

| Model | Accuracy |
|-------|----------|
| MFCC + SVM | **81.96%** |
| HuBERT Embeddings + SVM | **98.33%** |

---

##  Technologies

| Component | Tool |
|----------|-------|
| Language | Python |
| ML/DL | Scikit-learn, Transformers |
| Audio Processing | Librosa |
| Deployment | Gradio UI |

---

## ▶ How to Run

1. Open `Accent_Food_Recommendation.ipynb` in Google Colab.
2. Install requirements:
   ```bash
   pip install -r requirements.txt

Run all cells to:

Load dataset
Extract MFCC & HuBERT features
Train models

Evaluate and generate results

Launch the Gradio app:

demo.launch()

Sample Output
Input: English speech sample
Predicted Accent: Telugu-English Accent
Suggested Food: Hyderabadi Biryani, Pesarattu, Gongura Pachadi

Files Included
File	Description
Accent_Food_Recommendation.ipynb	Main notebook
hubert_model.pkl	Trained HuBERT-based SVM model
mfcc_model.pkl	Trained MFCC-based SVM model
hubert_embeddings.npy	Saved HuBERT embeddings (subset)
mfcc_features.npy	Saved MFCC features (full dataset)
Project_Report.docx	Detailed project report
README.md	This documentation
requirements.txt	Required dependencies


