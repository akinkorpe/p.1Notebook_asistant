# 🧠 Kişisel Asistan CLI Uygulaması

Python kullanarak geliştirdiğim bu kişisel asistan projesi, komut satırı (CLI) üzerinden not almanızı, arama yapmanızı, kayıtlı notları görüntülemenizi ve istatistiksel analizler yapmanızı sağlar.

## 🎯 Özellikler

- 📝 **Not Ekleme:** Kullanıcıdan not alır, tarih ve saat bilgisiyle birlikte `notlar.txt` dosyasına kaydeder.
- 📚 **Notları Listeleme:** Kayıtlı tüm notları ekrana listeler.
- 🔍 **Anahtar Kelime Arama:** Notlar içinde kelime araması yapar, eşleşenleri listeler.
- 📊 **İstatistik Gösterimi:**
  - Toplam not sayısı
  - Toplam karakter sayısı
  - En uzun not
  - En çok tekrar eden kelime

## 🛠️ Kullanılan Teknolojiler

- Python 3
- Dosya işlemleri (I/O)
- Fonksiyonlar ve modüler yapı
- `datetime` modülü
- `collections.Counter` (kelime analizleri için)

## 🚀 Nasıl Kullanılır?

1. Bu projeyi klonlayın veya `.py` dosyasını bilgisayarınıza indirin:
   ```bash
   git clone https://github.com/kullaniciadi/kisisel-asistan.git
   cd kisisel-asistan
   python3 asistan.py