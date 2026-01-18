# 📊 Müşteri Kaybı Analizi

Bu proje, müşteri kaybı (churn) davranışlarını analiz etmek, churn oranını etkileyen temel faktörleri belirlemek ve karar destek sağlamak amacıyla hazırlanmış bir **Power BI dashboard** çalışmasıdır.

Dashboard; müşteri sözleşme tipi, ödeme yöntemi, internet hizmeti, müşteri süresi (tenure) ve aylık ücretler üzerinden churn analizini görselleştirmektedir.

---

## 🎯 Proje Amacı

Bu çalışmanın temel amacı:

- Müşteri kaybı oranını ölçmek
- Churn’e etki eden müşteri özelliklerini belirlemek
- Riskli müşteri profillerini tespit etmek
- Müşteri elde tutma (retention) stratejilerine veri temelli içgörüler sunmaktır

---

## 📊 Dashboard İçeriği

Dashboard’ta aşağıdaki temel **KPI’lar** yer almaktadır:

- **Toplam Müşteri Sayısı**
- **Kaybedilen Müşteri Sayısı**
- **Müşteri Kayıp Oranı (Churn %)**
- **Ortalama Müşteri Süresi (Ay)**

Dashboard’un PDF önizleme çıktısı:
[Dashboard PDF Önizleme](dashboard_preview.pdf)
---

## 🔍 Görselleştirilen Analizler

Dashboard’ta yer alan grafikler aşağıdaki analizleri içermektedir:

### 📄 Sözleşme Tipi Analizi
- Sözleşme tipine göre **müşteri kayıp oranı**
- Month-to-month, 1 yıllık ve 2 yıllık sözleşmelerin churn karşılaştırması

### 💳 Ödeme Yöntemi Analizi
- Ödeme yöntemine göre churn oranı
- Elektronik çek, otomatik kredi kartı ve banka transferi karşılaştırmaları

### 🌐 İnternet Hizmeti Analizi
- İnternet hizmeti türüne göre müşteri kaybı dağılımı
- Fiber, DSL ve internet hizmeti olmayan müşterilerin karşılaştırılması

### 👥 Demografik Analiz
- Cinsiyete göre müşteri kaybı dağılımı

### 📈 Fiyat ve Süre İlişkisi (Kritik Analiz)
- **Müşteri süresi (tenure) ile aylık ücret arasındaki ilişki**
- Churn durumuna göre fiyat ve süre bazlı riskli müşteri profillerinin belirlenmesi

Bu analiz, özellikle **kısa süreli ve yüksek ücret ödeyen müşterilerin churn riskinin daha yüksek olduğunu** göstermektedir.

---

## 📌 Analiz Özeti

- Month-to-month sözleşmeye sahip müşterilerde churn oranı belirgin şekilde daha yüksektir.
- Elektronik çek ile ödeme yapan müşteriler daha yüksek churn eğilimi göstermektedir.
- Fiber internet kullanan müşteriler churn eden müşteri grubunda önemli bir paya sahiptir.
- Churn eden müşteriler genellikle **daha kısa müşteri süresine** ve **daha yüksek aylık ücrete** sahiptir.
- Müşteri süresi arttıkça churn olasılığı genel olarak azalmaktadır.

Bu bulgular, **müşteri elde tutma stratejileri**, **fiyatlandırma politikaları** ve **sözleşme yapılandırmaları** açısından önemli içgörüler sunmaktadır.

---

## 🛠️ Kullanılan Araçlar ve Teknikler

- **Power BI**
- **DAX ölçüleri**
  - Toplam Müşteri
  - Churn Eden Müşteri
  - Churn Oranı (%)
  - Ortalama Müşteri Süresi
- Veri modelleme
- Etkileşimli slicer ve filtreler
- Dağılım grafiği (Scatter Plot) ile ilişki analizi
- CSV tabanlı müşteri verisi

---

## 🔒 Veri Hakkında

Bu projede kullanılan veriler:

- Eğitim ve portföy amaçlıdır
- Anonimleştirilmiş müşteri verilerinden oluşmaktadır
- Gerçek kişi veya kurum bilgisi içermemektedir