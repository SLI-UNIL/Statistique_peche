# Visualisation des donnees-carte interactive de la peche dans le canton de Vaud pour les années de 2020 à 2022

Cette carte représente les statistiques de pêche (nombre de capture par type de poisson et par rivière) dans le canton de Vaud pour les années 2020, 2021 et 2022 de manière interactive. 

## Base de données
### Données géographique
Les données géographique proviennent de [leaflet](https://leafletjs.com/) qui est un contributeur  d'[OSM](https://www.openstreetmap.org/). pour la couche des rivières, elle provient également d'OSM et a été exporter grâce à [overpass_turbo](https://overpass-turbo.eu/).
### Données statistiques
Les données statistiques concernant les captures de pêche sont disponibles sur [le site du canton de vaud](https://www.vd.ch/environnement/biodiversite-et-paysage/peche-1#c2028692). Pour rendre ces données utilisables, il a fallu les transformer de PDF à excel et ensuite les joindre pour avoir les statistiques par années et par rivière. En effet, les données venait sous le format d'PDF par année. Une fois cela fait il a fallu changer les noms des rivières dans le tableau excel pour qu'ils correspondent aux noms des rivières dans la couche Shapefile qui a été transformé par la suite en Geojson.

## Description 
