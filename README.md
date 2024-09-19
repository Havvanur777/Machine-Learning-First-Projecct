# Machine-Learning-First-Projecct
# Movie Ratings Analysis Project

## Proje Açıklaması
Bu proje, film değerlendirme verileri üzerinde hem gözetimli hem de gözetimsiz öğrenme tekniklerini uygulamayı amaçlamaktadır. Gözetimli öğrenme için regresyon analizi ve gözetimsiz öğrenme için K-means kümeleme kullanılmıştır.

## Veri Seti
Veri seti, film değerlendirmelerini içeren büyük bir veri kümesidir. [Kaggle Movie Ratings Dataset](https://www.kaggle.com/datasets/kaggle/input/the-movies-dataset/ratings.csv).

## Kullanılan Yöntemler

### Gözetimli Öğrenme
- **Lineer Regresyon**: Film değerlendirmelerini tahmin etmek için kullanıldı.
- **Performans Metrikleri**: Ortalama Kare Hata (MSE), Ortalama Mutlak Hata (MAE), R² Skoru.

### Gözetimsiz Öğrenme
- **K-means Kümeleme**: Kullanıcı ve film ID'lerine göre kümeler oluşturuldu.
- **Performans**: Kümeleme sonuçları görselleştirildi.

## Hiperparametre Optimizasyonu
KNN sınıflandırıcısı için hiperparametre optimizasyonu Grid Search yöntemi ile gerçekleştirildi.

## Sonuçlar
- **Regresyon Modeli Performansı**: MSE, MAE, R² Skoru hesaplandı.
- **K-means Kümeleme**: Kümeleme sonuçları görselleştirildi ve kümelerin özetleri çıkarıldı.
- **KNN Sınıflandırıcısı Performansı**: Karışıklık matrisi, doğruluk, kesinlik, duyarlılık ve F1 puanı hesaplandı.

## Kurulum ve Kullanım
1. Python ve gerekli kütüphanelerin kurulu olduğundan emin olun.
2. Notebook dosyasını açın ve kodları çalıştırın.

## Notlar
Bu proje Kaggle üzerinde çalıştırıldı ve tüm kodlar Kaggle Notebook'unda test edilmiştir. Kodları kendi bilgisayarınızda çalıştırırken performans sorunlarıyla karşılaşabilirsiniz.

## Kaggle linki 
https://www.kaggle.com/code/havvanurkarakaya/the-movies-dataset-first-machine-learning-project 
