# İstanbul Mahalleleri İçin Deprem Risk Tahmini ve Açıklanabilir Yapay Zeka Analizi

Bu proje, İstanbul'daki mahallelerin yapı stoğunu kullanarak mahalle bazlı deprem risk skorlarını hesaplamak ve bu riskleri makine öğrenmesi modelleriyle tahmin ederek **açıklanabilir yapay zeka (Explainable AI)** yöntemleri ile analiz etmeyi amaçlamaktadır.

---

## 🎯 Projenin Amacı

- İstanbul'un mahalle düzeyindeki yapı stokunu veriye dayalı olarak analiz etmek
- Ortalama bina yaşı ve kat sayısına göre **göreli bir deprem risk skoru** oluşturmak
- Random Forest regresyon modeliyle risk skorunu tahmin etmek
- SHAP kütüphanesi ile model kararlarını şeffaf şekilde açıklamak
- Çeşitli görselleştirmeler ile sonuçları anlaşılır kılmak

Bu proje, afet öncesi risk yönetimi, şehir planlaması ve kamu bilgilendirmesi için önemli bir örnek çalışma niteliğindedir.

---

## 🧩 Kullanılan Veri Seti

Veri seti İstanbul Büyükşehir Belediyesi Açık Veri Portalı'ndan temin edilmiştir:

**Mahalle Bazlı Bina Sayıları**

İçeriği:
- İlçe adı
- Mahalle adı ve benzersiz kimlik numarası (mahaller_uavt)
- Bina yapım yılları (1980 öncesi, 1980–2000 arası, 2000 sonrası)
- Kat sayısı kategorileri (1–4, 5–9, 9–19 kat arası)

---

## 🛠 Kullanılan Teknolojiler ve Kütüphaneler

- Python >= 3.8
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- shap

---

## 📝 Proje Akışı

1. **Veri Ön İşleme**
   - Kodlama türünün belirlenmesi
   - Verinin temizlenmesi ve dönüştürülmesi
2. **Temel Analizler ve Görselleştirmeler**
   - İlçe bazlı bina yaşı ve kat dağılımları
   - Mahalle bazlı toplam bina sayısı, ortalama bina yaşı, ortalama kat sayısı hesaplamaları
   - Grafikler (bar chart, pie chart, scatter plot, heatmap)
3. **Risk Skoru Hesaplama**
   - Ortalama bina yaşı ve kat sayısına göre normalize edilmiş göreli risk skoru
4. **Makine Öğrenmesi Modeli**
   - Random Forest regresyon modeli eğitimi
   - Model performans ölçümü (MSE, R²)
5. **Model Kararlarının Açıklanması**
   - SHAP değerleri ile en etkili değişkenlerin analizi
   - SHAP force plot ile tahminlerin detaylı açıklaması
6. **Sonuçların Mahalle Düzeyinde Raporlanması**
   - Gerçek ve tahmini risk skorlarının tablo halinde sunulması

---

## 🔍 Sonuç ve Kazanımlar

- İstanbul genelinde mahalle risk seviyeleri sayısal olarak ortaya konmuştur.
- Yapı stoğunun ortalama yaş ve kat sayısına göre riskli bölgeler belirlenmiştir.
- Modelin karar verme süreci şeffaf şekilde açıklanmıştır.
- Veri bilimi, makine öğrenmesi ve açıklanabilir yapay zekanın birlikte nasıl kullanılabileceği gösterilmiştir.

---


## Linkedın hesabım : www.linkedin.com/in/buse-kılıç-19b282280
## Medium hesabım : https://medium.com/@buself.021
