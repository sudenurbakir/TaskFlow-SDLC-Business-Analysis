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
