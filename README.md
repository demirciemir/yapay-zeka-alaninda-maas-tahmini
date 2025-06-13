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

## Görseller

![7_feature_importance](https://github.com/user-attachments/assets/04f2e530-f73d-462b-b38b-14f97d12a832)
![6_confusion_matrix](https://github.com/user-attachments/assets/96a7db2d-4482-42f6-86e0-01e2217df921)
![5_maas_etiket_dagilimi](https://github.com/user-attachments/assets/0e53a0ec-2677-4ee3-b35c-4295d90064c7)
![4_endustri_maas](https://github.com/user-attachments/assets/3278b648-30e4-4e79-8ddb-2f0f567b983f)
![3_deneyim_dagilimi](https://github.com/user-attachments/assets/04a1fd8b-817c-4bd4-b43d-f608b1b0162f)
![2_egitim_dagilimi](https://github.com/user-attachments/assets/50d77f43-9b0f-4e5a-b577-ab1c954c3014)
![1_maas_dagilimi](https://github.com/user-attachments/assets/832fd42e-e8ad-4d07-8015-42f6c33ab3fc)

  

## Geliştiren

Emir DEMİRCİ  
Veri Madenciliği Final Projesi (2025)
