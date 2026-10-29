# Kaşifya sitesini ücretsiz yayına alma (GitHub Pages)

Sonuç adresi: **https://kasifya.github.io**
- Tanıtım sayfası: `https://kasifya.github.io/`
- Uygulama: `https://kasifya.github.io/uygulama/`
- Veri güvenliği ve KVKK: `https://kasifya.github.io/veri-ve-kvkk.html`

## 1. Hesap aç
1. https://github.com/signup adresine girin.
2. Kullanıcı adı olarak **kasifya** yazın. Alınmışsa `kasifya-fen` gibi bir ad seçin; adresiniz de `kasifya-fen.github.io` olur.

## 2. Depo oluştur
1. Sağ üstte **+ › New repository**.
2. Repository name: **kasifya.github.io**. Bu ad, kullanıcı adınızla birebir aynı olmalı.
3. **Public** seçin, **Create repository** deyin.

## 3. Dosyaları yükle
1. Depo sayfasında **uploading an existing file** bağlantısına (ya da **Add file › Upload files**) tıklayın.
2. Bu paketteki her şeyi sürükleyip bırakın: `index.html`, `veri-ve-kvkk.html`, `lisans.html`, `LICENSE`, `.nojekyll`, `uygulama` ve `img` klasörleri. Zip'in kendisini değil, içindekileri bırakın.
   - `.nojekyll` gizli dosya olduğu için görünmeyebilir. Görünmezse sorun değil.
   - Uygulama dosyası 23,5 MB. Web yükleme sınırı dosya başına 25 MB olduğu için sığar.
3. Altta **Commit changes** deyin.

## 4. Yayını aç
1. **Settings › Pages**.
2. Source: **Deploy from a branch**. Branch: **main**, klasör: **/ (root)**. **Save** deyin.
3. 1–2 dakika sonra sayfanın üstünde adresiniz görünür.

## 5. Verileri taşı (bir kez)
Tarayıcı verileri adrese bağlıdır. Yeni adreste uygulama ilk açılışta boş gelir.
En kolayı flash bellek: eski dosyada **Panel › Yedek ve veri › Flash bellekle her yerde › Flash belleği / klasörü seç** ile flash bellekteki bir klasörü seçin. Yeni adreste aynı klasörü seçince veriler kendiliğinden gelir.
Ya da: eski dosyada **Veri dosyasını indir**, yeni adreste **Dosyadan birleştir**.

## 6. Güncelleme
Yeni sürüm geldiğinde `uygulama/index.html` dosyasını aynı yolla yeniden yükleyin (Add file › Upload files). Veriler silinmez.

## Daha sonra alan adı alırsanız
1. Settings › Pages › **Custom domain** kutusuna alan adınızı (ör. `kasifya.com.tr`) yazın.
2. Alan adı firmasının DNS paneline şu dört A kaydını ekleyin:
   `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
3. `www` için CNAME kaydı ekleyin: `kasifya.github.io`
4. Ayar oturunca **Enforce HTTPS** kutusunu işaretleyin.

Not: Alan adı değişirse veriler yine adrese bağlı olduğu için 5. adımı tekrarlayın.

## Telif
`LICENSE` ve `lisans.html` kullanım koşullarını içerir: öğretmenler ücretsiz kullanabilir, izinsiz kopyalanamaz, değiştirilemez, dağıtılamaz ve satılamaz. Bu iki dosyayı da depoya yükleyin.
