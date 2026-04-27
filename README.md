# SkyLink - İHA Yer İstasyonu Kontrol Sistemi

## 📝 Proje Özeti
SkyLink, İHA operasyonlarını daha verimli, güvenilir ve kullanıcı dostu bir şekilde yönetmek amacıyla geliştirilmiş kapsamlı bir yer kontrol istasyonu (GCS) çözümüdür. Proje, İHA'lar ile kesintisiz veri iletişimi sağlayarak operatörlerin gerçek zamanlı izleme, anlık görev planlama ve veri analizi yapmasına olanak tanır.

## ✨ Özellikler
* **Gerçek Zamanlı Veri İzleme:** Telemetri verilerinin (irtifa, hız, batarya, konum) anlık takibi.
* **Dinamik Görev Yönetimi:** Uçuş rotasının operasyon sırasında anlık olarak güncellenmesi.
* **Kullanıcı Dostu Arayüz:** Operatör kontrolünü kolaylaştıran sezgisel GUI tasarımı.
* **Yedekli Haberleşme:** Veri kaybını önlemek için tasarlanmış anten ve modem sistemleri.

## 🛠 Kullanılan Teknolojiler
* **Yazılım:** Python, PyQt5 (Arayüz), MAVLink (Haberleşme), Socket Programlama.
* **Donanım:** 
    * TP-Link EAP225 Access Point ve Mantıstek Modem.
    * Pixhawk uçuş kontrolcüsü entegrasyonu.
    * Laptop tabanlı kontrol ünitesi.

## 🏗 Proje Yapısı ve Mimarisi
* **Haberleşme Katmanı:** İletişim protokollerini (MAVLink, UDP) yöneten ve veri paketlemesini yapan yapı.
* **İşleme Birimi:** Gelen telemetri ve görsel verileri ayrıştırıp kullanıcıya sunan motor.
* **GUI (Arayüz):** PyQt5 ile geliştirilmiş, harita ve telemetri panellerini içeren görsel katman.
