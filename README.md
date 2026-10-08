# Slekta Wiborg og Aanonsen

En anetavle med kilder for slekta Wiborg (farssiden) og Aanonsen (morssiden). Treet går sju generasjoner bakover, til Kongsvinger, Eidskog og Vinger, til Fredrikstad, Skjeberg og Romedal, og til Kråkstad, Elverum og Sarpsborg. Det går også over grensen til Skåne og Värmland.

**Se treet:** åpne `index.html` i en nettleser, eller se nettsiden når GitHub Pages er slått på (se under).

## Innhold

| Fil | Hva det er |
|---|---|
| `index.html` | Interaktivt tre. Klikk på en person for å se kilder, søsken og hvor sikker koblingen er. |
| `docs/anetavle.md` | Hele anetavla som tekst, med kilde for hver person. Kan leses direkte på GitHub. |
| `data/slekta-wiborg.ged` | GEDCOM 5.5.1 for import i MyHeritage, Geni, FamilySearch, Gramps og andre slektsprogrammer. |
| `data/personer.json` | Rådata: personer, foreldrekoblinger og kildetekster. |

## Hvor sikre er opplysningene?

Hver person har en status:

- **Dokumentert**: funnet i en primærkilde, som kirkebok, folketelling eller dødsregister. Digitalarkivet-ID-en står i kildefeltet, så alt kan etterprøves.
- **Oppgitt av familien**: opplysninger fra familien som ikke er kontrollert i arkivene ennå.
- **Ikke bekreftet**: sannsynlig ut fra navneskikk, sted og alder, men ikke bekreftet i kirkebok.
- **Ukjent**: neste ledd å finne.

Sekundærkilder, som andres trær på Geni og FamilySearch, avisartikler og bygdebøker, står som «spor». De er ikke brukt som bevis.

## Personvern

Levende personer er tatt ut av denne offentlige versjonen. De to yngste leddene, utgangspersonen og foreldrene, står derfor bare som «Levende person». Den fullstendige versjonen ligger privat hos forfatteren.

## Publiser som nettside med GitHub Pages

1. Lag et nytt repository på github.com, for eksempel `slekta-wiborg`. Velg **Public** hvis andre skal se det.
2. Klikk **Add file → Upload files**, og dra inn alt innholdet i denne mappen. Ta med mappene `data` og `docs`, og fila `.nojekyll`.
3. Klikk **Commit changes**.
4. Gå til **Settings → Pages**. Under «Build and deployment» velger du **Deploy from a branch**, deretter grenen **main** og mappen **/ (root)**. Klikk **Save**.
5. Etter et minutt eller to ligger treet på `https://<brukernavn>.github.io/slekta-wiborg/`.

## Bidra

Har du opplysninger om noen i treet, eller ser du en feil? Opprett en issue i repositoryet. Oppgi gjerne kilden, helst med Digitalarkivet-ID.

## Kilder og verktøy

Hovedkildene er kirkebøker og folketellinger på [Digitalarkivet](https://www.digitalarkivet.no) og [Historisk befolkningsregister](https://www.histreg.no). Søk og sammenstilling er gjort med hjelp av Claude (Anthropic), og alle koblinger er kontrollert mot kildene som er oppgitt.

Sist oppdatert 8. oktober 2026.
