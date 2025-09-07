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

### İlk Kez Giriş ve Yetkilendirme
Eğer ilk kez giriş yapıyorsanız:
1. Sistem yöneticinizden alınan geçici şifreyi kullanın
2. Sistem sizden yeni bir şifre oluşturmanızı isteyecek
3. Güvenli bir şifre oluşturun (en az 8 karakter, büyük/küçük harf, sayı ve özel karakter)
4. Profil bilgilerinizi güncelleyin
5. **Modül Yetkileri**: Kampanya, Script Designer, Bonus Yönetimi gibi modüllere erişim için yöneticinizden yetki talep edin

## 6. Ana Menü

### Dashboard (Ana Sayfa)
- **Güncel Duyurular**: Sistem duyuruları ve haberler
- **Aktif Kampanyalar**: Çalışan kampanya özetleri
- **Hızlı Erişim**: Sık kullanılan modüllere kısayollar
- **Sistem İstatistikleri**: Performans özeti ve kullanım raporları
- **Son Aktiviteler**: Kullanıcı işlemlerinin geçmişi

### Navigasyon Menüsü
- **🏠 Ana Sayfa**: Dashboard ve genel bakış
- **🎯 Kampanya Yönetimi**: Kampanya oluşturma ve düzenleme
- **📋 Script Designer**: Otomatik süreç tasarımı
- **🎁 Bonus Tanımları**: Müşteri bonus sistemi
- **🏦 Mağaza Yönetimi**: Kullanıcı ve mağaza tanımları
- **📊 Raporlama**: Detaylı analiz ve raporlar
- **⚙️ Sistem Ayarları**: Konfigürasyon ve yönetim
- **👤 Profil**: Kişisel bilgiler ve ayarlar

## 7. Temel Özellikler

### Kampanya Yönetimi
1. **"Kampanya Yönetimi"** modülüne gidin
2. **"Yeni Kampanya"** butonuna tıklayın
3. Kampanya detaylarını (ad, tarih, hedef kitle) girin
4. Kampanya kurallarını ve koşullarını tanımlayın
5. **"Kaydet ve Aktifleştir"** butonuna tıklayın

### Script Designer Kullanımı
1. **"Script Designer"** bölümüne gidin
2. **"Yeni Script"** oluşturun
3. Otomatik süreçleri tanımlayın (tetikleyiciler, aksiyonlar)
4. Script mantığını test edin
5. **"Deploy"** ederek canlıya alın

### Bonus Tanımlama
1. **"Bonus Tanımları"** bölümüne gidin
2. Bonus türünü seçin (puan, indirim, hediye)
3. Bonus koşullarını belirleyin
4. Geçerlilik tarihlerini ayarlayın
5. **"Bonusı Aktifleştir"** butonuna tıklayın

### Mağaza Kullanıcı Yönetimi
1. **"Mağaza Yönetimi"** bölümüne gidin
2. **"Yeni Kullanıcı"** ekleyin
3. Kullanıcı yetkileri ve rollerini tanımlayın
4. Mağaza bağlantısını kurun
5. **"Kullanıcıyı Aktifleştir"** butonuna tıklayın

## 8. Gelişmiş Özellikler

### Gelişmiş Kampanya Ayarları
- Çoklu kanal kampanya yönetimi (SMS, Email, Push)
- A/B testing ile kampanya optimizasyonu
- Dinamik hedef kitle segmentasyonu
- Real-time kampanya performans takibi

### Script Automation
- Karmaşık iş akışı otomasyonu
- API entegrasyonları için script şablonları
- Hata yönetimi ve log takibi
- Şartlı mantık ve döngü yapıları

### Gelişmiş Bonus Sistemleri
- Katmanlı bonus yapıları
- Biriken puan sistemleri
- Özel gün ve etkinlik bonusları
- Grup bazlı bonus tanımları

### Entegrasyon Yönetimi
- Harici sistemlerle API bağlantıları
- Veritabanı senkronizasyonu
- Third-party servis entegrasyonları
- Merkez.exe migration araçları

## 9. Sorun Giderme

### Yaygın Sorunlar ve Çözümleri

