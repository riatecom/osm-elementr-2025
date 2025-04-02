## Utiliser OpenStreetMap avec R

Présentation réalisée par Ronan Ysebaert, Louis Laurian et Timothée Giraud (UAR RIATE pour le groupe [ElementR](https://elementr.gitpages.huma-num.fr/website/apropos.html) en mai 2025.

### Contenu

Cette séance propose de sensibiliser ses participants à l'usage d'OpenStreetMap (OSM) avec R. Après une présentation des spécificités et de l’écosystème de cette base de données participative, nous reviendrons sur les packages R utiles pour interfacer son contenu et réaliser des opérations variées : import de tuiles raster, géocodage, export de données géographiques, calcul d’itinéraires et temps de trajet avec différents modes de transport.

La présentation sera étayée d’exemples d’application issus des travaux et projets du RIATE. Cela permettra d’aborder des aspects connexes liés à la complétude des données, l’implémentation de méthodes d’interpolation spatiale, la mise en place d’engins de routage pour des calculs d’itinéraires massifs ou encore la création d’indicateurs d’accessibilité dérivés de matrices origine-destination.

Cette intervention se conclura par la présentation d’une chaine de traitement reproductible qui résumera les éléments abordés durant la séance et qui pourra utilement être remobilisée dans d’autres contextes spatiaux ou thématiques. 


### Programme détaillé (pour discussion)

#### Le projet OpenStreetMap

####OpenStreetMap en qqes mots

- Juillet 2004, Steve Coast.
- Wikipedia de la donnée géographique
- Courant du libre (licence Open Data Commons Open Database License)
- Contribution par les utilisateurs
- OpenStreetMap France, 2011

#### L'usage d'OSM

- Evolution des utilisateurs à travers le temps (https://osmstats.neis-one.org/?item=members). 38 % des utilisateurs inscrits ont modifié un objet et 38 % ont contribué de manière significative (Zipf, 2012). 
- Evolution des contributions
- Contributions par pays (source Geofabrik)

#### Les objets géographiques dans OSM

- nodes : un noeud qui contient des données avec sa position, des métadonnées (dernières contributions, modifications) et éventuellement des *tags* sous forme de pairs *key-value*.
- way : une ligne avec au minimum 2 nodes. Peut se référer aussi à un polygone (une ligne qui a partage son premier et dernier point)
- relation: décrit des relations plus complexes entre les objets (objets référencés appartenant à un aéroport, par exemple). 

### Les tags OSM

- key-value
- OSM wiki


#### Précision et complétude

- Précision géométrique
- Complétude des attributs / exemple tiré de l'étude centralité
- Aspect liés à la saturation et complétude des attributs (Heidelberg Institute for Geoinformation Technology) > [Ohsome Dashboard](https://dashboard.ohsome.org/#backend=ohsomeApi&groupBy=none&time=%2F2025-02-02T12%3A00Z%2FP1M&key=natural&value=tree&types=node&measure=count) 




#### Réf

  