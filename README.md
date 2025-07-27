# Karar Ağaçları ile Iris Veri Seti Sınıflandırması

Bu proje, makine öğrenimi algoritmalarından Karar Ağaçları (Decision Trees) sınıflandırıcısını kullanarak ünlü Iris çiçek veri setindeki türleri (Setosa, Versicolor, Virginica) tahmin etmeyi amaçlamaktadır. Not defteri, veri setinin temel incelemesini, Karar Ağacı modelinin eğitimini, performans değerlendirmesini (doğruluk skoru ve karışıklık matrisi ile) ve özellik önemlerinin analizini adım adım göstermektedir.

## İçerik

Bu depo aşağıdaki Jupyter Notebook dosyasını içermektedir:

* **`iris.ipynb`**: Bu not defteri, Iris veri setini yükler, veri setini eğitim ve test kümelerine ayırır. Ardından, bir Karar Ağacı sınıflandırıcısı eğitir, modelin tahmin performansını değerlendirir (doğruluk skoru ve karışıklık matrisi kullanarak) ve modelin hangi özelliklere daha çok önem verdiğini gösteren özellik önemlerini (feature importances) analiz eder.

## Özellikler

* Iris veri setinin temel istatistikleri ve yapısının incelenmesi.
* Karar Ağacı sınıflandırma algoritmasının scikit-learn kullanılarak uygulanması.
* Modelin doğruluk skoru ve karışıklık matrisi ile performans değerlendirmesi.
* Karar Ağacının dallanma kararlarında hangi özelliklerin daha etkili olduğunu gösteren özellik önemlerinin hesaplanması ve görselleştirilmesi.
* Veri seti bölme (`train_test_split`) gibi ön işleme adımları.

## Kullanılan Teknolojiler

* **Python**
* **Pandas**: Veri manipülasyonu ve analizi için.
* **NumPy**: Sayısal işlemler için.
* **Matplotlib**: Veri görselleştirmeleri için.
* **Scikit-learn**: Karar Ağacı modeli, veri setini yükleme (`load_iris`), veri bölme ve model değerlendirme metrikleri için.
