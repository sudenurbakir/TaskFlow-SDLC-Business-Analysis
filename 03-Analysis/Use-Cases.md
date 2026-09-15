# Use Cases
## TaskFlow

Aşağıda sistemin temel kullanım senaryolarını Use Case formatında sıralanmıştır;

### UC-01: Sisteme Giriş Yapma
- **Aktör:** Kullanıcı
- **Ön Koşul:** Kullanıcının sistemde tanımlı bir hesabı olmalı
- **Ana Akış:**
  1. Kullanıcı giriş sayfasına gider
  2. E-posta ve şifresini girer
  3. Sistem bilgileri kontrol eder
  4. Ana sayfaya yönlendirir
- **Alternatif Akış:** Bilgiler hatalıysa kullanıcıya uyarı gösterilir

### UC-02: Yeni Görev Oluşturma
- **Aktör:** Kullanıcı veya Ekip Lideri
- **Ön Koşul:** Kullanıcı sisteme giriş yapmış olmalı
- **Ana Akış:**
  1. “Yeni Görev” butonuna tıklar
  2. Görev bilgilerini doldurur
  3. Kaydet butonuna basar
  4. Görev listede görünür
- **İş Kuralı:** Görev başlığı boş bırakılamaz

### UC-03: Görev Durumu Güncelleme
- **Aktör:** Görev sahibi veya Ekip Lideri
- **Ana Akış:**
  1. İlgili görevin detayına girer
  2. Durumu değiştirir
  3. Değişikliği kaydeder
  4. Liste güncellenir
