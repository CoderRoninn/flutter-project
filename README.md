# 📱 Mini Katalog Uygulaması

Bu proje, tamamen saf Flutter (`material.dart`) widget'ları kullanılarak geliştirilmiş, modern, hızlı ve şık bir mobil e-ticaret/katalog uygulamasıdır. Kullanıcı dostu arayüz tasarımı, akıcı geçiş animasyonları, dinamik yerel veri yönetimi ve gerçek zamanlı interaktif sepet sistemi ile uçtan uca eksiksiz bir mobil deneyim sunar.

---

## ✨ Öne Çıkan Özellikler

Uygulama, sıfır dış bağımlılık (harici paket kullanılmadan) prensibiyle, maksimum performans ve kararlılık odaklı olarak geliştirilmiştir:

* **Saf Flutter Mimarisi (`material.dart`)**: Herhangi bir üçüncü parti arayüz veya durum yönetimi paketi kullanılmadan, tamamen Flutter'ın kendi güçlü çekirdek widget'ları ile temiz bir kod mimarisi kurulmuştur.
* **Dinamik Ürün Kataloğu & JSON Modelleme**: Ürün verileri yerel bir JSON dosyasından çekilerek Dart nesnelerine dinamik olarak dönüştürülür ve listelenir.
* **Izgara Görünümü (GridView.builder)**: Katalog ekranında ürünler, responsive ve şık 2'li dikey kart tasarımları halinde sergilenir.
* **Hero Geçiş Animasyonları**: Katalogdan ürün detayına geçişlerde resimler arasında akıcı ve modern görsel geçiş animasyonları yer alır.
* **Özel Detay Sayfası & Alt Panel**: Ürün detay ekranında yukarı doğru kaydırılabilen, yuvarlatılmış köşelere sahip modern bir açıklama paneli kullanılmıştır.
* **Gerçek Zamanlı Sepet Yönetimi**: 
  * Ürünler ana sayfadan veya detay sayfasından sepete eklenebilir.
  * Sepet sayfasından (`CartPage`) ürünler anlık olarak silinebilir. Silme işlemi sonrasında toplam sepet tutarı ve ürün listesi anında güncellenir.
  * Checkout simülasyonu ile sipariş verme akışı tamamlanabilir.
* **Çift Tema Desteği**: Uygulama hem açık (Light Mode) hem de koyu (Dark Mode) temayı tam uyumlu olarak destekler.

---

## 📂 Proje Klasör Yapısı

Projede temiz kod prensiplerine uygun olarak modüler bir klasörleme mimarisi tercih edilmiştir:

```text
lib/
├── models/         # Veri modelleri ve sepet durum yönetim sınıfları (catalog.dart, cart.dart)
├── pages/          # Uygulama ekranları (login_page.dart, home_page.dart, home_detail_page.dart, cart_page.dart)
├── themes/         # Açık ve koyu tema tanımlamaları (themes.dart, app_color.dart)
├── utils/          # Uygulama içi rotalar ve sabitler (routes.dart)
└── widgets/        # Yeniden kullanılabilir özel arayüz bileşenleri (home_widgets/ vb.)
assets/
├── files/          # Yerel ürün veritabanı (catalog.json)
└── images/         # Logo ve yerel uygulama görselleri (AppLogo.png)
```

---

## ⚙️ Sistem Gereksinimleri

* **Flutter SDK:** `^3.11.5` veya üzeri stabil sürümler
* **Dart SDK:** `^3.0.0` veya üzeri
* **Çalışma Platformu:** Android / iOS emulator veya fiziksel mobil cihazlar

---

## 🛠️ Uygulamayı Çalıştırma Adımları

Projeyi kendi yerel ortamınızda ayağa kaldırmak için aşağıdaki adımları sırasıyla uygulayabilirsiniz:

1. **Depoyu Klonlayın:**
   ```bash
   git clone <repository-url>
   ```

2. **Proje Dizinine Gidin:**
   ```bash
   cd trendy_stor
   ```

3. **Gerekli Paketleri Yükleyin:**
   ```bash
   flutter pub get
   ```

4. **Projeyi Başlatın:**
   ```bash
   flutter run
   ```

---

## 📸 Uygulama Ekran Görüntüleri (Screenshots)

| Giriş Ekranı (Login) | Katalog Ekranı (GridView) | Detay Ekranı | Dinamik Sepet Ekranı (Cart) |
| :---: | :---: | :---: | :---: |
| ![Login Screen](assets/images/AppLogo.png) | *(Ekran Görüntüsü)* | *(Ekran Görüntüsü)* | *(Ekran Görüntüsü)* |
