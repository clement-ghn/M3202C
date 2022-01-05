On cherche à analyser des résultats sous forme de statistiques comme le nombre de contaminations.
Ces résultats seront basés sur différents modèles (Erdös-Rényi, SIR, Reed-Frost,...).

Le modèle de Erdös-Rényi consiste en un graphe aléatoire dont les nœuds représentent des personnes et les liens des contacts entre les personnes.
L'objectif de ce modèle est de trouver l'instant ‘t’ où le seuil épidémique est atteint.
Le problème majeur de ce modèle est la répartition des liens qui est d'environ 10 liens par personnes or en réalité ces liens sont très homogènes mais très variables.
![Modèle de Erdös-Rényi](http://envoiefess.es/M3202/1.png)

Les points noirs représentent les personnes, les liens en bleus, les contacts sains et en rouge les contacts ayant entraînés des contaminations


Le modèle de SIR est un graphique avec 3 courbes représentant le taux d'infectés, de sains et de retirés, soit le nombre de personnes atteintes du virus, le nombre de personnes pas encore atteintes et le nombre de patients guéris.
Ce modèle s'intéresse plus au taux de reproduction R0.
Au début de l’épidémie, l’expression de R0 est β/γ puisque 1/γ représente la durée moyenne de la maladie et qu’au début, les personnes rencontrées sont presque toutes saines.
β représente le taux de transmission, et γ le taux de guérison.
Il est considéré avec le modèle SEIR (qui prend en compte les morts) comme les meilleurs modèles existants sans trop de limites.
![Courbes](http://envoiefess.es/M3202/2.png)

On a trois courbes de couleurs différentes représentant les trois états possibles d’une personne.
La somme fait donc 1 car l’axe des ordonnées représente la proportion de population par états soit Saines, Infectées, Retirées. Ces courbes agissent en fonction du taux de transmission β et du taux de guérison γ.

Le modèle de Reed-Frost qui est un des premiers modèles existants il s'agit d'un ancêtre du modèle SIR.
Il reprend les mêmes termes et arguments, Sains, Infectés, Retirées et R0.
Néanmoins, il s'intéresse uniquement à la proportion de personnes infectées.
![Simulations](http://envoiefess.es/M3202/3.png)

On a ici une représentation des résultats de 10 000 simulations du modèle de Reed-Frost, le nombre de simulations(ordonnée) et les résultats, soit  la proportion des infectés (abscisse).
