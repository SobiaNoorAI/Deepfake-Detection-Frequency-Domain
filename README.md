# 🔍 Deepfake Detection using Frequency Domain Analysis

## 🎯 Research Context
This project addresses the growing challenge of AI-generated media by detecting frequency-domain artifacts invisible to the human eye. Deepfake generation and re-compression leave distinct patterns in the DCT coefficient distribution that standard CNNs miss.

## 🧠 Methodology
- **Dual-Branch Architecture:** Spatial (EfficientNet-B0) + Frequency (DCT feature extraction)
- **Novelty:** Frequency branch captures re-compression artifacts and manipulation signatures
- **Explainability:** Grad-CAM visualization for model interpretability

Deepfake-Detection-Frequency-Domain/

├── README.md                                                                                          
├── requirements.txt                                   
├── 01_data_preparation.ipynb                                                                           
├── 02_frequency_feature_extraction.ipynb                                                
├── 03_model_training.ipynb                    
├── 04_evaluation_and_gradcam.ipynb                          
├── app/          
│   └── streamlit_app.py              
├── models/             
├── data/             
│   ├── train/          
│   │   ├── real/            
│   │   └── fake/           
│   └── val/            
│       ├── real/         
│       └── fake/         
└── utils/              
    └── dct_utils.py            

## 📊 Dataset
[]

## 🏗️ Architecture
[Diagram placeholder]

## 📈 Results
[after training]

## 🚀 Quick Start
[Installation instructions to be added]
