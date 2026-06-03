# Manipuler des données spatiales avec R

Formation sur la manipulation de données spatiales en R, couvrant les données vectorielles (`sf`) et matricielles (`terra`).

**Auteur :** Steve Vissault — Institut National de la Recherche Scientifique (INRS)

## Contenu de la formation

1. Vue d'ensemble des objets spatiaux
2. Manipulation des vecteurs spatiaux (POINT, LIGNE, POLYGONE)
3. Opérations spatiales sur les vecteurs
4. Manipulation des rasters
5. Opérations spatiales sur les rasters

## Prérequis

```r
install.packages(c("sf", "terra", "mapview"))
```

## Compilation

Le diaporama est construit avec [Quarto](https://quarto.org/) et le format `revealjs`.

```bash
quarto render index.qmd
```

## Données

Les données d'exemple se trouvent dans le dossier `data/` et comprennent des fichiers vectoriels (GDB, Shapefile, CSV) et rasters (GeoTIFF).
