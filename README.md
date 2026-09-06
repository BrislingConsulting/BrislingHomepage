# BrislingHomepage

Placeholder "coming soon"-side for **brisling.no**, satt opp som statisk side for GitHub Pages
(ingen build-steg — bare `index.html`).

## Bakgrunn (kontekst hentet fra kunnskapsgrafen, 2026-09-06)

- Selskapsnavnet **Brisling Consulting AS** ble besluttet 5. september 2026. Det erstatter
  arbeidsnavnet **Kopter** som er brukt i tidligere strategidokumenter, agenda og referat fra
  fellesmøtet 27. august 2026 — alle referanser til «Kopter»/«Kopter AS» før den datoen skal leses
  som Brisling Consulting AS.
- Domenet **brisling.no** ble anskaffet 6. september 2026. `brisling-consulting.no` ble vurdert
  som alternativ, men er ikke i bruk.
- GitHub-organisasjonen **[BrislingConsulting](https://github.com/BrislingConsulting/)** ble
  opprettet samme dag. All produktutvikling i selskapet skal i første omgang skje her — dette er
  første konkrete tekniske infrastruktur under det nye navnet.
- Selskapet har også en pågående fusjonsprosess med Moedata AS ("Moedata-Brisling Fusion").

### Åpne punkter (ikke løst av denne siden)

- E-postoppsett på brisling.no (Google Workspace vs. Microsoft 365) — ikke avklart.
- Tilgangsstyring i GitHub-organisasjonen (hvem av grunnleggerne er eiere/medlemmer) — ikke
  dokumentert.

Full historikk og flere detaljer finnes i kunnskapsgrafen under `raw/` i
`AI Bibliotek/business` (Google Drive) — søk der (`graphify query "Brisling"`) hvis noe her
virker ufullstendig eller utdatert.

## Deploy (GitHub Pages)

1. Push til `main`.
2. I repo-innstillinger → **Pages**: sett source til branch `main`, mappe `/ (root)`.
3. `CNAME`-filen peker allerede til `brisling.no`. Sett opp DNS hos domeneregistrar:
   - `A`-poster for apex-domenet mot GitHub Pages' IP-er (185.199.108.153, .109.153, .110.153,
     .111.153), eller
   - `ALIAS`/`ANAME` mot `brislingconsulting.github.io` hvis registraren støtter det.
4. Skru på "Enforce HTTPS" i Pages-innstillingene når DNS har propagert.
