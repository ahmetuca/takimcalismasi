# Türkçe çalışma Takip Botu 


# 🤖 Alışkanlık Takip Botu — Proje Mimarisi

Kullanılan Teknolojiler: discord.py + sqlite3

# 📁 Dosya Yapısı

aliskanlik-botu/
│
├── bot.py          → Botun ana dosyası, komutlar burada
├── database.py     → Veritabanı işlemleri (kaydet, oku, sil)
└── schedule.db       → SQLite veritabanı dosyası (otomatik oluşur)

# 🗄️ Veritabanı (database.py)


 time_range  → Pratikler arasındaki saat aralıkları    
 habit_name  → Alışkanlık adı ("Spor")      
 date        → Tarih ("2025-06-09")
 I did it or I didn't do it  → çalışma veya çalışmama
 the reason why I cannot work → çalışmama amacı

 #  Nasıl Çalışır? (Akış)

 Kullanıcı Discord botuna türkçe çalışıp çalışmadığını yazar
↓
bot.py komutu yakalar
↓
database.py'deki fonksiyonu çağırır
↓
SQLite veritabanına yazar / okur
↓
Bot sonucu Discord'a gönderir

# Görev Dağılımı

## 👥 Takım Görev Dağılımı (Örnek)

| Kişi | Sorumluluk |
|---|---|
| **Yağız** | `database.db` → Tablo oluşturma, kaydetme, listeleme fonksiyonları |
| **Said** | `bot.py`, `database.py`, `Schedule.db`  kodlarını yazma |
| **Salih** | `README.md` dosyasını yazma + sunum yapma |











































