# Dutch Golden Age Highlights

Reference catalog for the Dutch Golden Age highlights section of the demo app.

All titles, inventory numbers, dates, and collection record identifiers below are taken **exactly as returned by the Rijksmuseum's own collection records** (Rijksmuseum Data Services / Linked Art). No third-party sources were used.

---

## Featured artworks

### 1. The Night Watch — SK-C-5

- **Title (as listed by the museum):** Het korporaalschap van kapitein Frans Banninck Cocq en luitenant Willem van Ruytenburch, bekend als de 'Nachtwacht'
- **Inventory number:** SK-C-5
- **Date:** 1642-01-01T00:00:00Z (cataloged by the museum as 1642)
- **Collection record ID:** https://id.rijksmuseum.nl/200107928

The museum's own object record for the company piece of Captain Frans Banninck Cocq and Lieutenant Willem van Ruytenburch, universally known as *The Night Watch*. This is the anchor highlight of the section.

### 2. Rembrandt — earliest-dated work in the collection sample — SK-A-4674

- **Title (as listed by the museum):** Allegorisch musicerend gezelschap
- **Inventory number:** SK-A-4674
- **Date:** 1626-01-01T00:00:00Z (cataloged by the museum as 1626)
- **Collection record ID:** https://id.rijksmuseum.nl/200107935

The earliest-dated work in the chronological sample of Rembrandt's works held in the Rijksmuseum collection.

### 3. Rembrandt — latest-dated work in the collection sample — SK-C-216

- **Title (as listed by the museum):** Portrait of a couple as figures from the Old Testament, known as 'The Jewish bride'
- **Inventory number:** SK-C-216
- **Date:** 1665-01-01T00:00:00Z (cataloged by the museum as 1665)
- **Collection record ID:** https://id.rijksmuseum.nl/200107934

The latest-dated work in the chronological sample of Rembrandt's works held in the Rijksmuseum collection.

### 4. Vermeer, The Milkmaid — SK-A-2344

- **Title (as listed by the museum):** De keukenmeid
- **Inventory number:** SK-A-2344
- **Date:** 1660-01-01T00:00:00Z (cataloged by the museum as 1660)
- **Collection record ID:** https://id.rijksmuseum.nl/200108369

The museum lists Vermeer's *The Milkmaid* under its Dutch title, *De keukenmeid*.

---

## Data source

- Rijksmuseum collection records, retrieved directly from the Rijksmuseum Data Services (Search API + Linked Art).
- The chronological Rembrandt sample (used to select items 2 and 3) was returned by the museum's own timeline of Rembrandt van Rijn's works in the collection, covering 1626–1665.

## Scope

- This change ships the catalog as two files only: `highlights.md` (this write-up) and `artworks.json` (machine-readable data, one entry per artwork keyed by inventory number).
- Hero images and integration into the demo page are deliberately out of scope and tracked separately in the issue tracker.
