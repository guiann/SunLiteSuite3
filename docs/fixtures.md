# Matériels configurés

Cette page décrit le patch matériel commun aux projets Sunlite Suite 3 du dépôt :

- `StartTrooper_BASE.shw` ;
- `Aida/Aida.shw` ;
- `FLAM_Kalea/Kalea.shw`.

Les trois projets utilisent la même configuration et le même adressage DMX. Toutes les adresses sont situées sur l'univers 1.

| Nom configuré | Type | Marque | Adressage DMX |
|---|---|---|---:|
| LED FRONT JARDIN | UB 9H | ADJ | U1 — 001 |
| LED FRONT CENTRE | UB 9H | ADJ | U1 — 011 |
| LED FRONT COUR | UB 9H | ADJ | U1 — 021 |
| Z120M Par 64 RGBW 120W | Z120M PAR 64 RGBW 120W | Stairville | U1 — 031 |
| PROJO COUR G | Z120M PAR 64 RGBW 120W | Stairville | U1 — 037 |
| PROJO CENTRE G | Z120M PAR 64 RGBW 120W | Stairville | U1 — 043 |
| PROJO JARDIN G | Z120M PAR 64 RGBW 120W | Stairville | U1 — 049 |
| PROJO COUR D | Z120M PAR 64 RGBW 120W | Stairville | U1 — 055 |
| PROJO CENTRE D | Z120M PAR 64 RGBW 120W | Stairville | U1 — 061 |
| PROJO JARDIN D | Z120M PAR 64 RGBW 120W | Stairville | U1 — 067 |
| Z120M Par 64 RGBW 120W 1 | Z120M PAR 64 RGBW 120W | Stairville | U1 — 073 |
| MPX-4LED Multipack 1 | MPX-4LED Multipack | Botex | U1 — 079 |
| MPX-4LED Multipack 2 | MPX-4LED Multipack | Botex | U1 — 083 |
| LED BACK G | LED STP-14 Sunbar | Eurolite | U1 — 087 |
| LED BACK D | LED STP-14 Sunbar | Eurolite | U1 — 124 |
| LED PALMIER G | LEDBAR24-RC | Ibiza Lighting | U1 — 161 |
| LED PALMIER D | LEDBAR24-RC | Ibiza Lighting | U1 — 170 |
| BROUILLARD | Hazer 2000 | BoomToneDJ | U1 — 179 |
| LED Theater Spot 100 3000K 1 | LED Theater Spot 100 3000K | Varytec | U1 — 181 |
| LED Theater Spot 100 3000K 2 | LED Theater Spot 100 3000K | Varytec | U1 — 183 |
| Cirrus 1000 1 | Cirrus 1000 | BoomToneDJ | U1 — 185 |
| Neon Tube | Neon Tube | Ape Labs | U1 — 196 |

Cet inventaire est extrait du fichier interne `_fixtures.xml` de chaque projet `.shw`. Lorsqu'un appareil ou son adresse change dans Sunlite Suite 3, mettre ce tableau à jour et vérifier que le patch reste cohérent entre les projets.
