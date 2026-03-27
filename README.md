# Hard Launch — Landing Page Concepts

Art direction explorations for Maven's Hard Launch "Learn from Humans" digital experience.

## Concepts

| Concept | Direction | Path |
|---------|-----------|------|
| **Digital Nostalgia** | ASCII portraits + CRT scan lines + blue phosphor glow | `/ascii-crt` |
| **Halftone Blue** | Blue monochrome dots on cream + blueprint grid + hatching transitions | `/halftone-blue` |
| **CMYK Halftone** | Four-color separation dots + channel misregistration transitions | `/halftone-cmyk` |

## Shared Elements

All concepts share the same page structure:
- Full viewport, no scroll
- "Learn {Topic} from humans" hero with rotating categories
- Email capture card
- Auto-cycling instructor portraits (10 instructors, 5s each)
- Maven branding (Source Serif 4 + Inter, Lapis color palette)

## Running Locally

No build step needed. Just serve the files:

```bash
npx serve .
```

Or open any `index.html` directly in a browser (images need a local server for Canvas processing).

## Images

Instructor headshots in `/images/` sourced from the experts-report repository.
