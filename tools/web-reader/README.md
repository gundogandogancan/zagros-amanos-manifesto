# 📖 Web Reader (Starter)

Statik HTML web reader. **Hiçbir framework, hiçbir build step.** Aç ve oku.

## 🚀 Kullanım

```bash
# 1. Bu klasöre gir
cd tools/web-reader

# 2. Python ile yerel server başlat (veya herhangi bir static server)
python3 -m http.server 8000

# 3. Tarayıcıda aç
open http://localhost:8000
```

## 🎯 Şu an ne yapıyor?

- Manifesto bölümlerini güzel formatla gösterir
- Dil seçici (eklenen çeviriler arasında geçiş)
- Karanlık/aydınlık tema
- Mobil uyumlu

## 🤝 Geliştirilebilir noktalar

- [ ] Tüm çevirilere otomatik geçiş (markdown dosyalarını otomatik bulma)
- [ ] Tam metin arama (Lunr.js / Pagefind)
- [ ] Bölümler arası gezinme (TOC sidebar)
- [ ] Highlight + bookmark (localStorage)
- [ ] Print-friendly CSS
- [ ] PDF/EPUB export butonu
- [ ] Çeviriler arası yan yana karşılaştırma

Hangisini istersen PR aç — 24 saat içinde merge ederiz.

## 📜 Lisans

CC0 — kamu malı. Sahip yok.
