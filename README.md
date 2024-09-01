Bu proje, derin öğrenme tekniklerinden biri olan Evrişimli Sinir Ağları (CNN) kullanarak el yazısı rakamlarının otomatik olarak tanınmasını hedeflemektedir. MNIST veri seti üzerinde eğitilen model, verilen bir el yazısı rakam görüntüsünü yüksek doğrulukla sınıflandırabilmektedir.

# Ana Özellikler:

Veri Hazırlığı: MNIST veri setinin okunması, normalleştirilmesi ve CNN modeline uygun hale getirilmesi.
Model Eğitimi: Keras kütüphanesi kullanılarak CNN mimarisinin oluşturulması ve modelin veri seti üzerinde eğitilmesi.
Tahmin: Eğitilen modelin, yeni ve daha önce görmediği el yazısı rakam görüntülerini doğru bir şekilde sınıflandırması.
Model Kaydı: Eğitilen modelin, gelecekte kullanılmak üzere kaydedilmesi.

# Nasıl Kullanılır:

Gerekli Kütüphanelerin Kurulması: TensorFlow, Keras, NumPy, Pandas gibi kütüphanelerin kurulması.
Veri Setinin Hazırlanması: MNIST veri setinin projenin çalışma dizinine yerleştirilmesi.
Kodun Çalıştırılması: Jupyter Notebook veya Python ortamında kodun çalıştırılması.

# Kodun Temel Mantığı:

Veri Yükleme: MNIST veri seti Pandas kütüphanesi ile okunur.
Veri Ön İşleme: Veri normalleştirilir ve CNN modeline uygun bir şekle dönüştürülür.
Model Oluşturma: Keras kullanarak sıralı bir CNN modeli oluşturulur.
Model Derleme: Model, kayıp fonksiyonu, optimizasyon algoritması ve metrikler belirlenerek derlenir.
Model Eğitimi: Model, eğitim verisi üzerinde belirlenen epoch sayısı kadar eğitilir.
Model Değerlendirme: Modelin performansı, test verisi üzerinde değerlendirilir.
Model Kaydı: Eğitilen model, joblib kütüphanesi ile kaydedilir.
