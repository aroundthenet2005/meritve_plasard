# Plasard – Merilec (Offline)

To je “offline” web aplikacija (brez strežnika), ki dela direktno iz ZIP-a.

## Zagon
1) Razpakiraj ZIP v poljubno mapo  
2) Odpri `index.html` (dvojni klik)  
3) PDF katalog se odpira iz gumba **PDF** pri artiklu (odpre se na pravi strani).

## Kaj zna
- Meritev: osnovni obrazec + slike (samodejno pomanjšane)
- Dodatki: iskanje + filter (kategorija/sekcija) + dodaj v košarico
- Košarica: količine + seštevek
- Checkout: povzetek + podpis (canvas) + soglasje
- Izvoz:
  - **Izvozi JSON** (order + dodatki + podpis + slike)
  - **Izvozi PDF (Print)** → Ctrl+P → Shrani kot PDF

## Admin
- Nastavi geslo (lokalno) v zavihku Admin
- Urejaj cene/ime/šifre/dimenzije/sekcije
- Export/Import:
  - `plasard_catalog_overrides.json` (samo popravki)
  - `plasard_catalog_full.json` (celotna trenutna baza)

## Opombe
- Vse se shranjuje lokalno v brskalniku (LocalStorage).
- Če izbrišeš “site data” za lokalne datoteke ali uporabiš drug brskalnik, bo baza prazna (seed se bo naložil znova).
- Če se kje v katalogu vidi napaka iz PDF izluščenja: popravi v Adminu in izvozi overrides.
