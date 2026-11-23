# Materyal Denetçisi

Aileye gönderilecek terapi materyallerinde uygunsuz kelimeleri ve yazım hatalarını işaretleyen, tarayıcıda çalışan araç. PDF, Word ve metin okur.

- Sayfa: `site/` (Hece tasarım dili, kaynak: mihenk deposu `tasarim/hece`).
- Uygunsuz kelime listesi sayfada yalnızca hash olarak durur. Düz liste ve hash üreten betik bu depoya girmez.
- Sözlük: TDK Güncel Türkçe Sözlük kelime listesi (hash'li).

## Kaynaklar

Uygunsuz kelime listesi kısmen şu listelerden türetilmiştir: [ooguz/turkce-kufur-karaliste](https://github.com/ooguz/turkce-kufur-karaliste) (CC BY-SA 4.0), [egemenzeytinci/kufur-blok](https://github.com/egemenzeytinci/kufur-blok), [LDNOOBW](https://github.com/LDNOOBW/List-of-Dirty-Naughty-Obscene-and-Otherwise-Bad-Words) (CC BY 4.0). Bu yüzden `site/argo.json` CC BY-SA 4.0 koşullarıyla paylaşılır.
