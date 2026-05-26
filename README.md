# Visit Dønna — turistportal

Enkel, rask turistside for Dønna på Helgelandskysten.

## Filer
- `index.html` — hele siden (design, tekst og animasjoner bakt inn)
- `donnamannen.png` — hero-bildet av Dønnamannen

VIKTIG: begge filene må ligge i SAMME mappe i repoet, ellers vises ikke bildet.

## Legg ut på GitHub Pages
1. Last opp begge filene i repoet.
2. Settings -> Pages -> Source: "Deploy from a branch", branch `main`, mappe `/ (root)`.
3. Hard-refresh med Cmd+Shift+R etter et par minutter.

## Endre innhold
Alt ligger i index.html. Søk etter teksten du vil bytte:
- Drosjenummer: søk `465 55 516`
- E-post: søk `hei@visitdonna.no` (står to steder)
- SUP-pris: søk `Ta kontakt for pris`
- Farger: helt øverst i <style> under :root

## Bytte hero-bildet
Legg et nytt bilde i mappa og kall det `donnamannen.png` (eller endre filnavnet
i index.html der det står `donnamannen.png`). Liggende format (bredt) funker best.

## Neste steg å vurdere
- Ekte bilder til severdighets-kortene (kirka, Dønnesfjellet).
- Lenker til offisielle ferjeruter (Torghatten Nord / Reis Nordland) som oppdateres.
- Bookingløsning for SUP når forespørslene kommer (start med e-post/skjema).
- Sjekk og oppdater åpningstider/priser jevnlig — turister mister tillit til utdatert info.

## Ansvar (SUP-utleie)
Før første utleie: tegn forsikring, lag en enkel leieavtale med ansvarsfraskrivelse,
og gi en sikkerhetsinstruks (vest, sjekk vær/vind, ikke padle ut i fralandsvind).


## Oppdatering

Denne pakken inneholder nå 10 artikkelsider i mappen `artikler/`, samt `CNAME` for donnamannen.no. Forsidens eksisterende stil er beholdt; artiklene gjenbruker samme uttrykk.

Artiklene er førsteutkast og bør faktasjekkes mot oppdaterte kilder før publisering, særlig fergeruter, åpningstider og praktisk besøksinformasjon.
