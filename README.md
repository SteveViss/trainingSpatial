# Manipuler des données spatiales avec R

Formation sur la manipulation de données spatiales en R, couvrant les données vectorielles (`sf`) et matricielles (`terra`). Matériel pédagogique développé par [inSileco](https://www.insileco.io/) dans le cadre de l'atelier **R in Space / R et espace**.

**Auteur :** Steve Vissault — Institut National de la Recherche Scientifique (INRS)

La présentation est disponible en ligne : [steveviss.github.io/trainingSpatial](https://steveviss.github.io/trainingSpatial)

## Contenu de la formation

1. Vue d'ensemble des objets spatiaux
2. Système de référence des coordonnées (CRS)
3. Manipulation des vecteurs spatiaux (POINT, LIGNE, POLYGONE)
4. Importer et exporter des objets spatiaux
5. Opérations spatiales avec `sf`
6. Manipulation des rasters avec `terra`
7. Flux de travail intégrés (extraction, empilement)
8. Cartographie avancée (`ggplot2`, `tmap`)

## Prérequis

```r
install.packages(c("sf", "terra", "tmap", "geodata", "rnaturalearth", "tidyterra", "dplyr", "ggplot2"))
```

## Compilation

Le diaporama est construit avec [Quarto](https://quarto.org/) et le format `revealjs`.

```bash
quarto render index.qmd
```

## Données

Les données d'exemple se trouvent dans le dossier `data/` et comprennent des fichiers vectoriels (GDB, Shapefile, CSV) et rasters (GeoTIFF).
