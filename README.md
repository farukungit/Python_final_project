# Kredi Kartı Müşteri Kaybı Projesi

Bu projede, kredi kartı müşterilerinin kaybını (attrition) tahmin etmek amacıyla makine öğrenmesi modelleri kullanılmıştır. Veri seti, müşterilerin demografik bilgilerini ve banka ile olan ilişkilerini içermektedir. Proje, yüksek kayıp riski taşıyan müşterilere yönelik stratejiler geliştirmeyi hedeflemektedir.

## Kullanılan Yöntemler

- **Veri Temizleme**: Eksik veriler kontrol edilip, uygun şekilde dolduruldu veya silindi.
- **Öznitelik Seçimi (Feature Selection)**: Müşteri davranışlarını etkileyen özellikler seçildi.
- **Makine Öğrenmesi**: **Random Forest** algoritması kullanılarak model eğitildi.
- **Model Değerlendirme**: **Confusion Matrix**, **classification report** gibi metriklerle modelin başarısı değerlendirildi.

## Proje Adımları

1. **Veri Yükleme ve İnceleme**: 
   - Veri seti yüklendi ve temel yapısı incelendi.
   
2. **Veri Temizleme**:
   - Eksik değerler kontrol edildi ve uygun şekilde işlendi.
3. **Görselleştirme**:
   - **Müşteri Yaş Dağılımı**: Müşteri yaşlarının dağılımı **histogram** ve **kernel density estimate** (KDE) grafiği ile görselleştirildi.
   - **Cinsiyet Dağılımı**: Müşteri cinsiyetlerinin dağılımı **bar plot** ile görselleştirildi.
   - **Eğitim Seviyesi Dağılımı**: Müşterilerin eğitim seviyeleri **bar plot** ile görselleştirildi.
   - **Gelir Kategorisi Dağılımı**: Müşterilerin gelir seviyelerinin dağılımı **bar plot** ile görselleştirildi.
   - **Müşteri Kayıp Durumu (Attrition)**: Müşteri kayıp durumu, **bar plot** kullanılarak görselleştirildi.
   - **Müşteri Kart Kategorisi ve Gelir Dağılımı**: **Isı haritası** (heatmap) ile kart kategorileri ve gelir kategorileri arasındaki ilişki görselleştirildi.
   - **Kayıp Oranı ve İletişim Sayısı**: **Scatter plot** ile kayıp oranı ve banka ile iletişim sayısının ilişkisi görselleştirildi.

4. **Model Eğitimi**:
   - **Random Forest** modeli ile eğitim yapıldı.

5. **Model Değerlendirmesi**:
   - Test verisi üzerinde modelin başarısı **classification report** ve **confusion matrix** ile değerlendirildi.

6. **Hiperparametre Optimizasyonu**:
   - **GridSearchCV** ile modelin hiperparametreleri optimize edilerek en iyi parametreler belirlendi.

7. **Tahminler ve Stratejiler**:
   - Kayıp müşteri tahminleri yapıldı ve kayıp oranlarını azaltmak için stratejiler geliştirildi.



