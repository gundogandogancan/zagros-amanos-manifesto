# Katkıda Bulunma Rehberi · Contributing Guide

## 🇹🇷 Türkçe

Zagros Amanos manifestosuna katkıda bulunmak istediğin için teşekkürler. Bu döküman nasıl katkı yapacağını adım adım anlatır.

### Hangi katkılar kabul edilir?

✅ **Çeviriler** — manifestoyu kendi dilinde aktarmak  
✅ **Düzeltmeler** — yazım, gramer, eksik referans  
✅ **Açıklamalar / yorumlar** — `annotations/` klasörüne kişisel veya akademik notlar  
✅ **Tartışmalar** — `discussions/` klasörüne uzun-form yazılar  
✅ **Sanat eserleri** — manifestoya ait illüstrasyon, ses kayıtları, video  
✅ **Web sitesi katkısı** — özgün versiyon [zagrosamanos.com](https://zagrosamanos.com) için öneriler

### Hangi katkılar kabul edilmez?

❌ Nefret söylemi içeren değişiklikler  
❌ Belirli bir parti/grubu yücelten propagandaya çeviren içerik  
❌ Telifli üçüncü taraf eserlerini izinsiz dahil etmek  
❌ Doxxing, kişisel bilgi ifşası

### Çeviri yapacaksan

1. **`manifesto/translations/[dil-kodu]/`** klasörü oluştur.  
   Örnekler: `en` (English), `ku` (Kurmancî), `ar` (Arabic), `fa` (Persian), `de` (German), `el` (Greek), `hy` (Armenian), `syr` (Syriac), `fr` (French), `es` (Spanish)

2. Bölüm bölüm gidebilirsin. Hepsini bitirmek zorunda değilsin.  
   Örnek dosya isimleri:
   - `00-preface.md`
   - `01-introduction.md`
   - `02-chapter-one.md`
   - …

3. **Markdown formatında** yaz. PDF değil, Word değil, `.md`.

4. **Header ve yapıyı koru** — orijinal manifestodaki bölüm sıralaması aynı kalsın.

5. **Çevirmen notu** ekleyebilirsin (`> Not: bu kelime kültürel olarak…` gibi).

6. Çeviri hâlâ devam ediyorsa `WIP` (Work In Progress) ekle dosya başına.

### Açıklama (annotation) yazacaksan

1. **`annotations/`** altına dosya ekle.
2. Dosya adı: `seninAdin-konu.md` formatında (örn: `mehmet-tarihselbaglam.md`)
3. Akademik, kişisel, eleştirel — her ton kabul.
4. Manifesto'dan alıntı yaparken bölüm referansı ver.

### Pull request süreci

1. **Fork** et bu repoyu
2. Yeni bir **branch** aç: `git checkout -b ku-translation-chapter-1`
3. Değişikliklerini commit et: `git commit -m "translate chapter 1 to kurmancî"`
4. **Push** et: `git push origin ku-translation-chapter-1`
5. GitHub'da **Pull Request** aç
6. Şablonu doldur (otomatik açılır)
7. Bekleme süresi: 3-7 gün arası genelde dönülür

### Sorun çıkarsa

Bu repo bir manifestoyu paylaşmak için var, kavga için değil. Anlaşmazlık olursa:

1. **Issues**'a bir konu aç
2. Karşılıklı saygıyla konuş
3. Yine de çözülmezse `com@zagrosamanos.com` adresine yaz

---

## 🇬🇧 English

Thank you for contributing to the Zagros Amanos manifesto. This document explains how to contribute step by step.

### What contributions are welcome?

✅ **Translations** into any language  
✅ **Corrections** — typos, grammar, missing references  
✅ **Annotations / commentary** in the `annotations/` folder  
✅ **Discussions** — long-form pieces in `discussions/`  
✅ **Art** — illustrations, audio recordings, video relating to the manifesto  
✅ **Website improvements** — suggestions for [zagrosamanos.com](https://zagrosamanos.com)

### What is not accepted?

❌ Hate speech edits  
❌ Content that converts the manifesto into propaganda for a specific party/group  
❌ Copyrighted third-party works included without permission  
❌ Doxxing, personal info disclosure

### If you're translating

1. Create a folder: **`manifesto/translations/[lang-code]/`**  
   Examples: `en`, `ku` (Kurmancî), `ar`, `fa`, `de`, `el`, `hy`, `syr`, `fr`, `es`

2. You can translate section by section. No need to finish everything.  
   Suggested filenames:
   - `00-preface.md`
   - `01-introduction.md`
   - `02-chapter-one.md`
   - …

3. Use **Markdown format**. Not PDF, not Word.

4. **Preserve structure** — keep section order from the original.

5. You may add **translator notes** (`> Note: this word culturally…`).

6. Add `WIP` to file header if translation is in progress.

### If you're annotating

1. Create file in **`annotations/`**.
2. Filename format: `yourName-topic.md` (e.g., `sarah-historicalContext.md`)
3. Academic, personal, critical — all tones welcome.
4. When quoting the manifesto, include section reference.

### Pull request process

1. **Fork** this repository
2. Create a new **branch**: `git checkout -b en-translation-chapter-1`
3. Commit your changes: `git commit -m "translate chapter 1 to english"`
4. **Push**: `git push origin en-translation-chapter-1`
5. Open a **Pull Request** on GitHub
6. Fill the template (opens automatically)
7. Response time: usually 3-7 days

### If a conflict arises

This repo exists to share a manifesto, not to argue. If disagreement happens:

1. Open an **issue**
2. Discuss with mutual respect
3. If still unresolved, email `com@zagrosamanos.com`

---

## 📋 Quick reference / Hızlı başvuru

| Action | Folder | File format |
|---|---|---|
| Translate | `manifesto/translations/[lang-code]/` | `.md` |
| Annotate | `annotations/` | `.md` |
| Long-form discuss | `discussions/` | `.md` |
| Report typo | GitHub Issue | — |
| Suggest edit | Pull Request | — |

---

<p align="center">
  <em>Halklar üstü, dil üstü, çağ üstü.</em><br/>
  <em>Beyond peoples, beyond languages, beyond ages.</em>
</p>
