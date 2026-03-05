# TP Dashboard TSI-G – Maïlys Pelissier

## Accès au dashboard

Le dashboard est hébergé et publié par **GitHub Pages**.

Il est directement accessible depuis ce lien :

https://MailysPelissier.github.io/TP_Dashboard_TSIG/

## Fonctionnement

La liste déroulante sous le titre « Indicateur » permet de choisir l’indicateur à afficher.

Le slider en dessous de l’année permet de choisir l’année dans laquelle afficher les données sur la carte. La liste des années disponibles dépend de l’indicateur.

Quand on clique sur une province, les graphiques correspondant aux données de l’indicateur sélectionné sur cette région s’affichent. Il faut bien recliquer sur la région après avoir changé d’indicateur pour que les diagrammes se mettent à jour.

## Structure du projet

```bash
TP_Dashboard_TSIG/
│
├── index.html
├── data/
│   ├── number_WWTP.geojson
│   ├── capacity_pollution_eq.geojson
│   └── bathing_water_provinces.geojson
└── README.md
```

## Technologies utilisées

Les bibliothèques utilisées sont Leaflet pour la cartographie et Chart pour les graphiques.

Le fond cartographique utilisé est celui d’OpenStreetMap.

Les données sont chargés sous la forme de GeoJSON (voir dossier data).
