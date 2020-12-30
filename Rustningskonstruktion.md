---
author: Joel
category:
- Regelsidor
- Rustningar
- Work in progress
created_at: '2011-03-07T17:41:43Z'
id: rustningskonstruktion
title: Rustningskonstruktion
---
Hur man sätter ihop rustningar.

## Material

| Pansartyp       | Hugg | Kross | Stick | BRYT | Pris          | Tid  | Vikt      |
|:----------------|------|-------|-------|------|---------------|------|-----------|
| Alvglas         | 13   | 11    | 11    | 20   | (500 sunuvai) | 100h | 0,40kg    |
| Ben             | 3    | 4     | 3     | 5    | 1 silver      | 40h  | 0,35kg    |
| Benfjäll        | 7    | 5     | 3     | 5    | 25 silver     | 5h   | 0,35kg    |
| Benlamell       | 7    | 5     | 6     | 6    | 30 silver     | 8h   | 0,325kg   |
| Bronsplåt       | 10   | 7     | 11    | 14   | 162 silver    | 15h  | 0,65kg    |
| Fjällpansar     | 8    | 5     | 5     | 15   | 25 silver     | 5h   | 0,45kg    |
| Guldplåt        | 6    | 4     | 6     | 12   | 24.700 silver | 40h  | 1,40kg    |
| Lamellpansar    | 8    | 3     | 7     | 16   | 30 silver     | 8h   | 0,40kg    |
| Läder, härdat   | 5    | 6     | 5     | 15   | 12 silver     | 10h  | 0,30kg    |
| Läder, mjukt    | 3    | 4     | 3     | 14   | 4 silver      | 3h   | 0,15kg    |
| Nitläder        | 7    | 5     | 4     | 14   | 16 silver     | 5h   | 0,40kg    |
| Plåt            | 13   | 9     | 14    | 20   | 80 silver     | 25h  | 0,50kg\*  |
| Päls            | 2    | 3     | 2     | 13   | 3 silver      | 2h   | 0,15kg    |
| Ringbrynja      | 10   | 1     | 6\*   | 17   | 40 silver     | 16h  | 0,425kg   |
| Ringbrynja, tät | 12   | 2     | 8\*   | 19   | 60 silver     | 24h  | 0,60kg    |
| Ringläder       | 7    | 5     | 4     | 12   | 20 silver     | 5h   | 0,60kg    |
| Siluna          | 6    | 4     | 6     | 12   | 60 silver     | 15h  | 0,30kg    |
| Silver          | 10   | 7     | 11    | 14   | 705 silver    | 30h  | 0,80kg    |
| Somdiaplåt      | 15   | 11    | 14    | 20   | 150 silver    | 30h  | 0,60kg    |
| Somdiabrynja    | 13   | 2     | 8\*   | 17   | 80 silver     | 20h  | 0,425kg   |
| Thabrinkk       | 15   | 1     | 4\*   | 19   | 60 silver     | 24h  | 1kg       |
| Tjockplåt       | 26   | 18    | 28    | 24   | 130 silver    | 35h  | 1,05kg\*  |
| Trä             | 4    | 5     | 4     | 7    | 3 silver      | 10h  | 0,925kg   |
| Träfjäll        | 6    | 5     | 3     | 10   | 25 silver     | 5h   | 0,35kg    |
| Trälamell       | 6    | 5     | 5     | 12   | 30 silver     | 8h   | 0,325kg\* |
| Tunnplåt        | 7    | 5     | 7     | 16   | 60 silver     | 20h  | 0,4kg\*   |
| Vadderat tyg    | 2    | 3     | 1     | 10   | 2 silver      | 2h   | 0,10kg    |
| Lumianfjäll     | 23   | 22    | 19    | 25   | \-            | \-   | 0,3kg     |
| Mortuachfjäll   | 25   | 24    | 21    | 28   | \-            | \-   | 0,35kg    |
| Vrakhpansar     | 17   | 16    | 17    | 16   | \-            | \-   | 0,55kg\*  |
| Krokodilskinn   | 5    | 6     | 5     | 15   | 12 silver     | 10h  | 0,30kg    |

