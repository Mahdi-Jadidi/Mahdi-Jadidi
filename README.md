<div align="center">

# Mahdi Jadidi

**ML Engineer · Building production-ready machine learning systems**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/mahdi-m-jadidi)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:mahdi.m.jadidi@gmail.com)
[![CV](https://img.shields.io/badge/CV-Download-2E7D32?style=flat&logo=googledrive&logoColor=white)](https://github.com/Mahdi-Jadidi/Mahdi-Jadidi/blob/main/Mahdi_Jadidi_CV.pdf)
![Location](https://img.shields.io/badge/📍-Tehran,_Iran-6B6B6B?style=flat)

</div>

---

I design ML pipelines that work — with **leakage-safe evaluation**, **time-aware validation**, and models that generalize beyond the training set. My projects span fraud detection, learning-to-rank, knowledge tracing, and computer vision. I treat negative results as findings, not failures.

---

## Featured Projects

<table>
<tr>
<td width="50%">

### 🔍 [retail-fraud-classifier](https://github.com/Mahdi-Jadidi/retail-fraud-classifier)
4-model ensemble fraud detection with semi-supervised pseudo-labeling. Strict no-leakage chronological split, F1-weighted ensembling, and a student LightGBM model trained on high-confidence pseudo-labels.

![F1](https://img.shields.io/badge/F1-0.817-2196F3?style=flat)
![AUC](https://img.shields.io/badge/AUC-0.915-2196F3?style=flat)
![PR--AUC](https://img.shields.io/badge/PR--AUC-0.914-00897B?style=flat)

`LightGBM` `XGBoost` `CatBoost` `Random Forest` `pseudo-labeling`

</td>
<td width="50%">

### 🎯 [job-candidate-ranker](https://github.com/Mahdi-Jadidi/job-candidate-ranker)
Learning-to-rank pipeline matching 118K job applications to 5K postings. 53 engineered candidate–job features, out-of-fold target encoding, and a blended gradient-boosted ensemble evaluated with GroupKFold.

![NDCG@10](https://img.shields.io/badge/NDCG@10-0.875-7B1FA2?style=flat)
![MAP@5](https://img.shields.io/badge/MAP@5-0.682-7B1FA2?style=flat)

`HistGradientBoosting` `learning-to-rank` `GroupKFold` `scikit-learn`

</td>
</tr>
<tr>
<td width="50%">

### 🧠 [student-performance-lstm](https://github.com/Mahdi-Jadidi/student-performance-lstm)
LSTM knowledge tracing on ASSISTments 2017. Sequential modeling of student interaction history — skill type, hint usage, consecutive errors — with engineered cross-features. Production-ready modular codebase.

![AUC](https://img.shields.io/badge/AUC-0.904-F57F17?style=flat)
![Accuracy](https://img.shields.io/badge/Accuracy-80.8%25-F57F17?style=flat)

`PyTorch` `LSTM` `knowledge tracing` `BCEWithLogitsLoss`

</td>
<td width="50%">

### 🥦 [produce-classifier-cnn](https://github.com/Mahdi-Jadidi/produce-classifier-cnn)
CNN classifier for 10 fruit and vegetable classes with Grad-CAM visualization and robustness analysis: −74% accuracy on grayscale, −70% on channel swap. Reveals strong color-shortcut dependence.

![Accuracy](https://img.shields.io/badge/Accuracy-87.75%25-00695C?style=flat)
![Grayscale](https://img.shields.io/badge/Grayscale_drop-−74%25-D84315?style=flat)

`PyTorch` `Grad-CAM` `robustness testing` `data augmentation`

</td>
</tr>
<tr>
<td width="50%">

### 📰 [article-shares-prediction](https://github.com/Mahdi-Jadidi/article-shares-prediction)
Stacking regressor predicting online article virality on 30K articles. Polynomial feature expansion to 134 features, log-target transform, permutation-based feature selection to top 50.

![CV MSLE](https://img.shields.io/badge/CV_MSLE-0.00691-388E3C?style=flat)

`LightGBM` `XGBoost` `CatBoost` `Ridge` `stacking`

</td>
<td width="50%">

### 🚗 [Used-Car-Price-Estimation](https://github.com/Mahdi-Jadidi/Used-Car-Price-Estimation-with-NLP-vision-Extensions)
End-to-end pipeline: Selenium scraping → multilingual translation → sentence-transformer embeddings → price prediction. Modular `src/` layout, Dockerfile, and GitHub Actions CI.

![Docker](https://img.shields.io/badge/Docker-✓-2196F3?style=flat)
![CI/CD](https://img.shields.io/badge/CI%2FCD-GitHub_Actions-2196F3?style=flat)

`Selenium` `sentence-transformers` `deep-translator` `SQLite` `Docker`

</td>
</tr>
</table>

---

## Stack

| Domain | Tools |
|---|---|
| **ML / DL** | PyTorch · scikit-learn · LightGBM · XGBoost · CatBoost |
| **NLP / Vision** | sentence-transformers · Grad-CAM · OpenCV · deep-translator |
| **Data** | pandas · NumPy · SQL · PostgreSQL · SQLite |
| **Engineering** | Python · Docker · GitHub Actions · Selenium · Jupyter |
| **Domains** | Tabular ML · Computer Vision · Sequential / RNN · Learning to Rank · NLP |

---

## How I work

**No leakage** — Chronological splits, train-only normalization, out-of-fold encoding. Every pipeline validated against the scenario it faces in production.

**Metrics that matter** — F1 for imbalanced classification, NDCG for ranking, MSLE for skewed regression targets. Chosen before touching the model, not after.

**Honest analysis** — If feature engineering hurts, I say so (see [california-housing-mlp](https://github.com/Mahdi-Jadidi/california-housing-mlp)). If the model relies on color shortcuts, I show it (see [produce-classifier-cnn](https://github.com/Mahdi-Jadidi/produce-classifier-cnn)).

**Production structure** — Modular `src/` layouts, `requirements.txt`, Dockerfiles, CI workflows. Code that runs the same on any machine.

---

<div align="center">

**Open to ML Engineering and Data Science roles · Remote or Tehran · Available for research collaborations**

[LinkedIn](https://linkedin.com/in/mahdi-m-jadidi) · [mahdi.m.jadidi@gmail.com](mailto:mahdi.m.jadidi@gmail.com) · [CV](https://github.com/Mahdi-Jadidi/Mahdi-Jadidi/blob/main/Mahdi_Jadidi_CV.pdf)

</div>
