# Kalea - Catalogue des scènes réutilisables

Source : [Conduite.md](Conduite.md). Spectacle de FLAM, accompagné par StarTroopers.

## Décompte proposé

**29 scènes plateau, noir compris**, après regroupement des états identiques. Ajouter **3 états d'avant-spectacle à définir**, soit **32 entrées au total** si le public est également géré par des scènes.

Ce décompte est provisoire : les différences de teinte, de zone et d'intensité sont conservées tant que la conduite ne permet pas de les assimiler. Les 29 scènes plateau sont maintenant créées dans `Kalea.shw`, avec les adaptations matérielles détaillées en fin de document. Les 3 états public restent à définir.

## Principes

- Une scène représente un état lumineux rappelable, indépendamment du top qui l'utilise. Les temps de transition et les déclencheurs appartiennent à la conduite.
- Les tops musicaux seuls ne créent pas de scène. Deux tops rappelant le même éclairage partagent la même scène.
- `PF blanc` est réutilisé aux tops 4, 8, 10 et 39 ; le mot FINAL n'impose pas à lui seul un nouvel état. `PF blanc extérieur` reste distinct, car la conduite distingue cette ambiance.
- Pour les actions relatives (« couper le bleu », « faces renforcées »), l'état résultant est proposé comme scène complète, avec héritage de l'état précédent explicitement signalé. Cet héritage est à valider.
- Les intensités, couleurs exactes, projecteurs concernés et temps de fondu restent à régler. Ne pas interpréter automatiquement PF comme tous les canaux à 100 %.

## Scènes plateau

| ID | Nom proposé | État lumineux | Tops / réutilisations | Réserve ou précision |
|---|---|---|---|---|
| S00 | NOIR | Extinction du plateau | 1, 7, 11, 11.1, 15, 22, 28 | Top 22 : déclencheur **[texte incomplet à confirmer]**. Ne préjuge pas de l'extinction du public. |
| S01 | PF BLANC | Plein feu blanc | 4, 8, 10, 39 | Même état proposé pour le final. |
| S02 | PF BLANC EXT | Plein feu blanc extérieur | 2, 16, 19 | Distinct du PF blanc non qualifié. |
| S03 | BLEU PROFOND DOUCHE CENTRE | Bleu profond + douche + face centre | 5 | La conduite ne précise pas la zone de la douche à ce top ; CENTRE désigne ici la face. |
| S04 | DOUCHE CENTRE LARGE | Douche centre + éclairage large | 6 | Nature du « large » et maintien éventuel du bleu **[à confirmer]**. |
| S05 | ORANGE FACE BLANCHE | Orange + face blanche | 9 | Conserver séparé de l'orange doux. |
| S06 | PF CHAUD INT | Plein feu chaud intérieur | 12 | Couverture intérieure. |
| S07 | BLEU DOUX FACE BLANCHE | Bleu doux + face blanche | 13 | Teinte/intensité distincte du bleu non qualifié. |
| S08 | BLEU SANS FACES | Bleu, faces coupées | 14 | Niveau et teinte du bleu **[à confirmer]** ; continuité du top 13 possible. |
| S09 | ORANGE FACES BLEUES | Orange + faces avant bleues | 17 | État de départ du top 18. |
| S10 | ORANGE SANS FACES BLEUES | État du top 17 avec le bleu coupé | 18 | État déduit de « couper le bleu » : conserver l'orange ; autres composantes **[à confirmer]**. |
| S11 | ORANGE DOUX FACE BLANCHE | Orange doux + face blanche | 20 | Variante douce de S05. |
| S12 | PF BLANC EXT CENTRE | Plein feu blanc extérieur centre | 21 | Variante centrée de S02. |
| S13 | PF CHAUD INT CENTRE | Plein feu chaud intérieur centre | 23 | Variante centrée de S06. |
| S14 | BLEU SOMBRE FACE CENTRE | Bleu sombre + face centre | 24 | **[intention à confirmer]** dans la conduite. |
| S15 | PF CHAUD | Plein feu chaud | 25 | Ne pas assimiler d'office à l'intérieur ou à la soirée. |
| S16 | BLEU FACES BLANCHES | Bleu + faces blanches | 26 et fin de cette musique | La fin de musique conserve cette scène, sans nouvel état. |
| S17 | VERT BLEU FACES CHAUDES | Vert/bleu + faces chaudes | 27 | Répartition des deux couleurs à définir. |
| S18 | PF SOIREE ORANGE SERRE | PF chaud orange, soirée, serré | 29 | « Serré » : **[dernier terme à confirmer]**. |
| S19 | PF LARGE | PF + large à l'arrivée des murs | 30 | Maintien du chaud orange du top 29 **[à confirmer]** ; ne pas présumer un retour au blanc. |
| S20 | FACE CENTRE | Face centre | 31, 37.1 | Même scène proposée ; fond éventuellement maintenu **[à confirmer]**. |
| S21 | BLEU FACE CENTRE | Bleu + face centre | 32 | Pas de douche demandée. Titre musical abrégé dans la conduite. |
| S22 | PF CHAUD ORANGE | Plein feu chaud orange | 33 | Couverture non qualifiée ; séparé du serré et du large. |
| S23 | FACE CHAUDE | Face chaude | 34 | Zone et maintien éventuel du fond **[à confirmer]**. |
| S24 | VIOLET ROSE FACE CENTRE | Violet-rose + face centre | 35 | Répartition et mélange à régler. |
| S25 | PF CHAUD SOIREE | Plein feu chaud, ambiance soirée | 36 | Fusion possible avec S22 si la même teinte orange et la même couverture sont confirmées. |
| S26 | BLEU VERT CENTRE PC2 | Bleu/vert + face centre + PC face 2 | 38 | « PC face 2 » : **[annotation à confirmer]**. |
| S27 | BLEU VERT FACE COTE | Face centre baissée, face côté montée, PC face 2 coupé | Après 38 : « Les jeunes écoutent » | **[à confirmer]** dans la conduite. Maintien du bleu/vert déduit du top 38, à valider. Niveaux finaux à définir. |
| S28 | FACES RENFORCEES | État précédent avec les faces renforcées | Musique 16 | État relatif : faces concernées, intensités, fond et maintien du PC2 coupé **[à confirmer]**. |

