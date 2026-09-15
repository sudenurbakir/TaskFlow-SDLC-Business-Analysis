# UAT Test Cases
## TaskFlow

Kullanıcı Kabul Testi için hazırlanan temel senaryolar:

### Test Case 1: Başarılı Giriş
- **Ön Koşul:** Geçerli bir kullanıcı hesabı mevcut
- **Adımlar:**
  1. Giriş sayfasına git
  2. Doğru e-posta ve şifreyi gir
  3. Giriş Yap butonuna tıkla
- **Beklenen Sonuç:** Ana sayfa açılır

### Test Case 2: Hatalı Giriş
- **Adımlar:** Yanlış şifre gir
- **Beklenen Sonuç:** “E-posta veya şifre hatalı” uyarısı çıkar

### Test Case 3: Yeni Görev Oluşturma
- **Adımlar:**
  1. Yeni Görev butonuna tıkla
  2. Başlık gir
  3. Bir kullanıcıya ata
  4. Kaydet
- **Beklenen Sonuç:** Görev listede görünür

### Test Case 4: Görev Durumu Değiştirme
- **Adımlar:** Bir görevin durumunu “Tamamlandı” olarak güncelle
- **Beklenen Sonuç:** Durum değişir ve listede yansır

### Test Case 5: Filtreleme
- **Adımlar:** Sadece “Devam Ediyor” durumundaki görevleri filtrele
- **Beklenen Sonuç:** Sadece ilgili görevler listelenir
