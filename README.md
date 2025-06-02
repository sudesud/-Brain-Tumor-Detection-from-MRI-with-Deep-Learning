🧠 Brain Tumor Detection from MRI with Deep Learning
Bu proje, beyin MRI görüntülerinden tümör var mı yok mu olduğunu sınıflandırmak için bir CNN tabanlı derin öğrenme modeli kullanır. Model, halka açık bir MRI veri kümesiyle eğitilmiş ve yüksek doğrulukla tahmin yapabilmektedir.

🚀 Özellikler
MRI görüntülerinden binary sınıflandırma (tümör var(hangi tür)/yok)

Keras/TensorFlow ile CNN modeli

Görsel ön işleme, eğitim, test ve performans analizi

📁 Kullanım
bash
Kopyala
Düzenle
git clone https://github.com/kullaniciadi/brain-tumor-detection.git
pip install -r requirements.txt
jupyter notebook MRI.ipynb
📊 Veri
Kullanılan veri kümesi Kaggle’dan alınmıştır ve tumor, no_tumor sınıflarını içerir.

📈 Başarı
Model, eğitim ve test verisinde yüksek doğruluk (%98.9) elde etmiştir. Sonuçlar confusion matrix ve ROC eğrisi ile görselleştirilmiştir.


