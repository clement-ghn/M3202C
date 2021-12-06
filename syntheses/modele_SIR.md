## Travaux


Synthèses expliquant comment faire une modélisation 
Pour les États connaître l’évolution d’une épidémie humaine, animale ou végétale est primordial.
Cette étude permet en effet de prédire l’évolution de la maladie au cours du temps et a pour but principal de guider les dirigeants dans la prise de décision.
Le modèle SIR :
modèle à compartiments, on divise la population en plusieurs catégories (Sain, Infectés, Retirées)
le modèle SIR ne s’occupe pas directement de prédire la mortalité de l’épidémie, pour cela il faut un autre modèle : le modèle SEIR

![Formule](http://images.math.cnrs.fr/IMG/png/schema_sir.png)

Ici, β représente le taux de transmission, et γ le taux de guérison. Mathématiquement, le modèle SIR est donné par le système suivant :

![Formule2](https://cdn.discordapp.com/attachments/905110065919426633/913743028726951966/unknown.png)
![Formule3](http://images.math.cnrs.fr/IMG/png/schema_sir_vac.png)

La politique de vaccination visant à vacciner 100% de la population est quasiment impossible : il faut donc trouver le bon équilibre pour vacciner une partie de la population assez importante pour ralentir, puis arrêter l’épidémie. C’est ce qu’a permis le modèle SIR.

Le taux de reproduction R0 est le nombre moyen de cas secondaires produits par un individu infectieux au cours de sa période d’infection.
Au début de l’épidémie, l’expression de R0 est β/γ puisque 1/γ représente la durée moyenne de la maladie et qu’au début, les personnes rencontrées sont presque toutes saines.
Ce taux peut être abaissé par des mesures comme la distanciation sociale, le confinement ou la fermeture de certains lieux.

![Graphique](http://images.math.cnrs.fr/IMG/png/comparaison_trans.png)
Comparaison du pic en modifiant le taux de transmission
Le taux de transmission est de 0,9 à gauche et de 0,2 à droite. Le taux de guérison est fixé à 0,1.


- 2 simulation interactive (à coder dans notre sujet)



Un petit programme SIR permet de tracer l'évolution des populations S, I et R en fonction du temps. Selon les valeurs des paramètres α et r, les comportements sont complètement différents : si α est trop élevé par exemple, les individus infectés meurent presque tout de suite et n'ont pas le temps d'en infecter beaucoup d'autres. Voici un exemple d'évolution des populations au cours du temps, obtenu avec SIR pour les valeurs r=4 et α=2.

![Graphique2](https://cdn.discordapp.com/attachments/905110065919426633/913746859359608882/simu0.png)
