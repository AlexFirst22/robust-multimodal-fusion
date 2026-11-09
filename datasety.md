# Porovnanie kandidátskych datasetov

Údaje overené z publikácií datasetov. Polia označené **?** treba ešte overiť na stránkach datasetov.

| | EAV (2024) | K-EmoCon (2020) | Ulm-TSST / MuSe (2021) | MAFW (2022) |
|---|---|---|---|---|
| Modality | EEG (30 kanálov), audio, video | audio, video, EEG, periférne fyziologické signály | audio, video, text (príznaky), EKG, EDA, dýchanie, tep | video, audio, popisný text |
| Účastníci / veľkosť | 42 účastníkov, 8 400 interakcií | 32 účastníkov, 16 debát po ~10 min | 105 účastníkov, ~10 h | 10 045 klipov |
| Scenár | konverzácia podľa podnetov (cue-based) | prirodzené debaty vo dvojici | stresový test TSST (pohovor) | „in the wild" |
| Anotácie | 5 emócií: neutrálna, hnev, radosť, smútok, pokoj | arousal-valence + 18 kategórií, 3 perspektívy, každých 5 s | spojité arousal a valence | 11 jednoduchých + 32 zložených kategórií |
| Jazyk | ? | ? | nemčina | ? |
| Prístup | ? | ? | EULA podpísaná profesorom | uvádzaný ako verejne dostupný, ? podmienky |
| Riziko AI | ? | ? | ? pôvod textových príznakov (ručný prepis alebo ASR) | ? |

## Poznámky

- **MAFW:** textová modalita je *popis správania*, nie prepis reči.
- **Text cez ASR:** ak dataset nemá ručné prepisy, automatický prepis (napr. Whisper) by boli dáta generované AI. Otázka pre vedúcu.

## Otázky na konzultáciu

1. Je prípustný automatický prepis reči (ASR), alebo pracovať len s audio / video / fyziológiou?
2. Môžete podpísať EULA pre Ulm-TSST?
3. Kedy je ďalšia konzultácia a ako chcete sledovať repozitár?

## Zdroje

- EAV: Lee et al., Scientific Data 11, 2024. https://doi.org/10.1038/s41597-024-03838-4
- K-EmoCon: Park et al., Scientific Data 7, 2020. https://doi.org/10.1038/s41597-020-00630-y
- Ulm-TSST: Stappen et al., MuSe 2021 Challenge, ACM MM Workshop. https://doi.org/10.1145/3475957.3484450
- MAFW: Liu et al., ACM MM 2022. https://doi.org/10.1145/3503161.3548190