## Avant-spectacle : 3 états réservés

Matériel public confirmé par l'utilisateur : les deux Z120M de la page `ProjoSalle`, U1 — 031 (ID 7) et U1 — 073 (ID 1). Leur présence est vérifiée dans Aida, StartTrooper_BASE et Kalea. La correspondance individuelle G/D n'est pas explicitée dans leurs noms enregistrés. Voir [la déclaration matérielle](../docs/fixtures.md). Les états ci-dessous restent à définir ; cette confirmation du matériel ne les programme pas.

Les repères ci-dessous sont ceux de la rubrique « Avant spectacle » ; ils ne sont pas les tops 1 et suivants du plateau.

| ID | Nom proposé | Repère public | Définition à préciser |
|---|---|---|---|
| P01 | PUBLIC | 1 | Éclairage d'accueil du public **[à confirmer]**. |
| P02 | STAR PUBLIC | 1.1 | Signification de « Star public » et différence avec P01 **[à confirmer]**. |
| P03 | NOIR PUBLIC | 1.2 | « NOIR NOIR - public » : périmètre de l'extinction **[à confirmer]**. Fusion avec S00 seulement si les mêmes sources doivent être éteintes. |

## Repères sans nouvelle scène

| Repère | Traitement |
|---|---|
| Top 3, musique 1 | Lancement musical seul ; aucun nouvel état décrit. |
| Tops 15.1 et 22.1 | État non précisé : **[à confirmer]**. Aucun état ajouté ou maintien imposé. |
| Musique 10 | « Salle/Hola » **[à confirmer]** ; aucun nouvel état lumière décrit. |
| Top 37, musique 15 | Lancement musical seul ; la face centre est indiquée au sous-top 37.1. |

## Regroupements supplémentaires possibles après confirmation

- S01 / S02 : PF blanc et PF blanc extérieur, si leur rendu est identique.
- S05 / S11 : orange et orange doux avec face blanche, si les niveaux sont identiques.
- S07 / S16 : bleu doux et bleu avec faces blanches, si teinte, niveaux et couverture sont identiques.
- S14 / S21 : bleu sombre et bleu avec face centre, si l'intention du top 24 le permet.
- S22 / S25 : PF chaud orange et PF chaud soirée, si la soirée correspond au même état.

Chaque paire fusionnée retire une scène au total. **Ne pas appliquer ces fusions avant confirmation** : elles risqueraient d'effacer une nuance voulue. Les deux passages avec douche (tops 5 et 6) restent deux états différents.

## Suivi

Mettre ce catalogue et son décompte à jour lorsque la conduite évolue ou qu'une incertitude est levée. Les mentions ajoutées ici signalent des choix nécessaires à la programmation, en complément des annotations de la transcription. Se référer à [l'inventaire matériel](../docs/fixtures.md) pour le patch. L'éclairage public est identifié sur ProjoSalle ; aucune douche n'est disponible et l'affectation du PC face 2 reste inconnue.

