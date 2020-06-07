![](65.gif)

## `dw"_diti${}<ESC>p`

#### komut açıklamaları

- `dw` ― imlecin önündeki kelimeyi siler
- `"_dit` ― imlecin üzerinde bulunduğu tag nesnesinin (örnekte *apiKey*) içeriğini siler ve silinen değeri `"_` (blackhole) yazmacına taşır 
- `i${}<ESC>` ― girdi moduna girer ve `${}` karakterlerini yazar ve normal moda döner
- `p` ― panodaki son değeri (`dw` işleminde silinen değeri vim panosuna) yapıştırır

`:help reg`
