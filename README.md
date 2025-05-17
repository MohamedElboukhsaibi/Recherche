Introduction : 

Ce projet de recherche explore les méthodes de régression fondées sur les différences d'observations, une approche souvent utilisée pour atténuer certains biais dans les données temporelles ou structurelles. L'étude se focalise à la fois sur l'aspect historique et théorique (notamment avec l'estimateur de Theil-Sen), et sur une analyse empirique à l'aide de techniques modernes de machine learning.

L’objectif principal est de déterminer si raisonner par différences (ex. : $\Delta y_t = y_t - y_{t-1}$) permet de réduire l'erreur absolue moyenne (MAE) dans des modèles de régression, par rapport à une modélisation classique sur les niveaux.

Objectif : 

Étudier l'origine et les fondements théoriques des méthodes basées sur les différences.

Revisiter l'estimateur de Theil-Sen et d'autres approches robustes.

Comparer, via des expérimentations, les performances prédictives :

Régression sur les niveaux.

Régression sur les différences.

Évaluer l’impact sur des métriques comme la MAE et la RMSE.

Méthodologie : 

Revue historique et bibliographique

Études classiques en économétrie (ex : séries temporelles, différences premières).

Estimateur de Theil-Sen et méthodes robustes.

Applications connues en économie et en physique.

Modélisation machine learning

Données simulées et/ou réelles (détails dans le dossier data/).

Prétraitement : normalisation, différences premières, etc.

Modèles utilisés : Régression linéaire, Random Forest, Gradient Boosting, etc.

Comparaison des performances avec/sans transformation en différences.

Évaluation

Métriques : MAE, RMSE, R².

Validation croisée et analyse des résidus.

Objectifs : 

Ce projet vise à répondre aux questions suivantes :

Les transformations en différences améliorent-elles systématiquement les performances ?

Quels types de modèles en tirent réellement avantage ?

Dans quels contextes (stationnarité, tendance, bruit) ces transformations sont-elles bénéfiques ?

Auteur : 

Projet de recherche développé par El boukhsaibi Mohamed & Gerart Jarod, dans le cadre d’une étude universitaire.
