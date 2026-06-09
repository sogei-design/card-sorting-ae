# Card Sorting AE

Card sorting per validare la nuova architettura informativa del portale Agenzia delle Entrate.

**Owner:** CXMSogei (migrato da roccajoe il 09/06/2026)  
**App:** https://cxmsogei.github.io/card-sorting-ae/

## Stack
- Frontend: HTML/CSS/JS vanilla
- Import: Excel (.xlsx) con 14 colonne — auto-detect by header
- Storage: Firebase Realtime DB (card-sorting-ae)

## File
- `index.html` — app card sorting
- `DB_Schede_Import_CardSorting.xlsx` — DB import (316 schede non-archiviate, post Ecotassa ID 513)

## Schema DB
ID · Nome · URL · Area AS-IS · Label (TO-BE) · Template · Tipo · Action · Macro Area 1 · Macro Area 2 · Sotto-categoria 1 · Sotto-categoria 2 · Life Event · Abstract
