# neural-network-TP

Travail pratique sur les réseaux de neurones. Réalisé durant le Bsc. à la He-arc.

Trois datasets proviennent d'un projet effectué par l'équipe de RaD de la HE-Arc. Ils sont tous les trois des séries temporelles.
Le dataset choisi pour ce projet est *Digester*.

L'objectif principal avec ces données est de prédire une valeure dans le future. C'est une tâche de régression, plus d'information sur les metrics à utiliser ici:

- [scikit-learn](https://scikit-learn.org/stable/modules/model_evaluation.html#regression-metrics)

## Digester

Un digester est une usine qui produit du papier ou carton à partir du bois.

### Description des données

Nom du fichier: `digester_data.csv`

Il y a environ un mois de données dans ce fichier (5968 lignes).
Les données sont enregistrées toutes les 10 minutes.

Il y a 37 colonnes dans ce dataset. Ce sont toutes des mesures provenant de capteurs dans l'usine.  
La plus improtante est `Blow Kappa` qui mesure la qualité de la production.  
**L'objectif est de prédire ce `Blow Kappa` en utilisant les autres capteurs.**  
