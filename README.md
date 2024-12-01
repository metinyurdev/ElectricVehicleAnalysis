# Elektrikli Araç Pazar Analizi Projesi

## 📊 Proje Hakkında
Bu proje, elektrikli araç pazarındaki eğilimleri analiz etmek ve enerji altyapısı planlamalarına yönelik stratejik içgörüler sağlamak amacıyla geliştirilmiştir. Özellikle **Seattle şehri** ve **Tesla marka araçlar** üzerine yapılan detaylı analizler, sektörün geleceğine ışık tutacak önemli bulgular sunmaktadır.

**Aygaz A.Ş.** gibi fosil enerji üreticilerine, elektrikli araçların pazar etkisi ve Tesla'nın neden pazar lideri olduğu gibi kritik bilgiler sunulmuştur. Bu analizler, çevre dostu enerji kaynaklarına yönelik yatırımlara rehberlik edecek veriler içermektedir.

## 🚀 Proje Amaçları
- Elektrikli araçların şehir bazındaki dağılımlarını analiz etmek
- Tesla'nın pazar liderliğini incelemek ve nedenlerini açıklamak
- Elektrikli araç kullanımı ile hibrit araç kullanımı arasındaki oranları karşılaştırmak
- Şehir bazında elektrikli araçların hangi markalar tarafından daha çok tercih edildiğini belirlemek
- Enerji ve yakıt sektöründeki firmalar için stratejik içgörüler sağlamak

## 📂 Veri Seti
- Kaggle'dan alınmıştır: [Electric Vehicle Population Data](https://www.kaggle.com/datasets/mariusborel/electric-vhicule-population-data)

### Veri Seti Yapısı
Veri seti toplamda **200.000+ satır** ve **17 sütun** içermektedir. Örnek sütunlar:
- **`Model`**: Aracın modeli (ör. Tesla Model S)
- **`Make`**: Üretici firma (ör. Tesla, Nissan)
- **`Electric Range`**: Aracın tam dolu batarya ile gidebileceği mesafe (mil cinsinden)
- **`City`**: Aracın kayıtlı olduğu şehir (ör. Seattle)

### Ölçekler
- **Electric Range (Menzil):** Sürekli sayısal bir değişken (mil cinsinden)
- **City (Şehir):** Kategorik değişken
- **Make (Marka):** Kategorik değişken
- **Electric Vehicle Type (Araç Türü):** Plug-in veya BEV (Battery Electric Vehicle)

## 🧰 Kullanılan Teknolojiler ve Kütüphaneler

| Teknoloji / Araç             | Açıklama                                           |
|------------------------------|---------------------------------------------------|
| ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) | Veri analizi ve işleme.                           |
| ![Pandas](https://img.shields.io/badge/-Pandas-150458?style=flat&logo=pandas&logoColor=white) | Veri manipülasyonu ve analiz işlemleri.           |
| ![Matplotlib](https://img.shields.io/badge/-Matplotlib-FF4F8B?style=flat&logo=python&logoColor=white) | Veri görselleştirme.                              |
| ![Seaborn](https://img.shields.io/badge/-Seaborn-5E5C5C?style=flat&logo=python&logoColor=white) | Gelişmiş veri görselleştirme.                     |
| ![Kaggle](https://img.shields.io/badge/-Kaggle-20BEFF?style=flat&logo=kaggle&logoColor=white) | Veri seti ve proje paylaşımı platformu.           |

---

## ⚙️ Proje Adımları
1. **Veri Toplama:** Kaggle'dan elde edilen elektrikli araç verileri kullanıldı.
2. **Veri Temizleme:** Eksik verilerin tespiti, doldurulması ve veri manipülasyonu yapıldı.
3. **Keşifsel Veri Analizi (EDA):** Verinin görselleştirilmesi ve anlamlı desenlerin ortaya çıkarılması.
4. **Analizler:** 
   - Elektrikli araç kullanım oranlarının analizi
   - Şehirler bazında araç dağılımlarının incelenmesi
   - Tesla'nın neden pazar lideri olduğunun analiz edilmesi
5. **Sonuçlar:** 
   - Tesla'nın 8 kat daha fazla tercih edilme sebebi
   - Elektrikli araçların hibritlere kıyasla üstünlüğü
6. **Raporlama:** Analizlerin dokümante edilmesi ve bulguların paylaşılması.

## 📈 Analiz Sonuçları
- **Seattle Şehri:** Elektrikli araç kullanım oranı en yüksek olan şehir. Tesla, burada en çok tercih edilen marka.
- **Tesla'nın Pazar Payı:** Tesla, diğer markalara kıyasla elektrikli araç pazarında 8 kat daha fazla tercih edilmiştir.
- **Elektrikli Araçlar vs Hibrit Araçlar:** Elektrikli araçlar, hibrit araçlara kıyasla 4 kat daha fazla tercih edilmektedir.
- **Şehir Bazlı Dağılımlar:** Seattle, Bellevue'den 4 kat daha fazla elektrikli araç kullanımı ile öne çıkmaktadır.

## 📄 Lisans
Bu proje, **MIT Lisansı** altında lisanslanmıştır.

## Kaggle Notebook Linki
- **Notebook:** [LINK](https://www.kaggle.com/code/metinyurdev/electricvehicleanalysisproject)
