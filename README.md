# Fashion MNIST Veri Seti Üzerinde Makine Öğrenimi Modelleri

Bu proje, TensorFlow kütüphanesi kullanılarak Fashion MNIST veri seti üzerinde makine öğrenimi modelleri oluşturmayı ve değerlendirmeyi amaçlamaktadır. Fashion MNIST, 10 farklı giyim kategorisinden oluşan bir veri setidir ve her bir görüntü 28x28 piksel boyutundadır.

## Proje Amacı
Projenin amacı, giyim eşyalarını doğru bir şekilde sınıflandırmak için en iyi performansı gösteren makine öğrenimi modelini belirlemektir. Bu amaç doğrultusunda Logistic Regression ve Random Forest modelleri kullanılmış ve değerlendirilmiştir.

## Kullanılan Teknolojiler ve Araçlar
- Python programlama dili
- TensorFlow ve Keras kütüphaneleri
- Jupyter Notebook (Google Colab)
- Matplotlib ve diğer veri görselleştirme araçları
- Scikit-learn kütüphanesi (model değerlendirme için)

## Veri Seti
Fashion MNIST veri seti, 60,000 eğitim örneği ve 10,000 test örneği içermektedir. Her bir örnek, 0 ile 9 arasında bir sınıf etiketiyle (örneğin, 0 tişört, 1 pantolon, vb.) etiketlenmiştir.

## Değerlendirme Sonuçları
### Logistic Regression Modeli
- Accuracy (Doğruluk): 0.8445
- Precision (Kesinlik): 0.8434
- Recall (Duyarlılık): 0.8445
- F1-score: 0.8437

### Random Forest Modeli
- Accuracy (Doğruluk): 0.8775
- Precision (Kesinlik): 0.8764
- Recall (Duyarlılık): 0.8775
- F1-score: 0.8762

Random Forest modelinin Logistic Regression modeline kıyasla daha yüksek performans gösterdiği görülmektedir.

## Nasıl Kullanılır
Projenin Jupyter Notebook dosyasını açarak adım adım model oluşturma, eğitme ve değerlendirme süreçlerini görebilirsiniz.

## Ek Bilgiler
Projeyi çalıştırmak için TensorFlow ve diğer bağımlılıkların kurulu olması gerekmektedir. Gerekli bağımlılıkları yüklemek için aşağıdaki komutları kullanabilirsiniz:

```bash
pip install tensorflow matplotlib scikit-learn
