# Satıştan sonra: siteyi yayına almak

Taslak site zaten hazır. Satıştan sonraki iş, onu gerçek bilgilerle tamamlamak ve yayına koymak. Claude Code ile ortalama yarım saat sürer.

## Dükkândan iste
- 4–8 fotoğraf (dükkânın içi, dışı, işlerinden örnekler). Telefonla çekilmiş olabilir.
- Fiyat listesi (ya da "fiyat sorunuz" kalsın mı?)
- Kesin çalışma saatleri, WhatsApp numarası, Instagram hesabı
- İstediği alan adı

## Claude Code'a ver
Proje klasöründe Claude Code'u aç ve şunu yaz:

```
mahalle-avcisi skill'ini kullan. ciktilar/<semt>/siteler/<dükkân> sitesini satışa hazırla.
Fotoğraflar: ./fotograflar/<dükkân>/   Fiyatlar: <listeyi yapıştır>
```

Skill sırasıyla şunları yapar: taslak bandını kaldırır, fotoğrafları küçültüp galeri ekler, fiyatları yazar, metinleri dükkâna göre yeniden yazar, başlık ve Google açıklamasını düzenler, her şeyi telefonda kontrol eder.

## Yayına al (ücretsiz seçenekler)
- **Cloudflare Pages** veya **Netlify**: site klasörünü sürükle-bırak, birkaç dakikada yayında.
- Alan adını (.com.tr / .com) bir kayıt firmasından al, DNS'i bu servise yönlendir.

## Google
- Google İşletme Profili'nde web sitesi alanına yeni adresi yaz. Dükkânın profili yoksa birlikte oluşturun (doğrulama dükkân sahibinin telefonuna/adresine gelir).
