# Yapay Zeka Alanında Maaş Tahmini

Bu proje, yapay zeka alanında çalışan bir işletmenin, iş ilanı açtığında adayın profiline göre yüksek mi yoksa düşük mü maaş teklif etmesi gerektiğini tahmin etmek için yapılmıştır.

Amaç, adayın eğitim durumu, deneyimi, çalıştığı ülke gibi bilgilere bakarak bir sınıflandırma modeli ile doğru maaş aralığını tahmin etmektir.

## Kullanılan Yöntem

- Veri madenciliği tekniği: Sınıflandırma (Classification)
- Algoritma: Random Forest
- Başarı oranı: %90 üzeri doğruluk

## Veri Seti

- Kaynak: [Kaggle - AI Job Dataset](https://www.kaggle.com/datasets/mukuldeshantri/ecommerce-fashion-dataset)
- Satır sayısı: ~15.000
- Özellikler: Eğitim, deneyim, sektör, ülke, yan hak puanı, vb.

## Çıktı

Model, her aday için sonucu şu şekilde verir:

- **0:** Düşük maaş teklifi yapılmalı
- **1:** Yüksek maaş teklifi yapılmalı

## Amaç ve Faydası

Bu proje sayesinde işletmeler:

- Maaş teklifini veriye dayalı şekilde belirleyebilir
- Aday kayıplarını önleyebilir
- İnsan kaynakları süreçlerini iyileştirebilir

## Geliştiren

Emir DEMİRCİ  
Veri Madenciliği Final Projesi (2025)
