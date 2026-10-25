DEFINE İŞARET REHBERİ — KURULUM VE YAYINLAMA

Bu klasör, iPhone'da Safari üzerinden açılabilen, yeşil-altın temalı ve çevrimdışı kullanım destekli basit bir web uygulamasıdır.

DOSYALAR
- index.html: Uygulamanın ekranı ve içerikleri
- manifest.webmanifest: Ana ekrana eklenebilir uygulama bilgileri
- service-worker.js: İlk açılıştan sonra çevrimdışı önbellek
- icon.svg: Uygulama simgesi

EN KOLAY YAYINLAMA: NETLIFY DROP
1. Bilgisayarda ZIP dosyasını açın; içindeki define-isaret-rehberi klasörünü bulun.
2. https://app.netlify.com/drop adresini açın. Netlify hesabı açmanız istenirse ücretsiz hesap oluşturun.
3. Klasörü sürükleyip bırakın. Yalnızca ZIP dosyasını değil, içindeki dosyaların bulunduğu klasörü yükleyin.
4. Netlify size https://...netlify.app biçiminde HTTPS adresi verir. Bu adresi iPhone'da Safari ile açın.
5. Çevrimdışı kullanım için sayfanın ilk kez tamamen yüklenmesini bekleyin.
6. iPhone'da Safari paylaş simgesine dokunun → Ana Ekrana Ekle → Ekle.

GITHUB PAGES ALTERNATİFİ
1. https://github.com adresinde oturum açın ve yeni bir public repository oluşturun.
2. Bu klasördeki dört dosyayı repository'nin en üst seviyesine yükleyin.
3. Repository → Settings → Pages bölümünü açın.
4. Build and deployment altında Deploy from a branch seçin; branch olarak main, klasör olarak /(root) seçip Save'e basın.
5. Yayınlanan https://kullaniciadi.github.io/repository-adi/ adresini iPhone Safari'de açın.
6. İlk yükleme tamamlandıktan sonra Ana Ekrana Ekle seçeneğini kullanın.

ÇEVRİMDIŞI KULLANIM
- Service worker HTTPS gerektirir; Netlify ve GitHub Pages bunu otomatik sağlar.
- Siteyi ilk kez internet varken açın ve tamamen yüklenmesini bekleyin.
- Safari'den Ana Ekrana Ekle, uygulama benzeri bir kısayol sağlar.
- Site dosyalarını değiştirirseniz service-worker.js içindeki CACHE_NAME değerini artırın (ör. v2) ve yeniden yayınlayın.

NOT
Bu rehber tarihî/kültürel bilgilendirme amaçlıdır. İşaretler tek başına define kanıtı değildir. İzinsiz kazı yapmayın; tarihî buluntuları yerinden oynatmayın. Gerçek kullanımda güncel hukuk ve kurum yönlendirmeleri için yetkili makamlara başvurun.
