Finans Takip V14.1

Bu sürümde:
- Güvenli günlük ve manuel JSON yedekleme korunur.
- Ana ekranda günlük ve aylık finans özeti bulunur.
- Kurye bölümünde günlük/aylık analiz ve otomatik 12 aylık fatura dönemleri bulunur.
- Fatura: paket dönemi önceki ayın 26'sı → fatura ayının son günü; KM dönemi fatura ayının 1'i → son günü; ödeme sonraki ayın 5'i.
- Gider eklerken Nakit veya kredi kartı seçilebilir. Nakit borca eklenmez; kredi kartı harcaması seçilen kredi kartı borcuna otomatik eklenir.
- Giderlerde dönem/kategori filtreleri bulunur.
- Borçlarda ödeme geçmişi ve başlangıç/ödenen/kalan tutarları korunur.
- Eski JSON yedekleri desteklenir; yeni alanlar yoksa güvenli varsayılanlar oluşturulur.


V14.1 düzeltmesi: Gider tarih filtresi daha kompakt hale getirildi ve tarih seçimi sonrasında kategori dağılımı/pastası ile gider listesinin kaybolmasına neden olan eksik HTML kapanışı düzeltildi.


V14: Kurye tarifeleri Ayarlar bölümünden değiştirilebilir. KM ücreti 7,5 TL/km olarak güncellenmiştir. 7,5 ve 7.5 ondalık girişleri doğru yorumlanır. İlk ve birleşen sipariş tarifeleri de Ayarlar üzerinden değiştirilebilir; eski kayıtların tutarları korunur.

V15: Borçlar bölümüne borç düzenleme eklendi. Borç adı, güncel kalan tutar ve kredi kartı limiti değiştirilebilir. Düzenleme gelir/gider veya borç ödemesi olarak kaydedilmez; aylık net kâr/zararı etkilemez. Son düzenleme "Düzenlemeyi Geri Al" ile eski değerlerine döndürülebilir. Borç ödeme hareketlerinde mevcut "Geri Al" işlevi korunmuştur.

V16: Ödenen borçlar bölümüne borcu düzenleme/yeniden açma, düzenleme geri alma ve borç ödeme işlemini geri alma kontrolleri eklendi.


V17: Borç ödeme geçmişine, borç bakiyesini değiştirmeden yalnızca hatalı ödeme kaydını raporlardan ve ilgili işlem geçmişinden kaldırma seçeneği eklendi. Mevcut ödeme geri alma seçeneği de korunmuştur.
