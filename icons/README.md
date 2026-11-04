# Icônes SailCat

Ce dossier contient les icônes de l'application aux différentes résolutions requises par Sailfish OS.

## Tailles requises

- 86x86 pixels
- 108x108 pixels
- 128x128 pixels
- 172x172 pixels (utilisée dans le README)
- 256x256 pixels

## Format

Les icônes doivent être au format PNG avec transparence.

## Design

L'icône devrait représenter un chat (cat) dans le style de Sailfish OS, avec des couleurs adaptées au thème de l'OS.

## Génération

La source vectorielle est `harbour-sailcat.svg` à la racine de ce dossier. Pour régénérer les PNG :

```bash
scripts/generate-icons.sh
```

Le script utilise `rsvg-convert`, `inkscape` ou ImageMagick. Le SVG peut aussi être édité avec GIMP, Inkscape ou tout autre éditeur graphique.
