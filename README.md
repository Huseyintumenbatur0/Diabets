# Diabetes Veri Seti Projesi

Bu proje, diabetes (şeker hastalığı) ile ilgili bir veri setinin analizi ve modelleme sürecini kapsamaktadır. Proje, hastalığın tanısında kullanılan belirli özelliklerin analizi ve modelleme amacıyla gerçekleştirilmiştir.

## Proje Amacı

Projenin amacı, diabetes hastalığı ile ilişkili özelliklerin incelenmesi, veri temizliği işlemlerinin gerçekleştirilmesi ve makine öğrenimi algoritmalarının uygulanmasıdır. Bu süreçte, Lineer Regresyon ve K-Nearest Neighbors (KNN) algoritmaları kullanılarak model oluşturulmuş ve sonuçlar karşılaştırılmıştır.

## Kullanılan Teknolojiler

- **Python**: Proje, Python programlama dili ile geliştirilmiştir.
- **Pandas**: Veri analizi ve manipülasyonu için kullanılmıştır.
- **NumPy**: Sayısal işlemler için kullanılmıştır.
- **Matplotlib** ve **Seaborn**: Veri görselleştirme için kullanılmıştır.
- **Scikit-learn**: Makine öğrenimi algoritmalarının uygulanması için kullanılmıştır.

## Veri Seti Hakkında

Veri seti, diabetes hastalığına sahip olan bireylerin çeşitli sağlık göstergeleri ile birlikte bir hedef değişken içermektedir. Aşağıdaki değişkenleri içermektedir:

- **age**: Bireyin yaşı
- **sex**: Bireyin cinsiyeti
- **bmi**: Vücut Kütle İndeksi
- **bp**: Kan basıncı
- **s1 - s6**: Diğer sağlık göstergeleri
- **target**: Diabetes hastalığı durumu (0 veya 1)

## Proje Adımları

1. **Veri Yükleme**: Gerekli kütüphaneler import edilerek veri seti yüklenir.
2. **Veri Önizleme**: Veri setinin ilk birkaç satırı incelenir.
3. **Veri Normalizasyon/Standartizasyon**: Özelliklerin ölçeklendirilmesi sağlanır.
4. **Modelleme**:
   - **Lineer Regresyon**: İlk model olarak kullanılır.
   - **K-Nearest Neighbors (KNN)**: İkinci model olarak kullanılır.
5. **Sonuçların Karşılaştırılması**: Her iki modelin sonuçları karşılaştırılarak grafik üzerinde gösterilir.
6. **Sonuçların Değerlendirilmesi**: Model başarı metrikleri (ortalama kare hatası, R² skoru vb.) hesaplanır.

## Kullanım

Proje dosyalarını indirdikten sonra, aşağıdaki adımları takip ederek projeyi çalıştırabilirsiniz:

1. Gerekli kütüphaneleri yükleyin:

   ```bash
   pip install -r requirements.txt
