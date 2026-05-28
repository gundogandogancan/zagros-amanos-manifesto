# 🤝 Katkıda Bulunma · Contributing

> **Söz veriyoruz: tüm PR'lar 24 saat içinde merge edilir.** Hızla büyüyen bir topluluk.
>
> **We promise: all PRs merged within 24 hours.** A community moving fast.

---

## 🇹🇷 Türkçe

### En hızlı yol

**Sadece fork + edit + PR aç.** Tartışma gerektirmez. Yüksek kalite + iyi niyet = merge.

```bash
# 1. Fork et (GitHub UI'dan tek tıkla)
# 2. Klonla
git clone https://github.com/SENİN_KULLANICIN/zagros-amanos-manifesto.git
cd zagros-amanos-manifesto

# 3. Branch aç
git checkout -b ozellik/web-reader-search

# 4. Çalış (ne istersen: çeviri, kod, sanat, yorum)

# 5. Commit + push
git add .
git commit -m "feat: arama özelliği eklendi"
git push origin ozellik/web-reader-search

# 6. GitHub'da Pull Request aç
```

Sonra ne olur? 24 saat içinde:
- ✅ Otomatik welcome mesajı gelir
- ✅ Hızlı review
- ✅ Merge

### Ne tür katkı yapabilirsin?

| Kategori | Klasör | Issue Template |
|----------|--------|----------------|
| 🌍 Çeviri | `manifesto/translations/[dil]/` | Translation |
| ✍️ Yorum | `annotations/` | Annotation |
| 💬 Tartışma | `discussions/` veya Issue | Discussion |
| 🛠️ Yazılım/Kod | `tools/[proje-adı]/` | Tool/Code |
| 🎨 Sanat | `assets/[tür]/` | Art/Media |
| 🛠️ Düzeltme | her yerde | Correction |

### Kod katkısı için

- **Hangi dil olursa olsun** — Python, JavaScript, Rust, Go, Swift, Kotlin
- **Hangi framework olursa olsun** — Astro, Next.js, Hugo, Flutter, React Native
- **Tek kural:** `tools/[proje-adı]/README.md` yaz, nasıl çalıştırılır anlat
- **Lisans:** CC0 (kamu malı) — başka lisans kabul edilmez
- **Bağımlılıklar:** MIT, Apache, BSD gibi uyumlu lisanslar olmalı

### Çeviri katkısı için

- `manifesto/translations/[ISO-dil-kodu]/` klasörü oluştur
- Markdown formatında (`00-preface.md`, `01-bolum.md`, vs.)
- Komple bitirmek zorunda değilsin — bölüm bölüm gönderebilirsin
- Çeviri sırasında not düşmek istersen: `---` ile ayır, `> Çevirmen notu:` ile başla

### Sanat katkısı için

- `assets/[tür]/` altına dosya
- Yüksek çözünürlük
- Telifsiz veya kendi eserin
- Dosya adı: `senin-adın-konu-tarih.uzantı`

---

## 🇬🇧 English

### Fastest path

**Just fork + edit + PR.** No discussion required. Good quality + good intent = merged.

```bash
git clone https://github.com/YOUR_USERNAME/zagros-amanos-manifesto.git
cd zagros-amanos-manifesto
git checkout -b feature/web-reader-search

# do work

git add .
git commit -m "feat: add search to web reader"
git push origin feature/web-reader-search

# open PR on GitHub
```

Then: within 24 hours you get a welcome message + review + merge.

### What can you contribute?

| Type | Folder | Issue Template |
|------|--------|----------------|
| 🌍 Translation | `manifesto/translations/[lang]/` | Translation |
| ✍️ Annotation | `annotations/` | Annotation |
| 💬 Discussion | `discussions/` or Issue | Discussion |
| 🛠️ Software/Code | `tools/[project-name]/` | Tool/Code |
| 🎨 Art | `assets/[type]/` | Art/Media |
| 🛠️ Correction | anywhere | Correction |

### For code contributions

- **Any language** — Python, JavaScript, Rust, Go, Swift, Kotlin
- **Any framework** — Astro, Next.js, Hugo, Flutter, React Native
- **One rule:** write a `tools/[project]/README.md` explaining how to run
- **License:** CC0 (public domain) — no other license accepted
- **Dependencies:** must use compatible licenses (MIT, Apache, BSD, etc.)

### For translations

- Create `manifesto/translations/[ISO-lang-code]/`
- Markdown format (`00-preface.md`, `01-chapter.md`, etc.)
- You don't have to finish everything — submit chapter by chapter
- For translator notes: separate with `---`, start with `> Translator's note:`

### For art

- File under `assets/[type]/`
- High resolution
- Public domain or your own work
- Filename: `your-name-topic-date.ext`

---

## 📜 Lisans onayı / License confirmation

Her katkı **CC0 1.0 Universal** lisansı altında — yani kamuya armağan. Bu, sonsuza dek herkes tarafından, her amaçla kullanılabilir demektir. Telif hakkı talep edemezsin.

Every contribution is under **CC0 1.0 Universal** — meaning dedicated to public domain. This means anyone, forever, can use it for any purpose. You cannot claim copyright.

**PR açtığında bu lisansı kabul etmiş sayılırsın.**
**By opening a PR, you accept this license.**

---

## 🚫 Kabul edilmeyenler / What we don't accept

- ❌ Telifli içerik (başka bir kitap, makale, vs.)
- ❌ Hate speech veya ayrımcılık
- ❌ Belirli bir parti/devlet propagandası
- ❌ Spam veya alâkasız reklam
- ❌ Başka bir lisans (sadece CC0)
- ❌ Çalışmayan/buggy kod (test et önce)

---

## 🌳 Felsefemiz / Our philosophy

Bu proje **iki dağ gibi** — sırtını dayadığında yıkılmaz. Senin katkın bir taş daha. Her taş önemli.

This project is **like two mountains** — when you lean on it, it doesn't fall. Your contribution is one more stone. Every stone matters.

*Wek du çiyayên pişt re ye*
