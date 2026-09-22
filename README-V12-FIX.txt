GOAT WEBSITE V12 FIX

Naprawiono błąd JS w v11: apply() było wywoływane zanim GOAT_ASSET_MAP został zainicjalizowany.
To powodowało ReferenceError i zatrzymywało zmianę języka.

V12:
- PL / EN / DE / FR / IT / ES / PT znów przełączają teksty.
- Grafiki językowe przełączają się niezależnie.
- Brak grafiki nie zatrzymuje tłumaczenia strony; jest fallback do polskiej grafiki.
- Oryginalna struktura strony i polskie grafiki zostały zachowane.

Wgraj CAŁĄ zawartość paczki do głównego katalogu repozytorium i zatwierdź Commit changes.
