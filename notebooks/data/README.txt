# NSL-KDD Intrusion Detection System

Derin öğrenme tabanlı saldırı tespit sistemi. CNN ve AE-CNN mimarileri karşılaştırılmıştır.

## Kullanılan Kütüphaneler
- TensorFlow / Keras
- Scikit-learn
- Pandas, NumPy
- Matplotlib, Seaborn

## Veri Seti
NSL-KDD — 125.973 eğitim, 22.544 test örneği  
İndirme: https://www.kaggle.com/datasets/hassan06/nslkdd

## Sonuçlar

| Model  | Accuracy | Precision | Recall | F1-Score |
|--------|----------|-----------|--------|----------|
| CNN    | 0.7515   | 0.9521    | 0.5932 | 0.7310   |
| AE-CNN | 0.7769   | 0.9764    | 0.6232 | 0.7608   |

AE-CNN, tüm metriklerde CNN'i geçmiştir.

## Görseller
![Confusion Matrix](images/confusion_matrices.png)
![Loss](images/loss_graphs.png)
![Accuracy](images/accuracy_graphs.png)
