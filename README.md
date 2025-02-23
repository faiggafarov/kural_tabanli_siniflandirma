# 🎯 Kural Tabanlı Sınıflandırma ile Müşteri Segmentasyonu  

Bu proje, bir oyun şirketinin müşteri verilerini analiz ederek **demografik özelliklere dayalı segmentler oluşturmasını** ve **potansiyel müşterilerin şirkete sağlayacağı geliri tahmin etmesini** amaçlamaktadır.  

## 🚀 Projenin Amacı  
- Kullanıcıların yaş, cinsiyet, ülke ve cihaz bilgilerini kullanarak **müşteri segmentleri** oluşturmak  
- Yeni müşterilerin hangi segmentte yer aldığını belirlemek  
- Yeni müşterilerin **ortalama ne kadar gelir getirebileceğini tahmin etmek**  

## 📂 Veri Seti  
**persona.csv** adlı veri seti, her müşterinin yaptığı satın alımlar hakkında bilgiler içermektedir:  
- **PRICE** → Müşterinin harcama tutarı  
- **SOURCE** → Müşterinin bağlandığı cihaz türü (Android/iOS)  
- **SEX** → Müşterinin cinsiyeti  
- **COUNTRY** → Müşterinin ülkesi  
- **AGE** → Müşterinin yaşı  

## 🔧 Kullanılan Teknolojiler  
- **Python**  
- **Pandas** (veri işleme)  
- **Numpy** (matematiksel işlemler)  

## 📌 Proje Adımları  
### 1️⃣ Veri Setinin Okunması  
```python
import pandas as pd
df = pd.read_csv('persona.csv')
df.head()
