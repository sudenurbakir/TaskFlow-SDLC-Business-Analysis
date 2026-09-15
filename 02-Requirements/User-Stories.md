# User Stories
## TaskFlow

Aşağıda sistemi kullanacak kişilerin bakış açısından yazdığım User Story’leri bulunmaktadır. 

### Epic 1: Kullanıcı Girişi

**US-01**  
Bir kullanıcı olarak, sisteme giriş yapabilmek istiyorum ki bana atanan görevleri görebileyim.  
**Kabul Kriterleri:**
- E-posta ve şifre ile giriş yapılabilmeli
- Hatalı girişte anlamlı bir uyarı çıkmalı
- Başarılı giriş sonrası ana sayfaya yönlendirilmeli

---

### Epic 2: Görev Yönetimi

**US-02**  
Bir kullanıcı olarak, yeni bir görev oluşturmak istiyorum.  
**Kabul Kriterleri:**
- Görev başlığı zorunlu olmalı
- Açıklama alanı opsiyonel olmalı
- Bitiş tarihi seçilebilmeli
- Görev bir kişiye atanabilmeli

**US-03**  
Bir kullanıcı olarak, görevimin durumunu güncellemek istiyorum.  
**Kabul Kriterleri:**
- Durum seçenekleri: Yapılacak, Devam Ediyor, Tamamlandı
- Değişiklik anında listede yansımalı

**US-04**  
Bir kullanıcı olarak, sadece bana atanan görevleri görmek istiyorum.  
**Kabul Kriterleri:**
- Sadece bana ait görevler listelenmeli
- Duruma göre filtreleme yapılabilmeli

**US-05**  
Bir ekip lideri olarak, ekibimdeki tüm görevleri görebilmek istiyorum.  
**Kabul Kriterleri:**
- Tüm görevler görüntülenebilmeli
- Kişi ve duruma göre filtrelenebilmeli
