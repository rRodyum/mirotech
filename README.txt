MIROTECH WEB SİTESİ

Bu klasör doğrudan GitHub'a yüklenmeye ve Vercel'de yayınlanmaya hazırdır.
index.html dosyası repository'nin ana dizininde bulunmalıdır.

GITHUB
1. github.com üzerinden giriş yapın.
2. New repository seçin. Repository name alanına mirotech-web yazın.
3. Public veya Private seçin ve Create repository düğmesine basın.
4. uploading an existing file bağlantısını açın.
5. Bu klasörün içindeki dosyaları ve assets klasörünü birlikte sürükleyin.
   ZIP dosyasını veya mirotech-web klasörünün kendisini yüklemeyin.
6. Commit changes düğmesine basın.

VERCEL
1. vercel.com üzerinden GitHub ile giriş yapın.
2. Add New > Project seçin.
3. mirotech-web repository'sini Import ile seçin.
4. Framework Preset alanını Other yapın.
5. Root Directory ana dizin olarak kalsın.
6. Build Command alanını boş bırakın. Gerekirse Override açıp temizleyin.
7. Output Directory alanını boş bırakın. Gerekirse Override açıp temizleyin.
8. Install Command alanını boş bırakın.
9. Deploy düğmesine basın.
10. Başarılı yayın sonunda verilen .vercel.app bağlantısını paylaşın.

Ziyaretçiler hesap açmadan siteyi görebilir.
Site statiktir. Veritabanı, Supabase, ortam değişkeni veya API anahtarı gerekmez.
GitHub ve Vercel hesapları yalnızca sitenin sahibi için gereklidir.
GitHub üzerinden bir dosyayı düzenleyip kaydedince Vercel otomatik yeniden yayınlar.

DOSYALAR
index.html — sayfa metinleri, Peugeot 3008 etiketi ve iletişim bilgileri
style.css — renkler, boyutlar ve sayfa tasarımı
products.js — 64 ürünün parça kodu, OEM, araç uyumu ve özellikleri
site.js — arama, filtreler, ürün penceresi ve 3B ayna dönüşü
assets — ürün fotoğrafları, araç fotoğrafları, özellik simgeleri ve 3B model

KENDİ ALAN ADINIZ
Vercel projesinde Settings > Domains bölümünden .com adresinizi ekleyebilirsiniz.
Ardından Vercel'in gösterdiği DNS kayıtlarını alan adı sağlayıcınızda tanımlayın.
