# Customer Analytics for E-Commerce — ML
 
E-ticaret platformu müşterilerinin davranışlarını analiz eden gözetimli öğrenme projesi.  
Supervised machine learning project analyzing customer behavior on an e-commerce platform.
 
---
 
## Veri Seti / Dataset
 
Kaggle'dan alınan iki ayrı CSV dosyası kullanıldı / Two CSV files from Kaggle:
 
- `e_commerce_class.csv` → Churn tahmini için / For churn prediction (`Churned` target)
- `e_commerce_reg.csv` → Yaşam boyu değer tahmini için / For lifetime value prediction (`Lifetime_Value` target)
 
---
 
## Görevler / Tasks
 
### Task 0 — EDA (Keşifsel Veri Analizi / Exploratory Data Analysis)
- Eksik değer ve aykırı değer analizi / Missing value & outlier analysis
- Korelasyon heatmap görselleştirmesi / Correlation heatmap visualization
 
### Task 1 — Binary Classification (Churn Tahmini / Churn Prediction)
Hangi müşteriler platformu terk edecek? / Which customers will leave the platform?
- Logistic Regression
- Random Forest
- HistGradientBoosting
- GridSearchCV + Stratified K-Fold cross-validation
 
### Task 2 — Regression (Yaşam Boyu Değer / Lifetime Value)
Müşterinin platforma toplam katkısı ne olacak? / What is the total value of a customer?
- Ridge Regression
- Random Forest Regressor
- HistGradientBoosting Regressor
 
---
 
## Stack
 
`Python` · `scikit-learn` · `pandas` · `matplotlib` · `Google Colab`
