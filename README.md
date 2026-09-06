# BrislingHomepage

Hjemmesiden til Brisling Consulting AS, hostet på [brisling.no](https://brisling.no) via GitHub Pages.

Statisk side — `index.html` er hele nettsiden, ingen build-steg.

## Deploy

1. Push til `main`.
2. I repo-innstillinger → **Pages**: sett source til branch `main`, mappe `/ (root)`.
3. `CNAME`-filen peker til `brisling.no`. DNS må peke dit (A-poster mot GitHub Pages, eller
   ALIAS/ANAME mot `brislingconsulting.github.io`).
4. Skru på "Enforce HTTPS" i Pages-innstillingene når DNS har propagert.
