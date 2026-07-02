# [M]EAT &amp; STAY HOTEL · T-Bone Steakhouse — Website

Moderne Website für das **MAS Hotel** ([M]EAT &amp; STAY) mit dem **T-Bone
Steakhouse** in Haar bei München. **Struktur und Inhalte orientieren sich an der
bestehenden Seite** [mas-hotel.com](https://www.mas-hotel.com/) (Zimmer,
Steakhouse, Tagungen, Grillseminare, Kontakt), das **Design ist komplett neu**.

## Look & Idee

Der Markenname bringt das Konzept auf den Punkt: **[M]EAT &amp; STAY** — verdeckt
man das *M*, bleibt *EAT &amp; STAY*. Hotel, Restaurant, Tagungen und
Grillseminare als ein Erlebnis unter einem Dach.

Design-Richtung: **warm &amp; handwerklich** — Creme-/Sandtöne, Espresso-Braun,
Rostrot-Akzent, dezente Papier-Textur, Stempel-/Handschrift-Elemente. Serifen-
Headlines (*Fraunces*), klare Sans (*Inter*), handschriftliche Akzente (*Caveat*).

## Seiten

| Datei | Inhalt |
|-------|--------|
| `index.html` | Startseite: Hero, Konzept, Angebots-Teaser, Steakhouse- &amp; Zimmer-Highlights, Galerie, Lage |
| `zimmer.html` | 37 Zimmer, Ausstattung, Frühstück &amp; Service |
| `steakhouse.html` | T-Bone Steakhouse: Dry-Aged-Konzept &amp; Speisekarte |
| `tagungen.html` | Tagungen &amp; Events: Räume, Bestuhlung, Ausstattung |
| `grillseminare.html` | Grillseminare mit Fleisch-Sommelier, Ablauf |
| `kontakt.html` | Anfrageformular, Anfahrt/Karte, Impressum · AGB · Datenschutz |

## Technik

Reines **HTML, CSS und Vanilla-JavaScript** — kein Build-Schritt, keine
Abhängigkeiten. Einfach `index.html` im Browser öffnen.

- Responsives Layout (Mobile-Menü, flexible Grids)
- Sticky-Navigation, Scroll-Reveal-Animationen, Laufband
- Google Fonts (*Fraunces*, *Inter*, *Caveat*), Bilder via Unsplash
- Zugänglichkeit &amp; `prefers-reduced-motion` berücksichtigt

### Lokal ansehen

```bash
open index.html
# oder mit lokalem Server:
python3 -m http.server 8000   # dann http://localhost:8000
```

### Deployment (GitHub Pages)

Repository-Settings → *Pages* → Source „Deploy from a branch" → Branch **`main`**,
Ordner **`/ (root)`**. Die `.nojekyll`-Datei stellt sicher, dass alle Assets
ausgeliefert werden. Jeder Push auf `main` aktualisiert die Live-Seite automatisch.

## Hinweise zu den Inhalten

Adresse, Kontaktdaten, Öffnungszeiten und Fakten (37 Zimmer, Dry-Aged 28 Tage,
6 Tagungsräume, Grillseminare) basieren auf öffentlich verfügbaren Angaben.
**Preise, Speisekarte und Bilder sind realistische Platzhalter** (Fotos via
Unsplash) und sollten vor dem Livegang durch die echten Daten und eigene Fotos
des Hauses ersetzt werden.
