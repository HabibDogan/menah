# İklim Ünitesi Kelime Kartları

Miftahu’l-Arabiyye A2, 2. ünite (المناخ) için telefona kurulabilen kelime kartları ve quiz uygulaması.

## GitHub’a yükleme

1. GitHub’da yeni bir depo (repository) oluştur, örneğin `iklim-kartlari`.
2. Bu klasördeki dosyaların hepsini depoya yükle. `icons` klasörünün içindekiler de klasörüyle birlikte yüklenmeli.
3. Deponun **Settings → Pages** bölümünde “Branch” olarak `main` ve `/ (root)` seçip kaydet.
4. Bir iki dakika sonra uygulama şu adreste açılır: `https://KULLANICI-ADIN.github.io/iklim-kartlari/`

## Telefona kurma

- **Android (Chrome):** Adresi aç, menüden “Uygulamayı yükle” veya “Ana ekrana ekle”yi seç.
- **iPhone (Safari):** Adresi aç, Paylaş düğmesine dokun, “Ana Ekrana Ekle”yi seç.

İlk açılıştan sonra uygulama internetsiz de çalışır.

## Dosyalar

- `index.html`: uygulamanın kendisi (kartlar ve quiz)
- `manifest.webmanifest`: uygulama adı, simgesi ve renkleri
- `sw.js`: internetsiz çalışmayı sağlayan dosya
- `icons/`: uygulama simgeleri

Kelimeleri değiştirmek istersen `index.html` içindeki `RAW` listesini düzenleyebilirsin. Değişiklikten sonra `sw.js` dosyasındaki `iklim-kartlari-v1` adını `v2` yaparsan telefondaki eski sürüm kendiliğinden yenilenir.
