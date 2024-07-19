# Google Play Duygu Analizi
google play scrapper kullanarak istenilen ugulamanın kullanıcı yorumlarını çekip kendi yazdığım duygu analizi satırlarına göre grafik ve confussion matrixi çıkaran ipynb dosyası

# Uygulama Bilgileri
Burada WhatsApp uygulamasını örnek aldık fakat tek değişmesi gereken id, language, ve num_reviews(çekilecek max yorum sayısı)
app_id = 'com.whatsapp' num_reviews = 10000 language = 'tr'

# Stop-words
Burada kullanılmadı fakat isteğe göre bir türkçe stop-words ekliyorum
