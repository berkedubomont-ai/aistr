# Eylül–Ekim derlemesi: siteye aktarım dosyaları

Üç yazının doks-site (Hugo) yapısına uygun hâli. Klasörler, doks-site reposundaki yerleriyle aynı; dosyaları olduğu gibi kopyalamak yeterli:

| Dosya | doks-site'ta gideceği yer |
|---|---|
| `content/tr/blog/eylul-ekim-derlemesi-1-ajan-suruleri-ve-filolari.md` | `content/tr/blog/` |
| `content/tr/blog/eylul-ekim-derlemesi-2-iceriden-gelen-kaygilar-ve-siyaset.md` | aynı |
| `content/tr/blog/eylul-ekim-derlemesi-3-yeni-modeller-matematik-ve-siber-guvenlik.md` | aynı |
| `static/uploads/2026/11/eylul-ekim-derlemesi-*` | `static/uploads/2026/11/` |

## Ön bilgi alanları

Alanlar sitedeki yazılarla aynı (örnek: `openai-hugging-face-olayi.md`): `translationKey`, `title`, `date`, `slug`, `draft`, `description`, `author`, `editor`, `contributors`, `image`, `thumb_image`, `social_image`, `categories`.

- **Taslak:** Üç yazı da `draft: true`. Site `hugo` komutuyla taslakları derlemediği için bu hâlde yayına çıkmazlar. Yayına almak için `false` yapın.
- **Tarih:** Tarihler yer tutucu. Gelecek tarihli yazılar da derlenmiyor, bu yüzden gerçek yayın günüyle değiştirilmeli.
- **Editör:** Boş.

## Görseller

- Görseller sitedeki düzene göre `/uploads/2026/11/` altında. Küçük resimler (`-thumb`, 480/768/960) ve AVIF/JPG kopyaları sitenin kendi `scripts/generate-thumbnails.py` betiğiyle üretildi, yani Cloudflare derlemesi bu adımı atlasa da dosyalar hazır.
- #1 ve #2'nin şekilleri ve kapakları sitenin tasarım sistemine (DESIGN.md) göre yeniden çizildi: Bone/Card kâğıt zemin, keskin köşeler, gölgesiz; IBM Plex Sans ve büyük rakamlarda Rajdhani; veri için Seal Violet (#4F00E9), ikinci renk olarak Ink Soft ve Violet Soft. #2'nin kapağındaki halkalar sitenin halka motifiyle uyumlu.
- #3'ün kapağı ve şekilleri henüz eski renklerde (yeşil, yuvarlak köşeli kartlar).
- Kapak görselleri 1600×900.

## Metin

- Metin Sözlük'le uyumlu: yanlış uyum, süper zekâ, süper yapay zekâ, genel yapay zekâ.
- Sözlük'te olan terimlerin ilk geçtiği yer `/tr/sozluk/` adresine bağlı.
- Sözlük'te karşılığı olmayan terimler (sürü, filo, düşünce zinciri, istem enjeksiyonu, düzenleyici ele geçirme, Lean) düz metin. Sözlük'e eklenebilirler.
- Başlıklar yalnızca H2 ve H3. İçindekiler'i şablon zaten üretiyor, bu yüzden metne eklemedim.
- Yazılar arası bağlantılar `/tr/blog/<slug>/` biçiminde.
- #2'de Coxon'un ve Chughtai'nin sözleri birer alıntı bloğunda (`>`); aynı sözler paragraflarda ve 15 kişilik listede tekrar edilmiyor.
- #2'deki "Bizim görüşümüz" kutusu da alıntı bloğu olarak yazıldı, Bengüsu'nun yazısının bağlantısı içinde. Temada ayrı bir kutu (callout) stili varsa onunla değiştirilebilir.
- #2'de "Çalışanların yazdıkları" ve "Laboratuvarların raporları" başlıklı iki okuma listesi var.

## Şekiller

- Telefonda okunabilsin diye #1 ve #2'de yazı ağırlıklı şekiller Markdown'a çevrildi: olay tarihleri tablo, ajan grupları ve Tencent zaman çizelgesi liste. Görsellerde yalnızca grafik ve kısa etiketler var.
- Olay tablosu telefon genişliğinde (390 px) sitenin yazı tipiyle taşmadan sığıyor.
- #2'deki 16 adımlık siyaset şekli ve #3'ün şekilleri hâlâ uzun görseller; telefonda okunmaları zor, sonra ele alınacak.
- "Laboratuvarların içinden" bölümündeki 15 kişilik liste görsel değil, düz liste.
- Etkileşimli sürümler `berkedubomont-ai/aistr` reposunda duruyor.
