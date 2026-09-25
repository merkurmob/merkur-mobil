Merkür Mobil v1.2 TEST
PC v3.7.14 Üretim Kayıt Defteri, mevcut sistem_data/approvals verisini kullanır. PC paketi değişmedi.
Usta kendi kayıtlarını oluşturur, ilerleme ekler/düzeltir ve işi kapatır. Stok aktarımı yalnızca PC üzerinden yapılır.
Sistem veri satırında updated_at eşleşmeli koşullu PATCH kullanılır; çakışmada yenileme istenir.
ÖNEMLİ: Mevcut stok talepleri eski upsert mantığını kullanıyor; aynı anda yoğun işlemde ayrı değerlendirme gerekir.
Önce yedek alıp test edin.
