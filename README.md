# Seçim Asistanı — topluluk kural bankası

[Seçim Asistanı](https://chromewebstore.google.com/detail/ehkooeplfignodnkfleonhgnkhoalpma) Chrome uzantısının, kullanıcıların öğrettiği mağaza **okuma kuralları**.

Bir kullanıcı tanınmayan bir alışveriş sitesinde "Bu siteyi öğren" dediğinde, Chrome'un cihaz içi yapay zekâsı sitenin hangi öğesinin ürün kartı, ürün adı ve fiyat olduğunu bulur. Kullanıcı isterse bu kural buraya önerilir. Onaylanan kurallar `kurallar.json` dosyasına eklenir ve her kullanıcının uzantısı günde bir kez bu dosyayı okur. Böylece her kullanıcı, fiyatını karşılaştırabildiğimiz siteleri herkes için çoğaltır.

## Ne paylaşılır, ne paylaşılmaz
- **Paylaşılır:** yalnız sitenin alan adı ve sayfa seçicileri (CSS seçici / yazı kalıbı), isteğe bağlı arama adresi şablonu.
- **Paylaşılmaz:** kişisel veri, gezinme geçmişi, aranan ürünler, fiyatlar, hesap bilgisi. Çalıştırılabilir kod kabul edilmez.
- Uzantı her kuralı yüklerken yeniden denetler (bilinen alanlar, kısa yazılar, tehlikeli içerik yok); paketteki ve kullanıcının kendi öğrendiği kural her zaman önceliklidir.

## Kural önermek
Uzantıda bir siteyi öğrettikten sonra çıkan "Bu kuralı herkesle paylaş" bağlantısı, kuralı hazır yazılmış bir öneri (issue) olarak açar. Göndermek senin elindedir.

---

# Selection Assistant — community rule bank

Store **reading rules** taught by users of the Selection Assistant Chrome extension: only the site's domain and page selectors (which element is the product card, name, price). No personal data, no executable code. The extension re-validates every rule before use.

**What is shared:** only the domain and page selectors (CSS selector / text pattern), optionally a search URL template. **Never shared:** personal data, browsing history, searches, prices, account data. Executable code is rejected. **To propose a rule:** after teaching a site in the extension, the "Share this rule with everyone" link opens a pre-filled issue — sending it is up to you.

---

# Assistant de choix — banque de règles communautaire (Français)

Règles de **lecture** des boutiques enseignées par les utilisateurs de l'extension Chrome « Assistant de choix » : uniquement le domaine et les sélecteurs de page (quel élément est la fiche produit, le nom, le prix). Aucune donnée personnelle, aucun code exécutable. L'extension revérifie chaque règle avant usage. Pour proposer une règle : après avoir appris un site, le lien « Partager cette règle » ouvre une proposition pré-remplie ; c'est vous qui l'envoyez.

# Auswahl-Assistent — Community-Regelbank (Deutsch)

Von Nutzern der Chrome-Erweiterung „Auswahl-Assistent" beigebrachte **Leseregeln** für Shops: nur die Domain und Seitenselektoren (welches Element Produktkarte, Name, Preis ist). Keine personenbezogenen Daten, kein ausführbarer Code. Die Erweiterung prüft jede Regel vor der Nutzung erneut. Regel vorschlagen: Nach dem Anlernen einer Seite öffnet der Link „Diese Regel teilen" einen vorausgefüllten Vorschlag – das Absenden liegt bei Ihnen.

# Помощник выбора — общий банк правил (Русский)

**Правила чтения** магазинов, которым пользователи научили расширение Chrome «Помощник выбора»: только домен и селекторы страницы (какой элемент — карточка товара, название, цена). Никаких личных данных и исполняемого кода. Расширение заново проверяет каждое правило перед использованием. Предложить правило: после обучения сайта ссылка «Поделиться правилом» открывает готовое предложение — отправляете его вы.

# Asistente de elección — banco de reglas de la comunidad (Español)

**Reglas de lectura** de tiendas enseñadas por los usuarios de la extensión de Chrome «Asistente de elección»: solo el dominio y los selectores de página (qué elemento es la ficha del producto, el nombre, el precio). Sin datos personales ni código ejecutable. La extensión vuelve a comprobar cada regla antes de usarla. Para proponer una regla: tras enseñar un sitio, el enlace «Compartir esta regla» abre una propuesta ya rellenada; enviarla depende de ti.

# चयन सहायक — सामुदायिक नियम बैंक (हिन्दी)

"चयन सहायक" Chrome एक्सटेंशन के उपयोगकर्ताओं द्वारा सिखाए गए दुकानों के **पढ़ने के नियम**: केवल डोमेन और पेज सेलेक्टर (कौन-सा तत्व उत्पाद कार्ड, नाम, कीमत है)। कोई व्यक्तिगत डेटा नहीं, कोई चलने वाला कोड नहीं। एक्सटेंशन हर नियम को उपयोग से पहले फिर से जाँचता है। नियम सुझाने के लिए: किसी साइट को सिखाने के बाद "यह नियम सबके साथ साझा करें" लिंक पहले से भरा सुझाव खोलता है — भेजना आपके हाथ में है।
