Ce code à pour but d'étudier le fonctionnement du "DxO Selective Tones".

Pour cela, plusieurs dossiers sont disponibles, hierarchisé de la même manière que la diapositive préssenté lors de la soutenance :

- exploration : première approche de l'outil pour comprendre brièvement la réponse du système selon l'entrée donné
- checkerboard : permet d'étudier si le système réagit selon un patch, ou pixel par pixel
- invariance : à pour but de comprendre quelles sont les métriques utilisées par le système
- greys : vise à quantifier puis reproduire l'état de sortie de l'outil selon une nuance de couleur sur 1, 2 ou 3 canaux.
- reverse_engineering : reproduit l'outil pour le paramètre "high tones" 

L'étude a donc porté dans un premier temps sur le système pour comprendre son fonctionnement sur les "high tones", "middle tones", "shadow tones" et "blacks", puis nous avons réimplémenté le système sur les "high tones". Un travail similaire peut enssuite être fait sur les autres tons.