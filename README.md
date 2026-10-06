# Concert season management: repertoire, performers, venues and tickets

*Gestione delle stagioni concertistiche: repertorio, esecutori, sedi e biglietti*

**Microsoft Access 97** · 2001 · version 1.0  
Author: **Massimo Sbarbaro** ([ORCID 0009-0006-8965-9013](https://orcid.org/0009-0006-8965-9013))

## Overview

A database for planning and documenting concert seasons. It links composers, collections and works to the concerts of each season, records performers and their instruments, venues, planned and actual dates, and manages ticket types, prices, seating areas and attendance.

I designed and programmed this application in 2001. It is published here in 2026 as part of the documented record of my software work, with a permanent DOI on Zenodo.

## Main functions

- Repertoire: composers with dates and stylistic period, collections and works with opus and text.
- Concerts by season with programme, performers and instruments, planned and actual date and venue.
- Tickets by type, seating area and price, and number of spectators per ticket type.

## Data

Tables `Autore`, `Raccolta`, `Opera`, `Concerto`, `ConcertoOpere`, `ConcertoEsecutore`, `Esecutore`, `Strumento`, `Luogo`, `Biglietto`, `Spettatore`, `Categoria`.

## Technology

Microsoft Access 97 format (.mdb), forms and VBA module.

## Repository contents

| Path | Content |
|---|---|
| `database/` | The Access 97 application, emptied of all data. |
| `docs/schema.md` | Tables and fields. |
| `source/queries/` | SQL of the saved queries. |

## What is not included

The database is published **empty**: every table has been emptied and the file compacted, so no record of the original data survives. The file is in Microsoft Access 97 format: it opens in Access 97–2010; later versions of Access must first convert it with an intermediate version. The table schema is documented in `docs/schema.md`.

## Related repositories

- [sound-music-archive-catalogue-access](https://github.com/massimosbarbaro/sound-music-archive-catalogue-access)

## How to cite

Use the citation metadata in [`CITATION.cff`](CITATION.cff) (GitHub: *Cite this repository*). Each release is archived on Zenodo with its own DOI.

> Sbarbaro, Massimo. *Concert season management: repertoire, performers, venues and tickets (Microsoft Access 97, 2001)*. Software, version 1.0. GitHub: https://github.com/massimosbarbaro/concert-season-management-access

## License

Released under the [MIT License](LICENSE). © 2001 Massimo Sbarbaro.