## Programmation réalisée le 14 septembre 2026
**29 scènes S00 à S28 ajoutées sur la page Master de `Kalea.shw`.** Les trois états public restent à définir et ne sont pas programmés. Les noms de la table initiale décrivent la conduite ; les noms ci-dessous sont ceux des boutons adaptés au matériel.
La sauvegarde avant modification est [Kalea_avant_scenes_2026-09-14.shw](sauvegardes/Kalea_avant_scenes_2026-09-14.shw). Le patch, les profils matériels et les autres pages sont conservés. Les références Master à des boutons absents de la base ont été remplacées par le classement des nouvelles scènes.
### Affectation et adaptations
- Faces : PROJO JARDIN G/D (49, 67), CENTRE G/D (43, 61), COUR G/D (37, 55), univers 1. Les deux appareils de chaque zone reçoivent le même niveau.
- Ambiance avant : LED FRONT JARDIN/CENTRE/COUR (1, 11, 21). Décor : LED PALMIER G/D (161, 170).
- S03 et S04 : aucune douche ; accent central produit par les deux PROJO CENTRE. S04 ouvre aussi cour et jardin. Cela conserve une focalisation, sans reproduire une lumière verticale.
- S26 : PC face 2 non identifié, remplacé par un centre renforcé à 90 %. S27 réduit le centre et monte les zones latérales ; S28 les renforce. Choix de départ **[à confirmer en répétition]**.
- Intérieur/extérieur : différenciation de teinte et de niveau, pas de changement réel de position. Serré/large : sélection des zones fixes ; aucun zoom motorisé supposé.
- S09 : bleu sur les faces et LED FRONT, orange sur les PALMIER. S10 coupe les deux groupes bleus et conserve le décor orange.
- LED BACK, PROJO SECOURS, néon, salle, packs MPX, fumée et brouillard ne sont pas commandés par ces scènes. S00 éteint les 11 appareils utilisés ; ce n’est pas un blackout universel de tous les appareils du patch.
- Chaque scène fixe les 84 canaux des 11 appareils utilisés : pas de dépendance à la scène précédente pour ces canaux. Les autres appareils et les éventuelles commandes live restent indépendants.
### Niveaux de départ
Pourcentages de dimmer, non mesures photométriques. J/C/Co = jardin/centre/cour. Le dimmer de chaque bouton est à 100 %. États statiques, sans fondu automatique : transitions à régler avec la conduite. Toutes les nuances et tous les niveaux ci-dessous sont des propositions ajustables **[à confirmer en répétition]**.
| Bouton Master | Faces J/C/Co | Couleur faces | FRONT couleur ; J/C/Co | PALMIER G / D ; niveau |
|---|---|---|---|---|
| S00 NOIR | 0/0/0 % | blanc | bleu ; 0/0/0 % | bleu / bleu ; 0 % |
| S01 PF BLANC | 80/80/80 % | blanc | blanc ; 20/20/20 % | blanc / blanc ; 20 % |
| S02 PF BLANC EXT | 85/85/85 % | blanc | bleu doux ; 20/20/20 % | bleu doux / bleu doux ; 25 % |
| S03 BLEU PROFOND ACCENT CENTRE | 0/80/0 % | blanc | bleu profond ; 35/15/35 % | bleu profond / bleu profond ; 35 % |
| S04 ACCENT CENTRE LARGE | 45/85/45 % | blanc | bleu doux ; 20/10/20 % | bleu doux / bleu doux ; 25 % |
| S05 ORANGE FACE BLANCHE | 65/65/65 % | blanc | orange ; 45/45/45 % | orange / orange ; 50 % |
| S06 PF CHAUD INT | 70/70/70 % | chaud | orange ; 15/15/15 % | orange / orange ; 20 % |
| S07 BLEU DOUX FACE BLANCHE | 55/55/55 % | blanc | bleu doux ; 30/30/30 % | bleu doux / bleu doux ; 30 % |
| S08 BLEU SANS FACES | 0/0/0 % | blanc | bleu doux ; 30/30/30 % | bleu doux / bleu doux ; 30 % |
| S09 ORANGE FACES BLEUES | 30/30/30 % | bleu | bleu ; 40/40/40 % | orange / orange ; 50 % |
| S10 ORANGE SANS FACES BLEUES | 0/0/0 % | bleu | bleu ; 0/0/0 % | orange / orange ; 50 % |
| S11 ORANGE DOUX FACE BLANCHE | 55/55/55 % | blanc | orange ; 25/25/25 % | orange / orange ; 30 % |
| S12 PF BLANC EXT CENTRE | 15/85/15 % | blanc | bleu doux ; 10/20/10 % | bleu doux / bleu doux ; 20 % |
| S13 PF CHAUD INT CENTRE | 10/70/10 % | chaud | orange ; 5/15/5 % | orange / orange ; 15 % |
| S14 BLEU SOMBRE FACE CENTRE | 0/55/0 % | blanc | bleu profond ; 20/10/20 % | bleu profond / bleu profond ; 20 % |
| S15 PF CHAUD | 75/75/75 % | chaud | chaud ; 15/15/15 % | orange / orange ; 15 % |
| S16 BLEU FACES BLANCHES | 65/65/65 % | blanc | bleu ; 45/45/45 % | bleu / bleu ; 45 % |
| S17 VERT BLEU FACES CHAUDES | 60/60/60 % | chaud | bleu ; 35/35/35 % | vert / bleu ; 45 % |
| S18 PF SOIREE ORANGE SERRE | 10/65/10 % | chaud | orange ; 10/30/10 % | orange / orange ; 25 % |
| S19 PF SOIREE LARGE | 75/75/75 % | chaud | orange ; 35/35/35 % | orange / orange ; 40 % |
| S20 FACE CENTRE | 0/70/0 % | blanc | bleu ; 0/0/0 % | bleu / bleu ; 0 % |
| S21 BLEU FACE CENTRE | 0/70/0 % | blanc | bleu ; 40/20/40 % | bleu / bleu ; 40 % |
| S22 PF CHAUD ORANGE | 70/70/70 % | chaud | orange ; 40/40/40 % | orange / orange ; 40 % |
| S23 FACE CHAUDE | 60/60/60 % | chaud | orange ; 0/0/0 % | orange / orange ; 0 % |
| S24 VIOLET ROSE FACE CENTRE | 0/70/0 % | blanc | violet ; 40/20/40 % | violet / rose ; 45 % |
| S25 PF CHAUD SOIREE | 65/65/65 % | chaud | orange ; 25/25/25 % | orange / orange ; 30 % |
| S26 BLEU VERT CENTRE RENFORCE | 25/90/25 % | blanc | bleu ; 35/20/35 % | vert / bleu ; 40 % |
| S27 BLEU VERT FACE COTE | 70/25/70 % | blanc | bleu ; 35/20/35 % | vert / bleu ; 40 % |
| S28 FACES RENFORCEES | 90/45/90 % | blanc | bleu ; 35/20/35 % | vert / bleu ; 40 % |

