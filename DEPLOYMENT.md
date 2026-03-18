# HASPEN Web Sitesi - Yayınlama Rehberi

## 🚀 Hosting'e Yükleme

### 1. Hosting Seçenekleri

**Önerilen Hosting Firmaları:**
- **Natro Hosting** (Türkiye, uygun fiyat)
- **Turhost** (Türkiye, güvenilir)
- **Hostinger** (Uluslararası, ekonomik)
- **DigitalOcean** (Gelişmiş, VPS)

### 2. Domain Alma

**Önerilen Domain:**
- haspen.com.tr (Türkiye)
- haspen.com (Global)

**Domain Nereden Alınır:**
- GoDaddy
- Natro
- Turhost

### 3. Dosyaları Yükleme

**FTP ile Yükleme:**
1. FileZilla veya Cyberduck kullanın
2. Hosting FTP bilgilerinizi girin
3. Tüm dosyaları `public_html` veya `www` klasörüne yükleyin

**Yüklenecek Dosyalar:**
```
/
├── images/
├── blog/
├── css/
├── js/
├── index.html
├── sitemap.xml
├── robots.txt
└── README.md
```

### 4. SSL Sertifikası

**Ücretsiz SSL:**
- Let's Encrypt (çoğu hosting otomatik sağlar)
- Cloudflare (ücretsiz)

**Kurulum:**
1. Hosting panelinden SSL aktif edin
2. HTTPS'e yönlendirme yapın

### 5. Google Entegrasyonları

**Google Search Console:**
1. https://search.google.com/search-console
2. Site ekleyin
3. `sitemap.xml` gönderin

**Google Analytics:**
1. https://analytics.google.com
2. Tracking ID alın
3. `index.html` head bölümüne ekleyin:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXXXX"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-XXXXXXXXXX');
</script>
```

**Google My Business:**
1. İşletmenizi kaydedin
2. Adres ve telefon bilgilerini ekleyin
3. Fotoğraflar yükleyin

### 6. Sosyal Medya Entegrasyonu

**Güncellenecek Linkler:**
- Instagram: `index.html` içinde `#` olan yerleri gerçek link ile değiştirin
- Facebook: Aynı şekilde
- WhatsApp: Zaten aktif (0542 710 08 30)

### 7. E-posta Kurulumu

**Profesyonel E-posta:**
- info@haspen.com.tr
- iletisim@haspen.com.tr

**Kurulum:**
1. Hosting panelinden e-posta oluşturun
2. Gmail veya Outlook'a bağlayın

### 8. Performans Optimizasyonu

**Cloudflare (Ücretsiz CDN):**
1. https://cloudflare.com kayıt olun
2. Domain'i ekleyin
3. Nameserver'ları değiştirin
4. Otomatik hızlandırma aktif

**Görsel Optimizasyonu:**
- Proje fotoğraflarını eklemeden önce sıkıştırın
- TinyPNG.com kullanın
- WebP formatına çevirin

### 9. Güvenlik

**Öneriler:**
- Düzenli yedekleme yapın
- Hosting paneli şifresini güçlü tutun
- 2FA (İki faktörlü doğrulama) aktif edin

### 10. Bakım ve Güncelleme

**Düzenli Yapılacaklar:**
- Blog'a ayda 1-2 makale ekleyin
- Proje fotoğraflarını güncelleyin
- Müşteri yorumlarını ekleyin
- Google Analytics'i kontrol edin

## 📊 SEO Kontrol Listesi

- [x] Sitemap.xml oluşturuldu
- [x] Robots.txt oluşturuldu
- [x] Meta description'lar eklendi
- [x] Alt text'ler (görseller eklenince)
- [ ] Google Search Console'a ekle
- [ ] Google Analytics ekle
- [ ] Google My Business kayıt
- [ ] Sosyal medya linkleri güncelle

## 🎯 İlk Hafta Yapılacaklar

1. ✅ Domain al
2. ✅ Hosting al
3. ✅ Dosyaları yükle
4. ✅ SSL aktif et
5. ✅ Google Search Console ekle
6. ✅ Google Analytics ekle
7. ✅ Sosyal medya linkleri güncelle
8. ✅ Gerçek proje fotoğrafları ekle
9. ✅ Test et (mobil + desktop)
10. ✅ Duyuru yap!

## 📞 Destek

Sorularınız için:
- GitHub: https://github.com/Trair-Teknoloji-Yatirimilari/Has-pen
- E-posta: (eklenecek)

---

**Not:** Bu site tamamen hazır ve yayına alınmaya hazır durumda!
