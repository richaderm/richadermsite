# Richaderm Site

Bu klasördeki `index.html` dosyasını GitHub'a eklerken aşağıdaki noktalara dikkat edin:

- **Tüm görseller (`.jpg`, `.png` vb.) ve video dosyaları** da aynı klasörde olmalı ve GitHub'a yüklenmeli. Örneğin:  
  - `richaderm-logo.jpg`
  - `richaderm-banner.jpg`
  - `richaderm-background.jpg`
  - Ürün görselleri: `ayak-sampuani.jpg`, `ultra-slim-jel.jpg` vs.
  - `tanitim.mp4`
- **Dosya ve klasör isimleri** küçük/büyük harf duyarlıdır. Sunucuda ve GitHub'da dosya adları birebir aynı olmalı.
- **index.html** dosyanızın kök dizinde (`richaderm-site/`) olduğundan emin olun.
- **Görsel ve video dosyalarının yolları** HTML'de doğru yazılmış olmalı (ör: `src="ayak-sampuani.jpg"`).
- **GitHub Pages** kullanıyorsanız, ana sayfa olarak `index.html` dosyasını kullanır.
- **Gizli dosya yoksa** (ör. `.gitignore` ile hariç tutulmadıysa) ve yukarıdaki dosyalar eksiksizse, HTML düzgün görüntülenir.

## Sık Karşılaşılan Sorunlar

- Görseller veya video görünmüyorsa, dosya adları ve yolları yanlış olabilir veya dosyalar eksik yüklenmiş olabilir.
- CSS veya JS dosyaları harici ise, onlar da yüklenmeli veya CDN üzerinden çağrılmalı.
- Dosya yollarında Türkçe karakter veya boşluk olmamasına dikkat edin.

## Kontrol Listesi

Aşağıdaki maddeleri tek tek kontrol edin:

- [ ] `index.html` dosyası kök dizinde mi? (`richaderm-site/index.html`)
- [ ] Tüm görseller (örn. `richaderm-logo.jpg`, `richaderm-banner.jpg`, ürün görselleri) ve videolar (`tanitim.mp4`) aynı klasörde mi ve doğru isimde mi?
- [ ] HTML dosyanızda görsel ve video yolları **doğru** mu? (örn. `src="ayak-sampuani.jpg"` dosya adı ile birebir aynı olmalı)
- [ ] Dosya adlarında **Türkçe karakter** (ı, ğ, ü, ş, ö, ç) veya **boşluk** yok mu?
- [ ] Dosya adlarında **büyük/küçük harf** farkı yok mu? (örn. `Logo.jpg` ≠ `logo.jpg`)
- [ ] `.gitignore` dosyanız görselleri veya videoları hariç tutmuyor mu?
- [ ] Eğer harici CSS/JS kullanıyorsanız, CDN linkleri doğru mu?
- [ ] GitHub Pages ayarlarında doğru branch ve klasör seçili mi? (Genellikle `main` ve `/root`)

## GitHub Pages için Ekstra Notlar

- GitHub Pages'da **bazı görseller görünmüyorsa** dosya adlarını ve yollarını tekrar kontrol edin.
- **index.html** dosyanızın başında `<base href="/">` etiketi **olmasın** (gerekirse kaldırın).
- Eğer özel alan adı kullanıyorsanız, DNS ayarlarınız doğru mu?
- Değişiklik yaptıktan sonra sayfayı yenilemeden önce tarayıcı önbelleğini temizleyin veya gizli sekmede açın.

---

**Not:** Sadece `index.html` dosyasını yüklerseniz ve görseller/videolar eksikse sayfa eksik veya bozuk görünebilir.
