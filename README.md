# Operation BREAKWATER

Individuele, asynchrone OSINT CTF voor vakontwikkeling.

## Voor deelnemers
1. Open de GitHub Pages-site.
2. Werk zelfstandig en op eigen tempo.
3. Open per challenge het bronbestand.
4. Lever flags exact aan als `CTF{...}`.
5. Hints kosten 10 punten per hint.
6. Noteer je onderzoeksstappen als `observable → pivot → corroboration → flag`.
7. Gebruik geen echte personen of systemen buiten de synthetische trainingsomgeving als target.

Voortgang, analyst logs en scores worden alleen via `localStorage` in de eigen browser bewaard.

## Resultaat doorgeven
Vul bovenaan een alias of naam in. Gebruik na afloop **Exporteer resultaat (JSON)** of **Exporteer resultaat (CSV)**. Het bestand bevat totaalscore, opgeloste challenges, gebruikte hints, analyst logs en de capability matrix. Stuur het resultaatbestand rechtstreeks naar de organisator.

## Tracks
Search, SOCMINT, GEOINT, Chronolocation, TECHINT, Infrastructure, Maritime, Aviation, Due Diligence, Verification en Analysis.

## GitHub Pages
Deze repository is bedoeld om direct vanaf `main` / root via GitHub Pages te publiceren.

## Security-model
De flags staan niet leesbaar in de challenge-data maar als SHA-256 hashes. Omdat GitHub Pages statisch is, blijft volledige geheimhouding onmogelijk. Voor interne vakontwikkeling is dit doorgaans voldoende; voor formele competitie is server-side flagvalidatie via bijvoorbeeld CTFd geschikter.

Alle namen, bedrijven, domeinen, locaties en onderzoeksdata in deze CTF zijn synthetisch.