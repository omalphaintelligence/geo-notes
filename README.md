# Geography Notes

Live: https://omalphaintelligence.github.io/geo-notes/

## Naya notes add karna (2 steps)
1. HTML file repo ke root me upload karo (koi folder nahi), jaise `climatology.html`.
2. `notes.json` me entry add/update karo:

```json
{
  "subject": "Physical Geography",
  "title": "Climatology",
  "emoji": "🌦️",
  "file": "climatology.html",
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
Har notes file ke `<header>` ke andar ye line ho: `<a class="homebtn" href="./">← Saare notes</a>`

## Book tab
Book chapters `notes.json` me `"tab": "book"` ke saath jaate hain:
```json
{ "tab": "book", "subject": "Physical Geography", "chapter": 22, "title": "Glaciers & Glaciated Topography", "file": "ch22-glaciers.html" }
```
`subject` = book ka naam (Book tab me sub-tab ban jata hai), `chapter` se order set hota hai.

## Original PDF links
Har notes page me `PDFSRC` (PDF ka naam) aur `PMAP` (topic → page number) hota hai. PDF repo ke root me rakho; `pdf.html?f=<file>.pdf&p=<page>` us page ko kholta hai.
