# LumosCare – Osteopathie mit Herz

Eine soziale Initiative der **Lumos Vitalis eG** aus Hamburg.

![LumosCare Logo](assets/logos/lumoscare-logo.svg)

## 📖 Über LumosCare

LumosCare bringt osteopathische Versorgung zu Menschen, die sie am meisten brauchen – kostenfrei, professionell und mit Herz.

Wir ermöglichen Kindern, Senioren und schwerkranken Menschen Zugang zu ganzheitlicher osteopathischer Behandlung in:
- Kinder- und Jugendhilfeeinrichtungen
- Seniorenheimen und Pflegeeinrichtungen
- Hospizen und Palliativstationen
- Ausgewählten Krankenhausabteilungen

## 🌟 Unsere Werte

- **Mitgefühl** – Empathie und Würde für jeden Menschen
- **Professionalität** – Qualifizierte Behandlung auf höchstem Niveau
- **Gemeinschaft** – Zusammen bewirken wir mehr
- **Nachhaltigkeit** – Langfristige Wirkung statt kurzfristige Lösungen
- **Zugänglichkeit** – Barrierefrei in jeder Hinsicht

## 🎨 Corporate Identity

Diese Website folgt dem **Corporate Identity Manual** der LumosCare:

### Farbpalette
- **Lumos-Blau**: `#2B5F8C` – Vertrauen, Ruhe, Professionalität
- **Care-Warmgelb**: `#F4B860` – Wärme, Hoffnung, Licht
- **Sanftes Grau**: `#E8EBF0` – Hintergründe
- **Tiefgrau**: `#3A4A5C` – Texte
- **Herzrot**: `#D97168` – Emotionale Akzente (sparsam)

### Typografie
- **Primär**: Poppins (Headlines, Logo)
- **Sekundär**: Open Sans (Fließtext)

## 📁 Projektstruktur

```
lumoscare/
├── index.html              # Hauptseite / Landingpage
├── css/
│   ├── main.css           # Haupt-Stylesheet (importiert alle anderen)
│   ├── variables.css      # CSS-Variablen (Farben, Schriften, etc.)
│   ├── base.css           # Reset & Basis-Styles
│   ├── layout.css         # Header, Footer, Navigation
│   ├── components.css     # Wiederverwendbare Komponenten
│   └── pages.css          # Seiten-spezifische Styles
├── js/
│   └── main.js            # JavaScript (Navigation, Animationen)
├── pages/
│   ├── einrichtungen.html # Informationen für Einrichtungen
│   ├── osteopathen.html   # Informationen für Osteopath:innen
│   ├── impressum.html     # Impressum
│   ├── datenschutz.html   # Datenschutzerklärung (TODO)
│   └── satzung.html       # Satzung (TODO)
├── assets/
│   ├── logos/             # Logo-Dateien (SVG)
│   ├── icons/             # Icon-Dateien
│   └── images/            # Bilder und Fotos
├── components/            # Wiederverwendbare HTML-Komponenten (optional)
├── .gitignore
└── README.md
```

## 🚀 Lokale Entwicklung

### Voraussetzungen
- Ein moderner Webbrowser
- Optional: Ein lokaler Webserver (z.B. Live Server für VS Code)

### Installation

1. Repository klonen:
```bash
git clone https://github.com/LumosVitalis/lumoscare.git
cd lumoscare
```

2. Die Website lokal öffnen:
   - Öffne `index.html` direkt im Browser, oder
   - Verwende einen lokalen Webserver (empfohlen):
     ```bash
     # Mit Python 3
     python -m http.server 8000

     # Mit Node.js (http-server)
     npx http-server
     ```

3. Website im Browser öffnen: `http://localhost:8000`

## 🌐 Deployment

### GitHub Pages

Die Website wird automatisch über GitHub Pages bereitgestellt.

1. In den Repository-Einstellungen → Pages
2. Source: `main` Branch
3. Folder: `/ (root)`

Die Website ist dann verfügbar unter:
```
https://lumosvitalis.github.io/lumoscare/
```

### Eigene Domain verbinden

1. CNAME-Datei im Root erstellen mit deiner Domain
2. DNS-Einstellungen beim Domain-Provider anpassen:
   - A-Record auf GitHub Pages IPs
   - Oder CNAME-Record auf `lumosvitalis.github.io`

## 📝 To-Do

- [ ] Datenschutzerklärung erstellen (`pages/datenschutz.html`)
- [ ] Satzung hochladen (`pages/satzung.html`)
- [ ] Professionelle Fotos einfügen
- [ ] Kontaktformular mit Backend verbinden
- [ ] SEO optimieren (Meta-Tags, Open Graph)
- [ ] Analytics einbinden (datenschutzkonform)
- [ ] Cookie-Banner implementieren (falls nötig)
- [ ] Barrierefreiheit testen (WCAG 2.1)

## 🛠️ Technologien

- **HTML5** – Semantisches Markup
- **CSS3** – Modernes, responsives Design
- **Vanilla JavaScript** – Keine Frameworks für maximale Performance
- **SVG** – Skalierbare Vektorgrafiken für Logo und Icons

## 📱 Browser-Unterstützung

- Chrome (neueste 2 Versionen)
- Firefox (neueste 2 Versionen)
- Safari (neueste 2 Versionen)
- Edge (neueste 2 Versionen)
- Mobile Browser (iOS Safari, Chrome Android)

## 📞 Kontakt

**Lumos Vitalis eG**
Projektleitung LumosCare
Christian Selzle & Joshua Alsen

📧 vorstand@lumosvitalis.de
🌐 www.lumosvitalis.de/lumoscare
📍 Mindelweg 6A, 22393 Hamburg

**Start der Pilotphase:** Frühjahr 2026 in Hamburg

## 📄 Lizenz

© 2025 Lumos Vitalis eG
Register: GnR 1159, Amtsgericht Hamburg

Alle Rechte vorbehalten. Die Inhalte dieser Website dürfen nicht ohne schriftliche Genehmigung reproduziert werden.

---

**Eine gemeinnützige Initiative für Menschen, die Berührung brauchen.**
