# Projets Sunlite Suite 3 — StarTroopers

Ce dossier regroupe les projets d’éclairage Sunlite Suite 3 de notre troupe, **StarTroopers**, ainsi que ceux des autres troupes auxquelles nous donnons un coup de main.

## Troupes et spectacles

- **StarTroopers** est notre troupe. **Aida** est l’un de nos spectacles.
- **FLAM** est une autre troupe que nous aidons. **Kalea** est leur spectacle.

## Hiérarchie des fichiers

```text
SunliteSuite3/
├── AGENT.md                 # Consignes d’intervention dans ce dépôt
├── README.md                # Organisation et inventaire des projets
├── docs/
│   └── fixtures.md           # Matériels et adressage DMX communs
├── StartTrooper_BASE.shw     # Projet Sunlite de base
├── Aida/
│   └── Aida.shw              # Spectacle de StarTroopers
├── FLAM_Kalea/
│   ├── Conduite.md           # Conduite lumière et annotations à confirmer
│   ├── Scenes.md             # Catalogue des états lumineux réutilisables
│   ├── Kalea.shw             # Spectacle FLAM : 29 scènes plateau sur Master
│   └── sauvegardes/
│       └── Kalea_avant_scenes_2026-09-14.shw # Copie avant programmation
└── output/
    └── pdf/
        └── Kalea_Conduite_condensee.pdf # Conduite imprimable sur deux pages
```

## Documentation

- [Matériels configurés et adressage DMX](docs/fixtures.md)
- [Conduite lumière de Kalea](FLAM_Kalea/Conduite.md)
- [Scènes réutilisables de Kalea](FLAM_Kalea/Scenes.md) - décompte, correspondance avec les tops et points à confirmer.
- [Conduite condensée de Kalea en PDF](output/pdf/Kalea_Conduite_condensee.pdf) - annotations « à confirmer » conservées ; à régénérer si la conduite change.

`FLAM_Kalea/Kalea.shw` a été créé par copie de `StartTrooper_BASE.shw`, puis déplacé dans son dossier actuel. C’est le fichier de travail pour Kalea.

Il contient désormais 29 scènes plateau adaptées aux faces, LED FRONT et LED PALMIER disponibles, sans douche. Les affectations, niveaux proposés et points à confirmer sont détaillés dans `FLAM_Kalea/Scenes.md`. Les états public restent à définir. L'archive a été vérifiée, mais l'ouverture dans Sunlite et le rendu sur le matériel restent à contrôler.

## Convention de nommage

- Les dossiers des spectacles de StarTroopers portent directement le nom du spectacle, par exemple `Aida/`.
- Pour les autres troupes, le nom de la troupe sert de namespace : `<Troupe>_<Spectacle>/`. Ainsi, `FLAM_Kalea/` désigne le spectacle Kalea de FLAM.
- Le fichier `.shw` porte le nom du spectacle, par exemple `Kalea.shw`.
- Conserver le nom actuel du fichier de base : `StartTrooper_BASE.shw`.

## Mise à jour

Maintenir ce README à jour lors de chaque ajout, déplacement, renommage ou suppression d’un fichier ou dossier de projet. Adapter l’arborescence et les descriptions aux emplacements réels.
