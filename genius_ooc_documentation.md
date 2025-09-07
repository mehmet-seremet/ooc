# Genius Open Online Center Kullanım Dökümanı

## 1. İçindekiler
1. [Giriş](#2-giriş)
2. [Sistem Gereksinimleri](#3-sistem-gereksinimleri)
3. [Kurulum](#4-kurulum)
4. [İlk Giriş](#5-ilk-giriş)
5. [Ana Menü](#6-ana-menü)
6. [Temel Özellikler](#7-temel-özellikler)
7. [Gelişmiş Özellikler](#8-gelişmiş-özellikler)
8. [Sorun Giderme](#9-sorun-giderme)
9. [SSS](#10-sss-sıkça-sorulan-sorular)
10. [İletişim](#11-iletişim)

## 2. Giriş

Genius Open Online Center (GOC), daha önce ayrı ayrı çalışan Genius uygulamalarının web teknolojisi ile birleştirilmiş kapsamlı bir yönetim platformudur. Bu sistem, kampanya yönetimi, script tasarımı, bonus tanımları ve mağaza kullanıcı yönetimi gibi işlevleri tek bir merkezi platformda toplar.

### Platform Bileşenleri
- **Kampanya Engine**: Pazarlama kampanyalarının oluşturulması ve yönetimi
- **Script Designer**: Otomatik süreçler için script tasarımı ve düzenleme
- **Bonus Tanımları**: Müşteri bonus sistemlerinin konfigürasyonu
- **Mağaza Kullanıcı Yönetimi**: Merkez.exe'nin web tabanlı karşılığı
- **Merkezi Yönetim**: Tüm sistemlerin tek noktadan kontrolü

## 3. Sistem Gereksinimleri

### Minimum Sistem Gereksinimleri
- **İşletim Sistemi**: Windows 10/11, macOS 10.14+, Linux Ubuntu 18.04+
- **Tarayıcı**: Chrome 90+, Firefox 88+, Safari 14+, Edge 90+
- **RAM**: 4 GB
- **İnternet Bağlantısı**: En az 25 Mbps (web tabanlı uygulamalar için)
- **Depolama**: 1 GB boş alan
- **Veritabanı**: SQL Server 2016+ (sunucu tarafı)

### Önerilen Sistem Gereksinimleri
- **RAM**: 8 GB veya üzeri
- **İşlemci**: Intel i5 veya AMD Ryzen 5 eş değeri
- **İnternet Bağlantısı**: 100 Mbps veya üzeri
- **Tarayıcı**: En güncel sürümler (otomatik güncelleme aktif)

## 4. Kurulum

### Web Tabanlı Erişim
1. Tarayıcınızı açın
2. `https://ooc.genius.com` adresine gidin
3. Kurumunuzun verdiği giriş bilgilerini kullanın
4. Sistem yöneticinizden gerekli yetkileri alın

### Sunucu Kurulumu (Yöneticiler İçin)
1. **Veritabanı Kurulumu**: SQL Server 2016+ gereklidir
2. **Web Sunucusu**: IIS 10.0+ veya Apache 2.4+
3. **Framework**: .NET 6.0+ yükleyin
4. **Konfigürasyon**: Kampanya engine ve script designer modüllerini aktifleştirin

## 5. İlk Giriş

### Giriş Adımları
1. Ana sayfada **"Giriş Yap"** butonuna tıklayın
2. **Kullanıcı Adı** ve **Şifre** bilgilerinizi girin
3. **"Beni Hatırla"** seçeneğini işaretleyebilirsiniz
4. **"Giriş"** butonuna tıklayın

### İlk Kez Giriş
Eğer ilk kez giriş yapıyorsanız:
1. Kurumunuzun verdiği geçici şifreyi kullanın
2. Sistem sizden yeni bir şifre oluşturmanızı isteyecek
3. Güvenli bir şifre oluşturun (en az 8 karakter, büyük/küçük harf, sayı ve özel karakter)
4. Profil bilgilerinizi güncelleyin

## 6. Ana Menü

### Dashboard (Ana Sayfa)
- **Güncel Duyurular**: Kurumsal duyurular ve haberler
- **Yaklaşan Etkinlikler**: Sınav, ödev teslim tarihleri
- **Hızlı Erişim**: Sık kullanılan özelliklere kısayollar
- **İstatistikler**: Kişisel performans özeti

### Navigasyon Menüsü
- **🏠 Ana Sayfa**: Dashboard ve genel bakış
- **📚 Derslerim**: Kayıtlı olunan dersler
- **📝 Ödevler**: Ödev listesi ve teslim durumu
- **📊 Sınavlar**: Sınav programı ve sonuçları
- **💬 Mesajlar**: Öğretmen ve öğrenci iletişimi
- **👤 Profil**: Kişisel bilgiler ve ayarlar

## 7. Temel Özellikler

### Ders Katılımı
1. **"Derslerim"** sekmesine gidin
2. Katılmak istediğiniz dersi seçin
3. **"Derse Katıl"** butonuna tıklayın
4. Kamera ve mikrofon izinlerini verin

### Ödev Teslimi
1. **"Ödevler"** bölümüne gidin
2. Teslim edilecek ödevi seçin
3. **"Dosya Yükle"** butonuna tıklayın
4. Dosyanızı seçin ve **"Gönder"** butonuna tıklayın

### Sınav Alma
1. **"Sınavlar"** bölümüne gidin
2. Aktif sınavı seçin
3. **"Sınava Başla"** butonuna tıklayın
4. Soruları cevaplayın ve **"Teslim Et"** butonuna tıklayın

### Mesajlaşma
1. **"Mesajlar"** bölümüne gidin
2. **"Yeni Mesaj"** butonuna tıklayın
3. Alıcıyı seçin
4. Mesajınızı yazın ve **"Gönder"** butonuna tıklayın

## 8. Gelişmiş Özellikler

### Grup Çalışmaları
- Öğretmen tarafından oluşturulan gruplara katılım
- Grup içi dosya paylaşımı
- Kolektif proje geliştirme araçları

### Beyaz Tahta Kullanımı
- Gerçek zamanlı çizim ve yazma
- Ekran paylaşımı
- Matematiksel formül editörü

### Kayıt ve Tekrar İzleme
- Ders kayıtlarına erişim
- İndirme ve çevrimdışı izleme
- Hız kontrolü ve not alma

### Takvim Entegrasyonu
- Google Calendar, Outlook entegrasyonu
- Otomatik hatırlatmalar
- Kişisel program yönetimi

## 9. Sorun Giderme

### Yaygın Sorunlar ve Çözümleri

#### Giriş Yapamıyorum
**Çözüm:**
1. Kullanıcı adı ve şifrenizi kontrol edin
2. Caps Lock tuşunun kapalı olduğundan emin olun
3. Tarayıcı çerezlerini temizleyin
4. Farklı bir tarayıcı deneyin

#### Video/Ses Sorunu
**Çözüm:**
1. Mikrofon ve kamera izinlerini kontrol edin
2. Tarayıcı ayarlarından medya izinlerini güncelleyin
3. Başka uygulamaları kapatın
4. İnternet bağlantınızı kontrol edin

#### Dosya Yüklenmiyor
**Çözüm:**
1. Dosya boyutunu kontrol edin (max 100MB)
2. Desteklenen formatları kontrol edin
3. İnternet bağlantınızı kontrol edin
4. Sayfayı yenileyin

#### Sayfa Yüklenmiyor
**Çözüm:**
1. İnternet bağlantınızı kontrol edin
2. Tarayıcı önbelleğini temizleyin
3. Güvenlik duvarı ayarlarını kontrol edin
4. VPN kullanıyorsanız kapatmayı deneyin

## 10. SSS (Sıkça Sorulan Sorular)

### Genel Sorular

**S: Sisteme kaç kişi aynı anda bağlanabilir?**
C: Sistem eş zamanlı olarak sınırsız kullanıcıyı destekler. Ancak sınıf başına maksimum 100 öğrenci önerilir.

**S: Mobil cihazlardan erişebilir miyim?**
C: Evet, hem mobil uygulama hem de mobil tarayıcı desteği mevcuttur.

**S: Offline çalışabilir miyim?**
C: Bazı içerikler offline görüntülenebilir, ancak etkileşimli özellikler internet bağlantısı gerektirir.

**S: Verilerim güvende mi?**
C: Evet, tüm veriler SSL şifreleme ile korunur ve GDPR uyumludur.

### Teknik Sorular

**S: Hangi dosya formatları desteklenir?**
C: PDF, DOC/DOCX, XLS/XLSX, PPT/PPTX, JPG, PNG, MP4, MP3 formatları desteklenir.

**S: Sınav süresi dolunca ne olur?**
C: Sistem otomatik olarak sınavı teslim eder ve mevcut cevapları kaydeder.

**S: Kayıtlar ne kadar süre saklanır?**
C: Ders kayıtları 1 yıl boyunca saklanır, öğrenci verileri mezuniyet sonrası 3 yıl saklanır.

## 11. İletişim

### Teknik Destek
- **E-posta**: support@genius.edu
- **Telefon**: +90 212 XXX XX XX
- **Canlı Destek**: Sistem içi chat özelliği
- **Çalışma Saatleri**: Pazartesi-Cuma 09:00-18:00

### Eğitim ve Danışmanlık
- **E-posta**: training@genius.edu
- **Telefon**: +90 212 XXX XX XX
- **Online Eğitim**: Her Çarşamba 14:00-15:00

### Satış ve Genel Bilgi
- **E-posta**: info@genius.edu
- **Web**: www.genius.edu
- **Sosyal Medya**: @GeniusEdu

---

**Son Güncelleme**: 07 Eylül 2025
**Versiyon**: 2.1.0
**Doküman Kodu**: GOC-DOC-2025-001

*Bu doküman Genius Education tarafından hazırlanmıştır. Tüm hakları saklıdır.*