# Eylül–Ekim derlemesi: siteye aktarım dosyaları

Üç yazının doks-site (Hugo) yapısına uygun hâli. Klasörler, repodaki yerleriyle aynı:

| Dosya | Repoda gideceği yer |
|---|---|
| `content/tr/blog/eylul-ekim-derlemesi-1-ajan-suruleri-ve-filolari.md` | Blog (TR) koleksiyonunun klasörü |
| `content/tr/blog/eylul-ekim-derlemesi-2-iceriden-gelen-kaygilar-ve-siyaset.md` | aynı |
| `content/tr/blog/eylul-ekim-derlemesi-3-yeni-modeller-matematik-ve-siber-guvenlik.md` | aynı |
| `static/cms-uploads/2026/11/eylul-ekim-derlemesi/*.webp` | `static/cms-uploads/` altına |

Repoyu göremediğim için iki şeyi senin kontrol etmen gerekiyor: blog yazılarının klasörü (`content/tr/blog/` mi, başka bir yer mi) ve ön bilgi (front matter) alan adları.

## Ön bilgi alanları

Her dosyanın başında CMS'teki alanlar var: `title`, `date`, `draft`, `slug`, `description`, `translationKey`, `image`. Yazar ve editör için `authors` ve `editor` yazdım; sitedeki yazılarda bu alanların adı farklıysa değiştirmek yeterli.

- **Taslak:** Üç yazı da `draft: true`. Yayına almak için bu satırı `false` yapın.
- **Tarih:** Tarihler yer tutucu. Gerçek yayın günüyle değiştirilecek.
- **Editör:** Boş.

## Metin

- Metin Sözlük'le uyumlu: yanlış uyum, süper zekâ, süper yapay zekâ, genel yapay zekâ.
- Sözlük'te olan terimlerin ilk geçtiği yer `/tr/sozluk/` adresine bağlı.
- Sözlük'te karşılığı olmayan terimler (sürü, filo, düşünce zinciri, istem enjeksiyonu, düzenleyici ele geçirme, Lean) düz metin. Sözlük'e eklenebilirler.
- Başlıklar yalnızca H2 ve H3. İçindekiler'i şablon zaten üretiyor, bu yüzden metne eklemedim.
- Yazılar arası bağlantılar `/tr/blog/<slug>/` biçiminde.

## Şekiller

- Etkileşimli şekiller, kaynak satırları şeklin altına bağlantı olarak yazılmış görsellere dönüştürüldü.
- "Laboratuvarların içinden" bölümündeki 15 kişilik liste görsel değil, düz liste.
- Etkileşimli sürümler `berkedubomont-ai/aistr` reposunda duruyor. Yazıların içine HTML konabiliyorsa onlar da eklenebilir.
- Kapak görselleri 1600×900.
