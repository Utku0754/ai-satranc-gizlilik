# AI Satranç — Gizlilik Politikası Sayfası

Tek dosyalık, bağımsız statik sayfa. Hiçbir bağımlılığı yok; herhangi bir
statik barındırmada çalışır (GitHub Pages, Cloudflare Pages, Netlify).

- `index.html` — Türkçe
- `en/index.html` — İngilizce

## GitHub Pages ile yayınlama

1. GitHub'da yeni bir repo aç, adı `ai-satranc-gizlilik` olsun (public olmalı).
2. Bu klasördeki `index.html` ve `en/` klasörünü repoya yükle
   (GitHub arayüzünde "Add file → Upload files" yeterli, terminal gerekmez).
3. Repo → **Settings** → sol menüden **Pages**.
4. "Build and deployment" altında Source olarak **Deploy from a branch**,
   Branch olarak **main** ve klasör olarak **/ (root)** seç, **Save** de.
5. Bir iki dakika içinde adres yayına girer:

       https://KULLANICI-ADIN.github.io/ai-satranc-gizlilik/

6. Adresi tarayıcıda açıp çalıştığını doğrula.

## App Store Connect'e girme

App Store Connect → uygulama → **App Privacy** → Privacy Policy → **Edit** →
Privacy Policy URL alanına yukarıdaki adresi yaz ve kaydet.

Şu an girili olan adres `https://ellturco.com/zerochess/gizlilik` — o sayfa
canlıya alınmadıysa bunun yerine GitHub Pages adresini gir.

## Not

Sayfa açık/koyu temayı sistem ayarına göre kendisi ayarlar, mobilde de
düzgün görünür. İçerik `GIZLILIK-POLITIKASI.md` ile aynıdır; uygulama adı
"AI Satranç" olarak güncellenmiştir.