#### Giriş Yapamıyorum
**Çözüm:**
1. Kullanıcı adı ve şifrenizi kontrol edin
2. Caps Lock tuşunun kapalı olduğundan emin olun
3. Tarayıcı çerezlerini temizleyin
4. Farklı bir tarayıcı deneyin
5. Sistem yöneticinizden yetki kontrolü yaptırın

#### Kampanya Çalışmıyor
**Çözüm:**
1. Kampanya tarih ayarlarını kontrol edin
2. Hedef kitle kriterlerini gözden geçirin
3. Kampanya log dosyalarını inceleyin
4. Script bağlantılarını test edin

#### Script Hatası
**Çözüm:**
1. Script syntax kontrolünü yapın
2. Test ortamında çalıştırın
3. Hata loglarını inceleyin
4. API bağlantılarını doğrulayın

#### Bonus Sistemi Sorunları
**Çözüm:**
1. Bonus koşullarını yeniden kontrol edin
2. Müşteri segmentasyon ayarlarını gözden geçirin
3. Veritabanı senkronizasyonunu kontrol edin
4. Bonus hesaplama algoritmalarını test edin

## 10. SSS (Sıkça Sorulan Sorular)

### Genel Sorular

**S: Sistem kaç kullanıcıyı aynı anda destekler?**
C: Sistem eş zamanlı olarak 1000+ kullanıcıyı destekler. Performans sunucu kapasitesine bağlıdır.

**S: Eski Genius uygulamalarındaki verilerim nerede?**
C: Tüm eski veriler OOC platformuna migrate edilmiştir. Veri bütünlüğü korunmuştur.

**S: Merkez.exe yerine nasıl geçiş yapılır?**
C: Migration araçları ile otomatik geçiş sağlanır. Detaylar için sistem yöneticinize başvurun.

**S: Hangi modüllere erişimim var?**
C: Erişim yetkileri rol tabanlıdır. Yöneticinizden gerekli yetkileri talep edebilirsiniz.

**S: Verilerim güvende mi?**
C: Evet, tüm veriler SSL şifreleme ile korunur ve GDPR uyumludur.

### Teknik Sorular

**S: Hangi tarayıcılar desteklenir?**
C: Chrome 90+, Firefox 88+, Safari 14+, Edge 90+ desteklenir. En güncel sürümler önerilir.

**S: API entegrasyonu nasıl yapılır?**
C: REST API dokümantasyonu sistem içerisinde mevcuttur. Geliştirici rehberine başvurun.

**S: Kampanyalarım neden çalışmıyor?**
C: Kampanya koşulları, tarih aralıkları ve hedef kitle ayarlarını kontrol edin.

**S: Script hatası alıyorum, ne yapmalıyım?**
C: Script Designer'da syntax kontrolünü yapın, test ortamında deneyip log dosyalarını inceleyin.

**S: Bonus hesaplamaları yanlış çıkıyor?**
C: Bonus kurallarını, koşulları ve algoritma ayarlarını yeniden gözden geçirin.

## 11. İletişim

### Teknik Destek
- **E-posta**: support@genius.com
- **Telefon**: +90 212 XXX XX XX
- **Canlı Destek**: Sistem içi chat özelliği
- **Çalışma Saatleri**: Pazartesi-Cuma 09:00-18:00
- **Acil Durum**: 7/24 sistem izleme

### Eğitim ve Danışmanlık
- **E-posta**: training@genius.com
- **Telefon**: +90 212 XXX XX XX
- **Online Eğitim**: Her Çarşamba 14:00-15:00
- **Kampanya Danışmanlığı**: Uzman ekip desteği

### Satış ve Genel Bilgi
- **E-posta**: info@genius.com
- **Web**: www.genius.com/ooc
- **Sosyal Medya**: @GeniusOOC
- **Geliştirici Portalü**: dev.genius.com

---

**Son Güncelleme**: 07 Eylül 2025
**Versiyon**: 3.0.0 (Unified Platform)
**Döküman Kodu**: OOC-DOC-2025-001

*Bu döküman Genius Technology tarafından hazırlanmıştır. Tüm hakları saklıdır.*