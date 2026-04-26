# Trzy pokoje (Płonę / Latarnia / Pomiędzy)

Jedna obecność, trzy stany. Dostępne w 5 językach: 🇵🇱 PL · 🇺🇸 EN · 🇪🇸 ES · 🇳🇱 NL · 🇺🇦 UK.

- **Latarnia** — wejście. Jedno zdanie, oddech. → `/`
- **Płonę** — gdy w środku za gorąco. Słowo w odpowiedź. → `/plone/`
- **Pomiędzy** — list do siebie; plik `.pomiedzy-YYYY-MM-DD.html` (kropka na początku nazwy). → `/pomiedzy/`
- Stary URL `/latarnia/` przekierowuje na `/` (z zachowaniem `?lang=`).

Live: [https://thelanterndev.github.io/plone/](https://thelanterndev.github.io/plone/)

## Języki / Languages

Aktywny język ustawiasz przyciskiem w prawym górnym rogu (`pl · en · es · nl · uk`). Wybór trzyma się w `localStorage`, można też wymusić przez URL: `?lang=en`, `?lang=es`, `?lang=nl`, `?lang=uk`. Polski jest językiem podstawowym i fallbackiem.

Pieczętowany list w *Pomiędzy* zapamiętuje język w pliku — przy otwarciu sealed-file UI zawsze pokazuje się w tym samym języku, w którym list był pisany.

## Lokalnie

```bash
python3 -m http.server 8000
```

Otwórz `http://localhost:8000/`.

---

## EN — Three rooms (Płonę / Lighthouse / Between)

One presence, three states. Available in 5 languages.

- **Lighthouse** — the entry. One sentence, a breath. → `/`
- **Płonę** — when it's too hot inside. A word in answer. → `/plone/`
- **Between** — a letter to your future self; a file `.pomiedzy-YYYY-MM-DD.html` (dot prefix). → `/pomiedzy/`

Switch the active language with the pill bar in the top-right corner (`pl · en · es · nl · uk`). Your choice is kept in `localStorage`, or you can force it via `?lang=en`, `?lang=es`, `?lang=nl`, `?lang=uk`. Polish is the primary fallback. A sealed *Between* letter remembers its language inside the file.

## ES — Tres cuartos

Una presencia, tres estados. Disponible en 5 idiomas. Cambia el idioma con la barra de la esquina superior derecha o forzando `?lang=es`. El polaco es el idioma de respaldo principal.

## NL — Drie kamers

Eén aanwezigheid, drie toestanden. Beschikbaar in 5 talen. Wissel van taal met de balk rechtsboven of via `?lang=nl`. Pools is de primaire fallback.

## UK — Три кімнати

Одна присутність, три стани. Доступно 5 мовами. Зміни мову у правому верхньому кутку або через `?lang=uk`. Польська — основна резервна мова.
