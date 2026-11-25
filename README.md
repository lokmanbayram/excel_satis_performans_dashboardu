# Satış Performansı Excel Dashboard

2025 yılına ait 1.000 siparişlik satış verisi üzerinden hazırladığım etkileşimli Excel dashboard çalışması. Veriler tek bir ekranda özetlenecek şekilde düzenlendi ve tüm grafikler dinamik formüllerle birbirine bağlandı.

<img src="dashboard_gorunumu.png" alt="Dashboard Ekran Goruntusu" width="100%">

## Neler Var

* **Sol Filtre Menüsü:** Yıl, ay, ürün kategorisi, şehir ve ödeme yöntemi seçimleri açılır listeler üzerinden yapılabiliyor. Seçim değiştiğinde sayfadaki tüm kartlar ve grafikler otomatik güncelleniyor.
* **Üst Özet Kartları:** Toplam ciro, net ciro, toplam sipariş adedi, ortalama sepet tutarı ve aylık eğilim çizgileri yer alıyor.
* **Aylık Performans ve Kategori Dağılımı:** Aylık ciro ile sipariş adedini birlikte gösteren karma grafik ve beş ürün kategorisinin ciro paylarını gösteren halka grafik bulunuyor.
* **Operasyon ve Ürün Özeti:** İadesiz sipariş başarı oranı göstergesi, teslimat hızına göre beş aşamalı sipariş hunisi ve en çok ciro getiren ilk üç ürün tablosu yer alıyor.

## Çalışma Kitabı Yapısı

* **Dashboard:** Tüm grafiklerin ve filtrelerin yer aldığı ana sunum ekranı.
* **Analiz_Modeli:** Filtrelere bağlı çalışan tüm hesaplama tablolarının bulunduğu sayfa.
* **Ham_Veri:** 1.000 satırlık kaynak satış kayıtlarının yer aldığı tablo sayfası.

## Kullanım

`Satis_Performans_Dashboard.xlsx` dosyasını bilgisayarınıza indirip Microsoft Excel ile açmanız yeterli. Sol taraftaki beyaz filtre kutularına tıklayarak farklı kırılımları inceleyebilirsiniz.
