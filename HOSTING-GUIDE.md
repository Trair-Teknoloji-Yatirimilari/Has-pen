# 🚀 HASPEN Web Sitesi - Canlıya Alma Rehberi

## Seçenek 1: GitHub Pages (ÜCRETSİZ - Önerilen)

### Adımlar:
1. GitHub repo ayarlarına git: https://github.com/Trair-Teknoloji-Yatirimilari/Has-pen/settings/pages
2. **Source** bölümünden **main** branch'i seç
3. **Save** butonuna bas
4. 2-3 dakika bekle
5. Site otomatik yayınlanacak: https://trair-teknoloji-yatirimilari.github.io/Has-pen/

### Özel Domain Bağlama:
1. Domain sağlayıcınızda (GoDaddy, Natro, vb.) DNS ayarlarına git
2. Şu kayıtları ekle:
   ```
   A Record: 185.199.108.153
   A Record: 185.199.109.153
   A Record: 185.199.110.153
   A Record: 185.199.111.153
   CNAME: www -> trair-teknoloji-yatirimilari.github.io
   ```
3. GitHub Pages ayarlarında **Custom domain** kısmına `haspen.com.tr` yaz
4. **Enforce HTTPS** seçeneğini aktif et

## Seçenek 2: Netlify (ÜCRETSİZ + Kolay)

### Adımlar:
1. https://netlify.com adresine git
2. GitHub ile giriş yap
3. **New site from Git** butonuna bas
4. Repository'yi seç: Has-pen
5. Deploy settings:
   - Branch: main
   - Build command: (boş bırak)
   - Publish directory: /
6. **Deploy site** butonuna bas
7. Site 1-2 dakikada yayınlanır

### Özel Domain:
1. Netlify dashboard'da **Domain settings**
2. **Add custom domain** → haspen.com.tr
3. DNS kayıtlarını gösterecek, domain sağlayıcınızda ayarla

## Seçenek 3: Klasik Hosting (cPanel)

### Gerekli Dosyalar:
Tüm dosyaları FTP ile `public_html` klasörüne yükle:
- index.html
- css/
- js/
- images/
- blog/
- sitemap.xml
- robots.txt

### FTP Bilgileri (Hosting'den alacaksın):
- Host: ftp.haspen.com.tr
- Username: (hosting'den)
- Password: (hosting'den)
- Port: 21

## ✅ Yayınlandıktan Sonra Yapılacaklar

1. **Google Search Console**
   - https://search.google.com/search-console
   - Site ekle
   - sitemap.xml gönder

2. **Google Analytics**
   - Tracking kodu ekle (index.html head'e)

3. **Test Et**
   - Mobil görünüm
   - Tüm linkler
   - Form çalışıyor mu
   - WhatsApp butonu

4. **SSL Sertifikası**
   - GitHub Pages: Otomatik
   - Netlify: Otomatik
   - cPanel: Let's Encrypt aktif et

## 📊 Site Bilgileri

- **Repository**: https://github.com/Trair-Teknoloji-Yatirimilari/Has-pen
- **Domain**: haspen.com.tr
- **WhatsApp**: 0542 710 08 30

---

**Önerim**: GitHub Pages veya Netlify kullan. Ücretsiz, hızlı ve SSL otomatik geliyor! 🚀
