# 🫘 Dry Bean Dataset Üzerinde Makine Öğrenmesi Pipeline Uygulaması

Bu projede, UCI Machine Learning Repository'den alınan Dry Bean Dataset kullanılarak uçtan uca bir makine öğrenmesi süreci uygulanmıştır.

## 🔹 Proje Adımları
- Veri Yükleme ve İnceleme
- Eksik Veri ve Aykırı Değer İşlemleri
- Özellik Ölçekleme (StandardScaler)
- Boyut İndirgeme (PCA & LDA)
- Farklı Makine Öğrenmesi Modellerinin Uygulanması
- Nested Cross-Validation ile Model Değerlendirme
- ROC Eğrileri ve AUC Skorlarının Hesaplanması

## 🔹 Kullanılan Modeller
- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost
- Naive Bayes

## 📊 Sonuçlar
En yüksek doğruluk, **XGBoost (Ham Veri)** modeli ile elde edilmiştir:
- Accuracy: %91.42
- F1-Score: %92.06

ROC eğrileri her sınıf için ayrı ayrı çizilmiş ve AUC skorları neredeyse 1.0’a ulaşmıştır.

## 📁 İçerik
- `dry_bean_pipeline.ipynb` : Tüm kodlar ve grafikler
- `rapor.pdf` : Kısa proje raporu
- `grafikler/` : PCA, LDA, ROC görselleri

## 🛠 Kullanılan Kütüphaneler
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost

## 📌 Not
Bu proje Üsküdar Üniversitesi Fen Bilimleri Enstitüsü Makine Öğrenmesi dersi ara sınav ödevi kapsamında hazırlanmıştır.

---

🔗 **Veri Seti Kaynağı:**  
https://archive.ics.uci.edu/ml/datasets/Dry+Bean+Dataset
