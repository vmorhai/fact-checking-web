# Overovanie faktov na základe prehľadávania webu

Bakalársky projekt, TUKE FEI. Autor: Vladyslav Morhai.
Vedúci: doc. Ing. Marián Mach


## Abstrakt
Modulárny pipeline na overovanie faktov: pre zadané tvrdenie (angličtina)
vygeneruje vyhľadávací dopyt, získa webové stránky, pomocou modelu NLI určí
vzťah ich textu k tvrdeniu a výsledky agreguje do verdiktu (potvrdené,
vyvrátené, protichodné dôkazy, nedostatok informácií) s mierou istoty
a zoznamom dôkazov. Vyhodnotenie na datasete AVeriTeC. Porovnanie s prístupom
založeným na LLM je voliteľné.

## Štruktúra
- `doc/` – plán projektu (`main.tex`, `references.bib`, PDF)
- `src/` – zdrojový kód
- `requirements.txt` – závislosti

## Spustenie
## Stav
Hotový plán projektu a základná kostra kódu. Ďalšie moduly (vyhľadávanie,
sťahovanie textu, NLI, vyhodnotenie) sa implementujú v ďalšom kroku.

## Datasety
- FEVER: https://fever.ai/dataset/fever.html
- AVeriTeC: https://fever.ai/dataset/averitec.html
- Demagog.sk (slovenčina): https://huggingface.co/datasets/NaiveNeuron/DemagogSK

## Literatúra
Úplný zoznam je v `doc/references.bib`.

