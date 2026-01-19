# Enerji Perakende Veri Analizi ve Müşteri Segmentasyonu

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Library](https://img.shields.io/badge/Library-Pandas%20|%20Seaborn%20|%20Matplotlib-orange)
![Status](https://img.shields.io/badge/Status-Completed-green)

Bu proje, Amasya bölgesindeki (Hamamözü, Gümüşhacıköy, Göynücek) enerji tüketim verilerini ve ödeme davranışlarını analiz ederek operasyonel verimliliği artırmayı ve tahsilat risklerini minimize etmeyi amaçlayan bir veri bilimi vaka çalışmasıdır.

## Proje Özeti
Enerji dağıtım şirketinin **1 milyondan fazla satırdan** oluşan 2023-2025 dönemi verileri incelenmiştir. 
Analizde 5 farklı veri tablosu kullanılmıştır:
* **Tahakkuk (Tüketim) Verileri:** Hamamözü, Gümüşhacıköy ve Göynücek ilçelerinin aylık kWh tüketimleri.
* **Tahsilat Verileri:** Müşterilerin ödeme kanalları, ödeme tarihleri.

## Proje Adımları

Proje 3 ana Jupyter Notebook'tan oluşmaktadır:

### 1. `notebook_01_veri_hazirligi.ipynb` (Veri keşfi ve Betimsel İstatistik)
* Çoklu Excel sayfalarının yüklenmesi ve birleştirilmesi.
* Eksik verilerin (Missing Values) analizi.
* Aykırı değer analizi

### 2. `notebook_02_gorsellestirme.ipynb` (EDA & Görselleştirme)
* **Mevsimsellik Analizi:** İlçelere göre aylık tüketim trendlerinin çizgi grafiklerle takibi.
* **Ödeme Disiplini:** Zamanında vs. Geç ödeme oranlarının pasta grafiklerle sunumu.
* **Dağılım Analizi:** Logaritmik ölçekli Boxplot kullanılarak tüketim dağılımlarının incelenmesi.

### 3. `notebook_03_veri_hikayesi.ipynb` (Stratejik Analiz & Müşteri Segmentasyonu)
* **Müşteri Segmentasyonu:** Müşterilerin tüketim hacmine ve fatura tutarına göre "Low", "Mid" ve "High" olarak ayrılması.
* **Tahsilat Risk Analizi:** Fatura tutarı ile ödeme gecikmesi arasındaki ilişkinin incelenmesi.
* **İş Önerileri:** Veriye dayalı aksiyon planlarının oluşturulması.

---

## Kullanılan Teknolojiler
* **Python:** Ana programlama dili.
* **Pandas:** Veri manipülasyonu ve birleştirme.
* **Matplotlib & Seaborn:** Veri görselleştirme.
* **NumPy:** Sayısal işlemler.

## Yazar
**Mert Can Demir**
*İstanbul Teknik Üniversitesi*
*Endüstri Mühendisliği*