### Réglages techniques et validation
Couleurs RGBW (0–255), avant application du dimmer : blanc = (255, 255, 255, 255); chaud = (255, 160, 59, 14); orange = (255, 90, 0, 0); bleu = (0, 0, 255, 0); bleu doux = (20, 65, 255, 0); bleu profond = (0, 0, 190, 0); vert = (0, 200, 70, 0); violet = (170, 0, 255, 0); rose = (255, 0, 100, 0). Ambre et UV dédiés des UB 9H à zéro ; macros et programmes automatiques désactivés.
Les canaux sont construits sur les modèles des scènes Aida dont le patch est identique. Z120M : 6 canaux (dimmer, strobe, R, G, B, W), strobe à 0 conformément au profil existant « NoFunction » et au [manuel r1](https://images.thomann.de/pics/atg/atgdata/document/manual/451128_c_451128_r1_en_online.pdf). Des versions matérielles plus récentes ont une autre table : vérifier le shutter lors du premier essai si les faces restent noires. UB 9H : 10 canaux, shutter à 32 (plage ouverte du preset Aida), dimmer au canal 9 ; [documentation constructeur](https://www.adj.com/products/ub-9h). PALMIER : valeurs statiques sur les 9 canaux, structure reprise de la scène Ambre existante.
Contrôles effectués : archive ZIP intègre, 29 scènes uniques, références de boutons résolues, IDs et nombres de canaux conformes au patch, valeurs 0–255, extinction des dimmers utilisés dans S00, conservation octet pour octet des entrées non modifiées et sauvegarde vérifiée par SHA-256. **Ouverture dans Sunlite et rendu réel non vérifiés ici** ; contrôler en répétition les teintes, niveaux et éventuels overrides live avant exploitation.

## Consigne pour les futurs états public

Utiliser ensemble les deux projecteurs ProjoSalle, U1 — 031 et U1 — 073, sans distinction G/D et avec les mêmes réglages. Cette consigne remplace la réserve sur leur identification gauche/droite. Les intentions des états public restent à préciser ; aucune scène supplémentaire n'a été créée par cette mise à jour documentaire.

