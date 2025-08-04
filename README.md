# 📱 Contact Manager - VCF Export

Excel dosyalarından kişileri okuyup VCF formatında dışa aktaran web uygulaması.

## ✨ Özellikler

- 📊 **Excel Desteği**: `.xlsx`, `.xls` formatlarını okur
- 🔤 **Akıllı İsim Birleştirme**: Farklı hücrelerdeki ad ve soyadı birleştirir
- 📞 **Esnek Telefon Bulma**: Son sütundaki telefon numaralarını bulur
- 🇹🇷 **Türkçe Karakter Desteği**: İ, ı, ğ, ü, ş, ö, ç karakterlerini doğru işler
- 🚫 **Tekrar Temizleme**: Aynı telefon numaralı kişileri filtreler
- 📱 **VCF Export**: Toplu telefon rehberi oluşturur
- 🎯 **Drag & Drop**: Dosyaları sürükleyip bırakabilirsiniz

## 🚀 Kullanım

1. **Dosya Yükle**: Excel dosyanızı sürükleyin veya seçin
2. **Kontrol Et**: Bulunan kişileri inceleyin
3. **VCF İndir**: Telefon rehberiniz hazır!

## 📋 Excel Formatı

Uygulamanız şu Excel formatını destekler:

| A Sütunu (Ad) | B Sütunu (Soyad) | C, D, E... | Son Sütun (Telefon) |
|---------------|-------------------|------------|---------------------|
| Berat         | Yılmaz           | ...        | 5443098337          |
| Berat Ahmet   | Yılmaz           | ...        | 5350820278          |
| Mehmet Ali    | Demir            | ...        | 5518589744          |
| İbrahim       | Çelik            | ...        | 5551234567          |

## 💡 Akıllı Özellikler

### 🔤 Çoklu İsim Desteği
- ✅ "Berat" + "Yılmaz" → "Berat Yılmaz"
- ✅ "Berat Ahmet" + "Yılmaz" → "Berat Ahmet Yılmaz"
- ✅ "Mehmet Ali Can" + "Demir" → "Mehmet Ali Can Demir"

### 🇹🇷 Türkçe Karakter Düzeltme
- ✅ "ibrahim" → "İbrahim"
- ✅ "ISTANBUL" → "İstanbul"
- ✅ "ahmet" → "Ahmet"
- ✅ "ismail" → "İsmail"

### 📞 Telefon Format Desteği
- ✅ 5443098337
- ✅ 0544 309 83 37
- ✅ +90 544 309 83 37
- ✅ (544) 309-83-37

### 🚫 Tekrar Temizleme
- Aynı telefon numaralı kişiler otomatik filtrelenir
- Çiftlenen kayıtlar temizlenir
- Tek seferde temiz liste elde edersiniz

## 🛠️ Teknolojiler

- **HTML5**: Modern web standartları
- **CSS3**: Responsive tasarım ve animasyonlar
- **JavaScript**: Vanilla JS - framework gereksiz
- **SheetJS**: Excel dosya okuma kütüphanesi
- **PapaCSV**: CSV dosya desteği

## 📱 Desteklenen Formatlar

**📥 Giriş:**
- Excel (.xlsx, .xls)
- CSV (.csv)
- Metin (.txt)

**📤 Çıkış:**
- VCF (vCard) formatı
- Tüm telefon sistemleri ile uyumlu

## 🔧 Kurulum

Kurulum gerektirmez! Tarayıcınızda açın ve kullanın.

```bash
# İsteğe bağlı: Yerel kopya oluşturun
git clone https://github.com/[kullanici-adi]/contact-manager-vcf.git
cd contact-manager-vcf
# index.html dosyasını açın
```

## 🎯 Kullanım Senaryoları

- **İş Yerinden**: Personel listelerini telefon rehberine aktarma
- **Etkinliklerden**: Katılımcı listelerini organize etme
- **Müşteri Listesi**: CRM verilerini mobil cihaza aktarma
- **Okul/Kurs**: Öğrenci velilerinin iletişim bilgileri

## 🔍 Debug Özellikleri

- **Detaylı Loglar**: Her işlem adımını görebilirsiniz
- **Hata Ayıklama**: Problemli satırları tespit eder
- **İşlem Takibi**: Hangi kişilerin eklendiği/atlandığı görülür

## 📈 Son Güncellemeler

### v2.0 - Major Update
- 🇹🇷 **Türkçe karakter desteği** eklendi
- 📞 **Son sütun telefon** desteği
- 🚫 **Tekrar temizleme** özelliği
- 🔤 **Çoklu isim** birleştirme
- 🎨 **UI iyileştirmeleri**

## 🤝 Katkıda Bulunma

1. Fork edin
2. Feature branch oluşturun (`git checkout -b feature/yeni-ozellik`)
3. Commit edin (`git commit -am 'Yeni özellik eklendi'`)
4. Push edin (`git push origin feature/yeni-ozellik`)
5. Pull Request oluşturun

## 🐛 Bilinen Sorunlar

Bilinen ciddi bir sorun bulunmuyor. Sorun yaşarsanız:
- [Issue açın](../../issues)
- Debug loglarını kontrol edin
- Excel dosya formatını kontrol edin

## 🌟 Gelecek Özellikler

- [ ] 📊 **Excel export** (VCF'den Excel'e dönüş)
- [ ] 📧 **Email desteği** (kişilerin email bilgileri)
- [ ] 🏢 **Şirket bilgileri** desteği
- [ ] 🔗 **QR kod** oluşturma
- [ ] 📱 **Toplu SMS** gönderme entegrasyonu

## 📞 İletişim

Proje ile ilgili sorularınız için [GitHub Issues](../../issues) kullanın.

---

**⭐ Faydalı bulduysanız yıldız vermeyi unutmayın!**
