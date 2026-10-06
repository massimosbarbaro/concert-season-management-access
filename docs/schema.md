# Table schema

## Autore

| Field | Type | Size |
|---|---|---|
| IdAutore | 3 | 2 |
| Nome | 10 | 100 |
| Cognome | 10 | 100 |
| DataNascita | 8 | 8 |
| DataMorte | 8 | 8 |
| Corrente | 10 | 100 |
| Note | 12 | 0 |

## Biglietto

| Field | Type | Size |
|---|---|---|
| IdBiglietto | 4 | 4 |
| Tipologia | 10 | 50 |
| IdLuogo | 4 | 4 |
| Seduto in | 10 | 50 |
| Costo | 4 | 4 |
| Stagione | 10 | 50 |

## Categoria

| Field | Type | Size |
|---|---|---|
| IdCategoria | 3 | 2 |
| Categoria | 10 | 50 |
| Tipologia | 10 | 50 |
| Sottocategoria | 10 | 50 |

## Concerto

| Field | Type | Size |
|---|---|---|
| IdConcerto | 3 | 2 |
| Stagione | 10 | 10 |
| DataPrevista | 8 | 8 |
| DataEffettiva | 8 | 8 |
| IdLuogoPrevisto | 2 | 1 |
| IdLuogoEffettivo | 2 | 1 |
| IdCategoria | 3 | 2 |
| Descrizione | 10 | 100 |
| Origine | 10 | 50 |
| Fatto | 10 | 1 |
| Note | 10 | 250 |

## ConcertoEsecutore

| Field | Type | Size |
|---|---|---|
| IdConcerto | 3 | 2 |
| IdEsecutore | 3 | 2 |
| IdStrumento | 3 | 2 |
| Fatto | 10 | 3 |

## ConcertoOpere

| Field | Type | Size |
|---|---|---|
| IdConcerto | 3 | 2 |
| IdOpera | 3 | 2 |

## Esecutore

| Field | Type | Size |
|---|---|---|
| IdEsecutore | 3 | 2 |
| Nome | 10 | 50 |
| Cognome | 10 | 50 |
| IdStrumento | 3 | 2 |

## Luogo

| Field | Type | Size |
|---|---|---|
| IdLuogo | 2 | 1 |
| Descrizione | 10 | 200 |
| Via | 10 | 200 |
| Citta | 10 | 100 |
| Cap | 10 | 10 |
| Stato | 10 | 10 |

## Opera

| Field | Type | Size |
|---|---|---|
| IdOpera | 3 | 2 |
| IdRaccolta | 3 | 2 |
| Op | 3 | 2 |
| N | 3 | 2 |
| Titolo | 10 | 250 |
| Note | 12 | 0 |
| Testo | 10 | 100 |

## Raccolta

| Field | Type | Size |
|---|---|---|
| IdRaccolta | 3 | 2 |
| IdAutore | 3 | 2 |
| Raccolta | 10 | 200 |
| Note | 10 | 250 |

## Spettatore

| Field | Type | Size |
|---|---|---|
| IdConcerto | 4 | 4 |
| IdBiglietto | 4 | 4 |
| Spettatori n | 10 | 50 |

## Strumento

| Field | Type | Size |
|---|---|---|
| IdStrumento | 3 | 2 |
| Strumento | 10 | 100 |
| Categoria | 10 | 100 |

