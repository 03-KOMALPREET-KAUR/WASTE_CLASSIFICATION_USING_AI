# ♻️WASTE_CLASSIFICATION_USING_AI

📌 **Overview**
This project presents a deep learning-based image classification approach to waste segregation, designed to identify whether waste is biodegradable or non-biodegradable.
It further classifies items into categories like plastic, metal, paper, cardboard, organic waste, glass types, clothes, shoes, batteries, and trash.
The system also provides disposal guidance – suggesting whether a material can be reused, recycled, or requires safe disposal.

📊 **Dataset**
We used the Garbage Classification Dataset consisting of 15,150 images from 12 different classes:
- Paper
- Cardboard
- Biological (Organic waste)
- Metal
- Plastic
- Green Glass
- Brown Glass
- White Glass
- Clothes
- Shoes
- Batteries
- Trash
📂 Source: Garbage Classification Dataset on Kaggle

🧠 **Methodology**
Built with Deep Learning (Transfer Learning with EfficientNetB0)

Stage 1: Binary classification → Biodegradable vs Non-Biodegradable
Stage 2: Multi-class classification → Predicts the exact waste category
Image Augmentation used for better generalization
Class Weights applied to handle class imbalance
Outputs include waste disposal suggestions

⚙️ **Tech Stack**
Python 
TensorFlow / Keras
NumPy, Pandas, Matplotlib
Google Colab (training)
Streamlit (deployment)

🌱 **Impact**

This system can:
Help in smart waste management
Encourage recycling & reusability
Support sustainability goals (SDG 12)
