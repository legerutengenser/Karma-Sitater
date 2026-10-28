# Karma-Sitater
Sitater til bruk i Karma Kode, Karma Diagnose ++


## Slik fungerer det
- `quotes.json` er den eneste filen som redigeres. Format: en liste med `{"text": "...", "author": "..."}`.
- Alle linjer unntatt den siste må ende med komma. Bruk vanlige anførselstegn rundt tekst og forfatter. Tegnet `"` inne i et sitat skrives `\"`.
- Programmene (Karma Kode, Karma Diagnose) henter listen maks én gang per døgn. Er filen ugyldig eller utilgjengelig, bruker de sin innebygde reservekopi.
- Sortert alfabetisk etter forfatter, deretter sitattekst.
