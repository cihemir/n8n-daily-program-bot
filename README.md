# Akademik Takvim Otomasyon Sistemi (n8n & Google API Entegrasyonu)

Bu proje, n8n iş akışı otomasyon platformu üzerinde kurgulanmış; üniversite ders programı verilerini Google Sheets üzerinden dinamik olarak çekerek kullanıcıya günlük Gmail raporu sunan  bir otomasyon çözümüdür.

## Proje Özeti
Sistem, manuel takibi ortadan kaldırarak akademik programın her sabah belirlenen saatte kullanıcıya ulaşmasını sağlar. JavaScript tabanlı filtreleme algoritması sayesinde, sadece ilgili güne ait veriler işlenir ve anlamlı bir rapor haline getirilir.

## Teknik Özellikler
* **Zamanlayıcı (Schedule Trigger):** Günlük rutin çalışma için optimize edilmiş tetikleyici mekanizması.
* **Google Sheets Entegrasyonu:** Veri tabanı olarak kullanılan e-tablodan "Gun", "Dersler" ve "Saat" sütunlarının API üzerinden okunması.
* **JavaScript Veri İşleme:** Code Node yapısı içerisinde bugünün tarihine göre verilerin parse edilmesi ve boş gün senaryolarının yönetilmesi.
* **Güvenli Yetkilendirme:** Google Cloud Console üzerinde OAuth 2.0 protokolü kullanılarak sağlanan güvenli erişim katmanı.

## Kullanılan Teknolojiler
* **Otomasyon:** n8n Workflow Automation
* **Veri Yönetimi:** Google Sheets API
* **İletişim Servisi:** Gmail API
* **Mantıksal Katman:** Node.js / JavaScript

