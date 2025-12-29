# Financial Sentiment Analysis

Bu projede finansal metinler üzerinde duygu analizi (sentiment analysis) yapılmıştır.
Veri seti Kaggle platformundan alınmıştır ve doğal dil işleme (NLP) teknikleri kullanılmıştır.

## Veri Seti
- Kaynak: Kaggle – Financial Sentiment Analysis Dataset
- İçerik: Finansal haber ve metin cümleleri
- Etiketler: negative, neutral, positive

## Kullanılan Yöntemler
- Metin temizleme (lowercase, özel karakterlerin kaldırılması)
- TF-IDF vektörleştirme
- Makine öğrenmesi tabanlı sınıflandırma modeli
- Model değerlendirme:
  - Accuracy
  - Precision
  - Recall
  - F1-score
- Confusion Matrix ve görselleştirmeler

## Görselleştirmeler
- Sınıf dağılımı (pasta grafiği)
- Confusion matrix (sayısal ve grafik)
- Sınıf bazlı performans karşılaştırmaları

## Sonuçlar
Model, neutral ve positive sınıflarında başarılı sonuçlar üretmiştir.
Negative sınıfında ise veri setindeki sınıf dengesizliği nedeniyle performans düşüklüğü gözlemlenmiştir.
Bu nedenle model performansı değerlendirilirken F1-score metriği esas alınmıştır.

## Dosyalar
- `finalproje.ipynb` : Proje notebook dosyası

