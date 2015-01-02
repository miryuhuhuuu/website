# Website Haskell-id

Kode sumber website haskell-id. Powered by [hakyll](http://jaspervdj.be/hakyll/index.html)

## Menjalankan secara Lokal

**Dependensi:**

- GHC (Glasgow Haskell Compiler)
- cabal minimal versi 1.18 (fitur sanbox)

```
git clone git@github.com:haskell-id/website.git
cd website/
cabal sandbox init
cabal install --only-dependencies
cabal install
./.cabal-sanbox/bin/site watch
```
## Penerjemahan

Sedang dalam proses pengerjaan penerjemahan materi [kuliah di UPenn](http://www.seas.upenn.edu/~cis194/spring13/lectures.html)

Status:

```
chapter 1: Done
chapter 4: Done
chapter 5: Done
```

Meski beberapa bab sudah selesai, tidak menutup kemungkinan untuk dikoreksi baik dari kesalahan tulis maupun terjemahan yang lebih baik.

Jika tertarik membantu, silakan update status di atas. Koreksi dan saran bisa melalui *issues*.
