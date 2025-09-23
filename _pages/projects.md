---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

---

## **BirdCLEF+ 2025 – Acoustic Biodiversity Challenge**  
**Conference:** CLEF 2025 | **Technologies:** Python, XGBoost, Spectrogram Analysis, Data Augmentation  
- Developed a scalable **one-vs-rest detection pipeline** with 206 per-species XGBoost models trained on log-mel spectrogram statistics and geo-contextual metadata.  
- Engineered **3,200-dimensional sparse binary features** via adaptive STFT-based frequency binning with class balancing.  
- Applied **targeted augmentation and rebalancing**, improving F1 scores from **0.00 → 0.72** for low-resource species.  
- Achieved **>0.90 mean AUC** across species in final evaluations.  

---

## **Data Ambiguity Quantification for Robust ML using Optimal Transport**  
**Technologies:** Python, Keras, Scikit-learn, Optimal Transport  
- Designed a framework leveraging **Optimal Transport** to maximize Wasserstein distance between optimized distributions, providing a rigorous **upper bound on generalization loss** (10× improvement over baselines).  
- Implemented **Leave-one-out CV** and **entropy-based ranking** to prioritize ambiguous samples for efficient annotation and improved classification accuracy.  

---

## **NeuroFraudGAN – Credit Card Fraud Detection with Synthetic Data**  
**Technologies:** Python, TensorFlow, GAN, Auto-NAS, Optimization  
- Synthesized **100k+ credit card transactions** from JPMorgan’s AIRSyntheticData, reducing class imbalance by **40%**.  
- Applied **Auto-NAS** for neural network optimization, improving training efficiency and scalability.  
- Achieved **96% accuracy** and **0.97 AUC-PR** through GAN-augmented training and hyperparameter tuning.  

---

## **Examination of Toxic Tweet Classification on Twitter**  
**Technologies:** Python, NLP, Transformers, Scikit-learn  
- Conducted large-scale analysis on **500k+ tweets** for hate speech and toxicity detection.  
- Built a **two-phase pipeline**: sentiment filtering with logistic regression → toxicity categorization with deep models.  
- Benchmarked **traditional ML (TF-IDF + LR)** against **transformer models (BERT)**, with class accuracies between **93–99%**.  

---

## **Evaluating ML & DL Architectures for NLP Tasks**  
**Technologies:** Python, TensorFlow, Keras, Scikit-learn  
- Achieved **88% accuracy** in sentiment analysis with optimized logistic regression.  
- Attained **99% accuracy** in NER using **LSTM**, outperforming classical models by 6%.  
- Enhanced text generation quality with **LSTM** and **GRU** through embedding fine-tuning.  

---

## **Social Media Marketing Optimization for Lead Generation**  
**Technologies:** A/B Testing, Tableau, Google Analytics  
- Reduced **CPC and CPM by 20%** via A/B testing and targeting optimization.  
- Built interactive dashboards for **CTR, ROAS, and relevance scores**, enabling data-driven marketing.  
- Achieved **30% cost efficiency improvement** through optimized budget allocation.  

---

## **Data Visualization in Football**  
**Technologies:** Python, Tableau, Pandas, TensorFlow  
- Analyzed **10,000+ player attributes**, identifying KPIs with **0.87 correlation** to overall ratings.  
- Generated **500+ shotmaps and heatmaps** for strategic team analysis.  
- Built position forecasting models with deep learning on player attributes.  

---

## **Image Compression Analysis (Coursework Project)**  
**Technologies:** MATLAB, Python, Linear Algebra, SVD  
- Compared **SVD-based compression** with **JPEG2000**, evaluating CR, PSNR, and SSIM.  
- Demonstrated JPEG2000’s superiority for medical imaging and archival storage.  
- Highlighted SVD’s flexibility for research and teaching contexts.  
