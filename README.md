# Studio Bella - Salgspitch Hjemmeside

En moderne, responsiv landingsside for frisørsalong Studio Bella, designet for konvertering og booking.

## Features

✨ **Moderne design**
- Eksklusive pink/lavender fargeplett
- Responsiv layout (mobil, tablet, desktop)
- Smooth animasjoner og hover-effekter

🎨 **Innhold**
- Hero-seksjon med CTA
- Tjenestekort (4 tjenester)
- Galleri med 6 bilder
- Om oss-seksjon
- Kundeanmeldelser
- Booking-CTA
- Footer med kontaktinfo

📱 **Teknologi**
- HTML5 + Tailwind CSS (CDN)
- Responsiv design (mobile-first)
- Google Fonts (Playfair Display + Inter)
- Ingen build-prosess

## Filstruktur

```
├── preview/
│   └── frisør-landing.html      # Hovedside
├── Images/
│   ├── kort-frisyre.png
│   ├── bolgande-lokkar.png
│   ├── modern-cut.png
│   ├── highlights.png
│   ├── brudeoppsett.png
│   ├── farging.png
│   └── om-oss.png
├── CLAUDE.md
└── README.md
```

## Lokal utvikling

Åpne `preview/frisør-landing.html` direkte i nettleseren – ingen build-steg nødvendig.

## Deploy på Vercel

### 1. Koble til Vercel
Besøk [vercel.com](https://vercel.com) og logg inn med GitHub.

### 2. Import prosjekt
- Klikk "Add New..." → "Project"
- Velg `Salgspitch-hjemmeside` repository
- Klikk "Import"

### 3. Konfigurer Vercel

Siden dette er en ren HTML-side:

| Setting | Verdi |
|---------|-------|
| **Framework** | Other (eller blank) |
| **Root Directory** | `./` |
| **Build Command** | (blank) |
| **Output Directory** | `./` |

### 4. Deploy
Klikk "Deploy" – siden deployes automatisk!

Vercel gir deg en URL som: `https://salgspitch-hjemmeside.vercel.app`

## Auto-deploy fra GitHub

Hver gang du pusher til `master`, deployer Vercel automatisk:

```bash
git add .
git commit -m "Dine endringer"
git push origin master
```

## Rediger siden

1. Åpne `preview/frisør-landing.html`
2. Gjør endringer
3. Pushé til GitHub
4. Vercel deployer automatisk

---

Laget med ❤️ for skjønnhet og selvtillit
