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
└── FLAM_Kalea/
    └── Kalea.shw             # Spectacle de la troupe FLAM
```

## Documentation

- [Matériels configurés et adressage DMX](docs/fixtures.md)

`FLAM_Kalea/Kalea.shw` a été créé par copie de `StartTrooper_BASE.shw`, puis déplacé dans son dossier actuel. C’est le fichier de travail pour Kalea.

## Convention de nommage

- Les dossiers des spectacles de StarTroopers portent directement le nom du spectacle, par exemple `Aida/`.
- Pour les autres troupes, le nom de la troupe sert de namespace : `<Troupe>_<Spectacle>/`. Ainsi, `FLAM_Kalea/` désigne le spectacle Kalea de FLAM.
- Le fichier `.shw` porte le nom du spectacle, par exemple `Kalea.shw`.
- Conserver le nom actuel du fichier de base : `StartTrooper_BASE.shw`.

## Mise à jour

Maintenir ce README à jour lors de chaque ajout, déplacement, renommage ou suppression d’un fichier ou dossier de projet. Adapter l’arborescence et les descriptions aux emplacements réels.
