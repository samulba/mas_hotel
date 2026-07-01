# [M]EAT &amp; STAY HOTEL · T-Bone Steakhouse — Website

Cleane, moderne Referenz-Website für das **MAS Hotel** (MEAT &amp; STAY) mit dem
**T-Bone Steakhouse** in Haar bei München. Sie dient als Design-Ziel für den
Relaunch der bestehenden Seite unter [mas-hotel.com](https://www.mas-hotel.com/).

## Idee

Der Markenname bringt das Konzept auf den Punkt: **[M]EAT &amp; STAY** —
verdeckt man das *M*, bleibt *EAT &amp; STAY*. Restaurant und Hotel unter einem
Dach, gedacht als ein Erlebnis. Die Seite spielt diesen Gedanken visuell aus:
warme, hochwertige „Steakhouse"-Ästhetik (Holzkohle-Schwarz, Cremeweiß,
Kupfer-Akzent), elegante Serifen-Headlines und ruhige, moderne Layouts.

## Seiten

| Datei | Inhalt |
|-------|--------|
| `index.html` | Startseite: Hero, Konzept, Steakhouse- &amp; Hotel-Teaser, Galerie, Location |
| `steakhouse.html` | T-Bone Steakhouse mit Speisekarte (Steaks, Vorspeisen, Beilagen, Wein) |
| `hotel.html` | Zimmer &amp; Suiten mit Preisen und Ausstattung |
| `kontakt.html` | Kontaktformular, Anfahrt/Karte, Impressum &amp; Datenschutz |

## Technik

Reines **HTML, CSS und Vanilla-JavaScript** — kein Build-Schritt, keine
Abhängigkeiten. Einfach `index.html` im Browser öffnen.

- Responsives Layout (Mobile-Menü, flexible Grids)
- Sticky-Navigation, Scroll-Reveal-Animationen, Laufband
- Google Fonts (*Fraunces* + *Inter*), Bilder via Unsplash
- Zugänglichkeit &amp; `prefers-reduced-motion` berücksichtigt

### Lokal ansehen

```bash
# Einfach die Datei öffnen …
open index.html

# … oder mit einem kleinen lokalen Server:
python3 -m http.server 8000   # dann http://localhost:8000
```

### Deployment (GitHub Pages)

Repository-Settings → *Pages* → Branch wählen, `/root` als Quelle. Die
`.nojekyll`-Datei stellt sicher, dass alle Assets ausgeliefert werden.

## Hinweise zu den Inhalten

Kontaktdaten, Öffnungszeiten und Adresse basieren auf öffentlich verfügbaren
Angaben. Preise und Speisekarte sind realistische **Platzhalter** und sollten
vor dem Livegang mit den echten Daten des Hauses abgeglichen werden. Bilder sind
Platzhalter von Unsplash und durch eigene Fotos des Hotels/Steakhouses zu
ersetzen.
