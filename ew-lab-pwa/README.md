# EW Lab Academy — PWA

## Vercel ile yayınlama
1. Bu ZIP'i bilgisayarda çıkar.
2. `ew-lab-pwa` klasörünün içeriğini bir GitHub deposuna yükle veya Vercel'de yeni proje olarak içe aktar.
3. Framework Preset: **Other**; Build Command ve Output Directory gerekmez (statik site).
4. Deploy et.
5. Vercel'in verdiği HTTPS adresini iPhone'da Safari ile aç.
6. Safari paylaş menüsü → **Ana Ekrana Ekle** → **Aç**.

## Notlar
- HTTPS üzerinden servis worker kaydolur.
- İlk açılıştan sonra uygulama çevrimdışı kullanılabilir.
- İlerleme bilgisi bu cihaz/tarayıcıdaki localStorage'da tutulur.
- PWA kurulumu için dosyayı doğrudan Dosyalar uygulamasından açmak yeterli değildir; HTTPS web adresi gerekir.
