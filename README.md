# Şeker Hastalığı Tahmini Projesi

Bu proje, şeker hastalığını tahmin etmek amacıyla lojistik regresyon modelinin kullanımını içermektedir. Projede bir biyometrik veri seti kullanılarak bireylerin özellikleri analiz edilmiş ve şeker hastalığı riskini tahmin eden bir model geliştirilmiştir.

## Amaç
Projede, bireylerin şu özelliklerine dayanarak şeker hastası olup olmadıklarını tahmin etmek hedeflenmiştir:
- Gebelik sayısı (Pregnancies)
- Glikoz seviyesi (Glucose)
- Kan basıncı (BloodPressure)
- Deri kalınlığı (SkinThickness)
- İnsülin seviyesi (Insulin)
- Vücut kitle indeksi (BMI)
- Genetik yatkınlık fonksiyonu (DiabetesPedigreeFunction)
- Yaş (Age)

Hedef değişken `Outcome` olup, 1 değeri bireyin şeker hastası olduğunu, 0 değeri ise olmadığını belirtir.

## Kullanılan Teknolojiler
Bu projede aşağıdaki Python kütüphaneleri ve araçları kullanılmıştır:
- **Pandas**: Veri işleme ve analizi için kullanıldı.
- **NumPy**: Sayısal hesaplamalar için kullanıldı.
- **Matplotlib & Seaborn**: Veri görselleştirme için kullanıldı.
- **Scikit-learn**: Makine öğrenmesi modelleme ve değerlendirme için kullanıldı.

## Proje Adımları
1. **Veri Yükleme ve İnceleme**:
   - Veri seti yüklendi ve eksik değerler kontrol edildi.
2. **Hedef Değişken Analizi**:
   - `Outcome` değişkeninin sınıf dağılımı analiz edildi ve görselleştirildi.
3. **Lojistik Regresyon Modeli**:
   - Bireylerin özelliklerine dayalı olarak lojistik regresyon modeli eğitildi.
4. **Model Performans Değerlendirmesi**:
   - Doğruluk oranı, karışıklık matrisi ve ROC eğrisi gibi metrikler hesaplandı.

## Sonuç
Bu proje, biyometrik ölçümlere dayanarak şeker hastalığını tahmin etmek için etkili bir model sunmaktadır. Sonuçlar doğrultusunda, modelin performansı değerlendirilmiş ve iyileştirme potansiyelleri belirlenmiştir.