*\*Reviderade värden.*

## Rustningstyp

| Delområde        | Kod | Delområdesfaktor |
|:-----------------|-----|------------------|
| Ansikte          | 1   | 1                |
| Skalle           | 2   | 2                |
| Hals/Nacke       | 3   | 1                |
| Vänster skuldra  | 4   | 1                |
| Höger skuldra    | 5   | 1                |
| Vänster överarm  | 6   | 1                |
| Höger överarm    | 7   | 1                |
| Vänster armbåge  | 8   | 1                |
| Höger armbåge    | 9   | 1                |
| Vänster underarm | 10  | 1                |
| Höger underarm   | 11  | 1                |
| Vänster hand     | 12  | 1                |
| Höger hand       | 13  | 1                |
| Bröstkorg        | 14  | 4                |
| Mage             | 15  | 3                |
| Underliv         | 16  | 1                |
| Vänster höft     | 17  | 1                |
| Höger höft       | 18  | 1                |
| Vänster lår      | 19  | 3                |
| Höger lår        | 20  | 3                |
| Vänster knä      | 21  | 1                |
| Höger knä        | 22  | 1                |
| Vänster vad      | 23  | 2                |
| Höger vad        | 24  | 2                |
| Vänster fot      | 25  | 1                |
| Höger fot        | 26  | 1                |

### Exempel

**Harnesk** Täcker: 4-5, 14-15. Multipel: x9

**Halvrustning** Täcker: 4-5, 14-15, 17-18. Multipel: x11

**Helrustning** Täcker: 4-11, 14-26. Multipel: x32

#### Hjälmar

**Anisktsmask** Täcker: 1 Multipel: x1

**Öppen hjälm** Täcker: 2 Multipel: x2

**Hjäm med visir/ansiktsskydd** Täcker 1-2 Multipel: x3

**Hjäm med nackskydd eller coif** Täcker 2-3 Multipel: x3

**Tunnhjälm** Täcker: 1-3 Multipel: x4

## Storlek

| Längd        | Modifikation    |
|:-------------|-----------------|
| varje -10 cm | -5% ytterligare |
| 121-130 cm   | x0,75 (-25%)    |
| 131-140 cm   | x0,80 (-20%)    |
| 141-150 cm   | x0,85 (-15%)    |
| 151-160 cm   | x0,90 (-10%)    |
| 161-170 cm   | x0,95 (-5%)     |
| 171-180 cm   | x1,00 (+0%)     |
| 181-190 cm   | x1,05 (+5%)     |
| 191-200 cm   | x1,10 (+10%)    |
| 201-210 cm   | x1,15 (+15%)    |
| 211-220 cm   | x1,20 (+20%)    |
| varje +10 cm | +5% ytterligare |

| Vikt         | Modifikation    |
|:-------------|-----------------|
| varje -10 kg | -5% ytterligare |
| 51-60 kg     | x0,95 (-5%)     |
| 61-70 kg     | x1,00 (+0%)     |
| 71-80 kg     | x1,05 (+5%)     |
| 81-90 kg     | x1,10 (+10%)    |
| 91-100 kg    | x1,15 (+15%)    |
| 101-110 kg   | x1,20 (+20%)    |
| 111-120 kg   | x1,25 (+25%)    |
| 121-130 kg   | x1,30 (+30%)    |
| 131-140 kg   | x1,35 (+35%)    |
| 141-150 kg   | x1,40 (+40%)    |
| varje +10 kg | +5% ytterligare |

## Särskilda egenskaper

**Tunnsmidd rustning:** Vikten minskar med 20%, Nackdelar: BRYT -2, Alla pansarvärden minskar med (-1/-1/-1). Pris: x2

**Tjock rustning:** BRYT +2, pansarvärden ökar med (+1/+1/+1). Nackdelar: Vikten ökar med 20%. Pris: x2