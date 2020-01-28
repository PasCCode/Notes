# Tipps & Tricks für die Search Console

## Ranking

- *Structured Data* do not influence ranking
- **superfluous keywords** (overloading the website with keywords oder numbers) can lead to a worse ranking
- on multilingual sites you can use the same file/filename for media on the different language sites

## Sitemap

- *Canonical URLs*
- date of last change
- immediate notification on change (new/updated pages)
- small sites (1-10k pages) do not really need a sitemap
- although RSS/Atom feeds can include body of text, Google Algorithm ignores this

## Indexing

- Content which is visible only after unfolding hidden stuff, will not be indexed
- even for desktop-only websites GoogleBot will index them as long as user can see all content on their mobile device (zoom in)
    &rarr; Google might rank the website lower for users on mobile devices due to it not being mobile friendly
- it is normal for the Search Console to show a higher number of desktop pages compared to mobile-only pages
    - it is only important that the percentage of errors flagged is about the same

## Crawling

- Seiten mit "unendlichen" Ergebnissen (unendliche Kalender oder Suchergebnisse) sollten mit der `robots.txt` oder einem `nofollow` Tag vom Crawling ausgeschlossen werden

- verschiedene Datei-Typen können unterschiedliche Cache-Richtlinien haben

- Google crawlt Webseiten mindestens einmal pro sechs Monate
