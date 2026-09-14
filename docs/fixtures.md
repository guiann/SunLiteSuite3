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
| Z120M Par 64 RGBW 120W (ProjoSalle — public) | Z120M PAR 64 RGBW 120W | Stairville | U1 — 031 |
| PROJO COUR G | Z120M PAR 64 RGBW 120W | Stairville | U1 — 037 |
| PROJO CENTRE G | Z120M PAR 64 RGBW 120W | Stairville | U1 — 043 |
| PROJO JARDIN G | Z120M PAR 64 RGBW 120W | Stairville | U1 — 049 |
| PROJO COUR D | Z120M PAR 64 RGBW 120W | Stairville | U1 — 055 |
| PROJO CENTRE D | Z120M PAR 64 RGBW 120W | Stairville | U1 — 061 |
| PROJO JARDIN D | Z120M PAR 64 RGBW 120W | Stairville | U1 — 067 |
| Z120M Par 64 RGBW 120W 1 (ProjoSalle — public) | Z120M PAR 64 RGBW 120W | Stairville | U1 — 073 |
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

## Fonctions scéniques

| Groupe | Fonction |
|---|---|
| ProjoSalle — paire d'éclairage public | Deux Z120M dédiés à l'éclairage de la salle et du public, affectation confirmée par l'utilisateur. Ils sont distincts des PROJO COUR/CENTRE/JARDIN qui éclairent le plateau. Correspondance individuelle gauche/droite à relever : les noms enregistrés ne comportent pas G/D. |
| PROJO COUR, CENTRE et JARDIN | Projecteurs de face implantés en fond de salle et orientés vers la scène. Leur répartition par zones permet d'assurer l'éclairage principal des interprètes et de modeler la scène de cour à jardin. |
| LED FRONT COUR, CENTRE et JARDIN | Projecteurs LED dédiés à la création d'ambiances colorées sur l'avant-scène. Leur implantation par zones permet de composer des états lumineux homogènes ou différenciés entre cour, centre et jardin. |
| LED PALMIER G et D | Barres LED implantées en fond de scène. Elles assurent la mise en valeur chromatique des décors et créent des ambiances lumineuses en contre et en fond de scène. |
| FUMEE — Cirrus 1000 | Machine à fumée lourde produisant un effet bas, dense et localisé, destiné à napper le sol de la scène. |
| BROUILLARD — Hazer 2000 | Machine à brouillard produisant une brume légère et diffuse dans la salle. Elle matérialise les faisceaux lumineux et contribue à l'ambiance générale sans former de nuage de fumée dense. |
| NEON — Neon Tube | Élément lumineux flexible utilisé comme source décorative. Il permet de souligner des formes, des volumes ou des éléments de scénographie. |

## Vérification de l'éclairage public

La paire de la page `ProjoSalle` est présente dans **Aida**, **StartTrooper_BASE** et **Kalea**, avec les mêmes identifiants, profils, modes et adresses (vérification du 14 septembre 2026).

| ID interne | Nom enregistré | Page | Canaux DMX | Aida | Base | Kalea |
|---|---|---|---|---|---|---|
| 7 | Z120M Par 64 RGBW 120W | ProjoSalle | U1 — 031 à 036 | Présent | Présent | Présent |
| 1 | Z120M Par 64 RGBW 120W  1 | ProjoSalle | U1 — 073 à 078 | Présent | Présent | Présent |

Les deux appareils utilisent le profil `STAIRVILLE\Z120M PAR 64 RGBW 120W.SSL2`, en mode 6 canaux (`Mode="4"` dans le fichier). Les suffixes « ProjoSalle — public » du tableau d'inventaire sont des précisions documentaires, pas des renommages dans les projets. Aucun libellé explicite « Salle G » ou « Salle D » n'a été trouvé dans les données textuelles d'Aida ; ne pas attribuer un côté à une adresse sans vérification de l'implantation.

Dans Kalea, ces appareils sont patchés mais ne sont pas commandés par les 29 scènes plateau S00 à S28. Le rôle du matériel public est désormais confirmé ; les actions « Public », « Star public » et « NOIR NOIR — public » restent à préciser avant leur programmation.

Cet inventaire est extrait des fichiers internes `_fixtures.xml` et `ProjoSalle/_page.pda` de chaque projet `.shw`. Lorsqu'un appareil ou son adresse change dans Sunlite Suite 3, mettre ce tableau à jour et vérifier que le patch reste cohérent entre les projets.

## Commande du public

Consigne utilisateur : commander ensemble les deux projecteurs ProjoSalle (U1 — 031 et U1 — 073), avec les mêmes réglages, pour les éclairages public. Aucune distinction gauche/droite n'est nécessaire ; leur correspondance G/D n'est donc plus un point à confirmer.

