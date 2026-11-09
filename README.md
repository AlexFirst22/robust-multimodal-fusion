# Robustná multimodálna fúzia pri neúplných a poškodených vstupných dátach

Bakalárska práca, TUKE FEI, Inteligentné systémy
Autor: Oleksandr Lysytsia
Vedúca práce: Ing. Martina Szabóová, PhD. (ÚUI)

## Cieľ

Rozpoznávanie emócií z viacerých modalít (text, audio, video, prípadne fyziologické signály),
ktoré je odolné voči chýbajúcim a poškodeným modalitám.

## Plán experimentu

1. Výber datasetu (pozri [docs/datasety.md](docs/datasety.md))
2. Baseline model na čistých dátach
3. Umelé poškodenie modalít: chýbajúca modalita, šum, desynchronizácia
4. Meranie poklesu výkonu
5. Robustné trénovanie
6. Opätovné meranie a porovnanie

## Požiadavky na dataset (konzultácia 21.10.2026)

- umelé poškodzovanie dát podľa Hazarika et al. (NAACL 2022) je prípustné
- nepoužívať IEMOCAP, vybrať novší dataset z aktuálnej literatúry
- datasety s ďalšími modalitami (EKG, EEG, EDA) sú vhodné
- v datasete nesmie byť nič generované umelou inteligenciou (dáta ani anotácie)

## Štruktúra repozitára

```
docs/        poznámky k literatúre, porovnanie datasetov
data/        dáta (necommitujú sa, pozri .gitignore)
src/         zdrojový kód
notebooks/   experimenty
```

## Stav

- [x] štúdium Hazarika et al. (NAACL 2022)
- [x] tabuľka typov poškodení (chýba / poškodené × text, audio, video)
- [ ] výber datasetu a žiadosť o prístup
- [ ] modul na poškodzovanie modalít
- [ ] načítanie dát a baseline
