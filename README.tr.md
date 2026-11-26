[English](README.md) · **Türkçe** · [Français](README.fr.md) · [Deutsch](README.de.md) · [Русский](README.ru.md) · [Español](README.es.md) · [हिन्दी](README.hi.md)

# Seçim Asistanı — topluluk kural bankası

[Seçim Asistanı](https://chromewebstore.google.com/detail/ehkooeplfignodnkfleonhgnkhoalpma) Chrome uzantısının, kullanıcıların öğrettiği mağaza **okuma kuralları**.

Bir kullanıcı tanınmayan bir alışveriş sitesinde "Bu siteyi öğren" dediğinde, Chrome'un cihaz içi yapay zekâsı sitenin hangi öğesinin ürün kartı, ürün adı ve fiyat olduğunu bulur. Kullanıcı isterse bu kural buraya önerilir. Onaylanan kurallar `kurallar.json` dosyasına eklenir ve her kullanıcının uzantısı günde bir kez bu dosyayı okur. Böylece her kullanıcı, fiyatını karşılaştırabildiğimiz siteleri herkes için çoğaltır.

## Ne paylaşılır, ne paylaşılmaz
- **Paylaşılır:** yalnız sitenin alan adı ve sayfa seçicileri (CSS seçici / yazı kalıbı), isteğe bağlı arama adresi şablonu.
- **Paylaşılmaz:** kişisel veri, gezinme geçmişi, aranan ürünler, fiyatlar, hesap bilgisi. Çalıştırılabilir kod kabul edilmez.
- Uzantı her kuralı yüklerken yeniden denetler (bilinen alanlar, kısa yazılar, tehlikeli içerik yok); paketteki ve kullanıcının kendi öğrendiği kural her zaman önceliklidir.

## Kural önermek
Uzantıda bir siteyi öğrettikten sonra çıkan "Bu kuralı herkesle paylaş" bağlantısı, kuralı hazır yazılmış bir öneri (issue) olarak açar. Göndermek senin elindedir.
