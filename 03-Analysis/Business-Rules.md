# Business Rules
## TaskFlow

Sistemin işleyişi içiçn temel iş kuralları:

### BR-01
Her görevin mutlaka bir atanan kişisi olmalıdır.

### BR-02
Görev başlığı en az 3 karakter uzunluğunda olmalıdır.

### BR-03
Tamamlanan görevler silinemez, sadece arşivlenebilir.

### BR-04
Bir kullanıcı yalnızca kendisine atanan görevlerin durumunu değiştirebilir. (Ekip Lideri bu kuralın dışındadır)

### BR-05
Aynı e-posta adresi ile birden fazla kullanıcı oluşturulamaz.

### BR-06
Görev bitiş tarihi geçmiş bir tarih olarak seçilemez.

### Görev Atama Yetkileri

Görev atama konusunda net kurallar;

- **Ekip Lideri**, sistemdeki herhangi bir kullanıcıya görev atayabilir.
- **Normal Kullanıcı**, sadece kendisine görev oluşturabilir veya kendisine atanan görevleri yönetebilir.
- Bir kullanıcı, başka bir kullanıcıya doğrudan görev atayamaz.
- Görev oluştururken “Atanan Kişi” alanı zorunludur. Atama yapılmadan görev kaydedilemez.

### Görev Durumu Geçiş Kuralları

Görevlerin durum geçişleri kurgusu;

1. **Yapılacak → Devam Ediyor**
   - Görevi üzerine alan kişi veya Ekip Lideri yapabilir.

2. **Devam Ediyor → Tamamlandı**
   - Görevi üzerine alan kişi veya Ekip Lideri yapabilir.

3. **Herhangi bir durum → İptal Edildi**
   - Sadece Ekip Lideri yapabilir.

4. **Tamamlandı** durumundaki bir görev tekrar geri alınamaz (Yapılacak veya Devam Ediyor yapılamaz).
   - Gerekirse yeni bir görev açılır.

5. **İptal Edildi** durumundaki görev tekrar aktif hale getirilemez.
