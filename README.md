<img src="readmestrip.jpg" width="600">

Bu repo, [@vimturkce](http://twitter.com/vimturkce) hesabında GIF olarak paylaşılan içerikleri barındırır ve **haftalık olarak güncellenir**.

Aşağıdaki listede komutları gruplarına göre yanlarına ufak açıklamalar yazarak ayırdım. GIF dosyalarını görüntülemek ve başlıkla ilgili bilgiye erişmek için bağlantıya tıklamanız yeterli.

### Başlıklar

### girdi modu
- [`<C-o>` - girdi modu içinde tek komut için normal moda geçiş yapmak](gifs/2_ctrl-o)
- [`S`, `C` - girdi moduna girmek](gifs/4_S-C-girdi-moduna-gecmek)
- [girdi modundan çıkarken dosyanın otomatik kaydedilmesi](gifs/28_girdi-modu-ve-dosyanin-kaydedilmesi)
- [`inoremap ( ()<ESC>i` ― otomatik parantez tamamlamak](gifs/30_parantez-tamamlama)

### normal mod
- [`ciw` - imlecin üzerinde bulunan kelimeyi silmek](gifs/5_ciw-kelime-silmek)
- [`<C-k> ile diagraf (özel karakter) basmak`](gifs/6_ozel-karakter-basmak)
- [`%` - parantez çiftlerinde atlama yapmak](gifs/7_parentiz-ciftleri-atlama)
- [`dn` - en son aranan kelimeye kadar silmek](gifs/9_aranan-kelimeye-kadar-silme)
- [`g+`, `g-` - undo branching](gifs/8_undo-branching)
- [`~` - karakteri büyük/küçük harf değiştirmek](gifs/11_buyuk-kucuk-harf)
- [`ga` - *ascii*, *hex* ve *octal* değerleri göstermek](gifs/12_ascii-hex-octal-deger)
- [`:mksession` - oturum dosyası oluşturmak](gifs/13_oturum_dosyasi_olusturmak)
- [`xp` - karakterlerin yerini değiştirmek](gifs/15_xp-karakterleri-degistir)
- [`:m<satir>` - satır taşımak](gifs/16_m-satir-tasimak)
- [`sistem komutu çalıştırmak`](gifs/17_harici-komut-calistirmak)
- [`<C-a>` `<C-x>` ― karakter/sayı artırmak](gifs/18_karakter-artirmak)
- [bölmelerin kullanımı](gifs/19_bolmelerle-coklu-dosya-acmak)
- [`ri` `ce` `le` ― metin hizalamak](gifs/21_metin-hizalamak)
- [`vimgrep /hey/ **/*` ― birden fazla dosyada arama yapar](gifs/23_coklu-dosya-deger-arama)
- [`:g/hey/d` ― eşleşen değerin bulunduğu satırı siler](gifs/24_g-eslesen-satiri-silmek)
- [`zfa` ― açılır-kapanır kod blokları](gifs/25_acilir-kapanir-bloklar)
- [`<C-p>` ― otomatik kelime/ifade tamamlama](gifs/27_kelime-tamamlama)
- [`:!sudo tee %` ― sudo yetkisiyle dosya kaydetmek](gifs/29_sudo-dosya-kaydetmek)
- [`:w >> b.js` ― verilen satır aralığını bir başka dosyaya yazmak](gifs/31_satir-araligini-dosyaya-yazmak)
- [`:g/^/m0` ― satırları ters çevirmek](gifs/32_dosya-satirlarini-ters-cevirmek)
- [`:sort u` ― aynı satırları silmek](gifs/33_ayni-satirlari-silmek)
- [`%s/\<a\>/b/gc` ― tam eşleşenler için bul-değiştir](gifs/34_tam-eslesme-ara-ve-degistir)
- [`%s/a/b/gc` ― etkileşimli bul-değiştir ](gifs/35_etkilesimli-bul-degistir)
- [`<C-v> g <C-a>` ― çoklu satırda sayı artırmak](gifs/36_coklu-satirda-sayi-artirmak)
- [`%s/kelime//gn` ― aranan değer için eşleşme sayısını bulmak](gifs/40_kelime-eslesme-sayisi)

### atlamalar (*jumps*)
- [`f`, `F` ve `t`, `T` - satıriçi aranan harfe atlama yapmak](gifs/10_satirici-aranan-harfa-atlama)
-  [`gd` ― kelimenin ilk tanımlandığı konuma atlamak](gifs/26_gd-tanima-atlamak)
-  [`20%` ― yüzde oranlı satır atlamak](gifs/37_yuzde-oranli-satir-atlamak)

### işaretleyiciler (*markers*)
- [işaretleyicilerin (*markers*) kullanımı](gifs/22_isaretler)

### yazmaçlar (*registers*)
- [`"+p` - sistem panosundan yapıştırmak](gifs/3_panodan-yapistirmak)

### makrolar
- [`qa` - makro kaydetmek](gifs/14_makro-kaydetmek)
- [`ia<ESC>qqylp<C-a>q24@q` ― tüm alfabeyi ekrana basar](gifs/20_alfabeyi-basmak)
