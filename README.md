# Geography Notes

Live: https://omalphaintelligence.github.io/geo-notes/

## Naya notes add karna (2 steps)
1. HTML file `notes/` folder me upload karo, jaise `notes/climatology.html`.
2. `notes.json` me entry add/update karo:

```json
{
  "subject": "Physical Geography",
  "title": "Climatology",
  "emoji": "🌦️",
  "file": "notes/climatology.html",
  "desc": "Short description",
  "topics": ["monsoon", "jet stream"],
  "mcq": 100,
  "flashcards": 30,
  "source": "Neetu Singh Vol-2"
}
```
- `file: null` → card "Jald aa raha" dikhega.
- Entries ke beech comma zaroor lagao, last entry ke baad nahi.
- Naya `subject` likhoge to naya colour + filter chip apne aap ban jayega.

## Notes page me "← Saare notes" button
Har notes file ke `<header>` ke andar ye line ho: `<a class="homebtn" href="../">← Saare notes</a>`
