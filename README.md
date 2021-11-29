
# M3202C Informatique 2021/22 - Modélisations mathématiques
# IUT de Saint-Dié-des-Vosges 
![LogoUL](https://cdn.discordapp.com/attachments/905110065919426633/913738803737411594/ul.png "LogoUL")
### Sommaire : 
1. Groupe
2. Présentation du sujet
3. Comptes-rendus
4. Nos travaux
5. Sources




## Groupe:
- ABEL Loïc 
- DEMATINI Loris
- GEHIN Clément

## Sujet: Comment éviter la propagation des épidemies grâce aux aspects mathématiques
#### Présentation succincte :
Une épidémie est l'apparition la propagation d'une maladie infectieuse contagieuse qui frappe en même temps et au même endroit un grand nombre de personnes.
Cette épidémie est toujours accompagnée de statistiques d'un point de vue infectieux (nombre d'infectés, âges touchés, taux de contamination, taux de mortalité, ...) ou vis à vis du remède (statistiques de soins, nombre de guéris, réinfectés ?, ...).
Ces modélisations, graphes, etc vont pouvoir être interprétés et travaillé par des chercheurs ou statisticiens afin de comprendre au mieux l'épidémie et la combattre plus efficacement.
C'est ce que nous essayerons de définir au fil du blog afin de répondre à la question posée:
**"Comment éviter la propagation des épidémies grâce aux aspects mathématiques ?"**.

## Compte-rendu des séances
**Séance 1 :**

Lors de cette première séance, nous avons dû constituer notre groupe pour ce module. La composition du groupe a été rapide, et nous avons ensuite pu prendre de l'avance pour la suite du module. Nous avons alors pris connaissance des sujets présentés par nos camarades des années précédentes.

**Séance 2 :**

Cette séance nous a permis de nous concentrer sur le choix de notre sujet. En effet, après concertation, plusieurs projets réalisés les années précédentes ont retenu notre attention, notamment "Les aspects mathématiques dans la propagation des épidemies" ainsi que dans le "jeu d'échecs". Ce dernier étant déjà choisi par un autre groupe, nous nous sommes documentés sur la propagation des épidemies. Les sources d'informations trouvées nous semblaient riches et variées, et c'est pour cette raison que notre présentation portera sur **Comment éviter la propagation des épidemies grâce aux aspects mathematiques**.

**Séance 3 :**

Lors de ce TP, nous avons commencé nos premières recherches afin d'approvisionner la présentation détaillée de notre sujet.
Dans le même temps, l'un de nous trois a rédigé le planning prévisionnel ci-dessous.

![PlanningPrevisionnel](https://gameosu.s-ul.eu/ZJpZKIHy)

**Séance 4 :**

Au cours de ce TD, nous avons été au coeur des articles intéressants sur notre sujet et nous avons alors décidé de les décortiquer afin d'en extraire le plus d'informations possibles. Nous nous sommes donc partagé le travail et avons récolté nos données à partir d'interviews, de blogs, d'articles de journaux, ... les données ne manquent pas étant donnée la situation actuelle.

**Séance 5 :**

Dans un premier temps durant ce TP, nous avons travaillé sur la création de l'affiche. Après études des différentes affiches des années précédentes, nous avons listé les éléments récurrents et nécessaires sur nos affiches. Nous avons alors créé une première ébauche de poster.
En parallèle, nous avons continué d'analyser nos sources et d'extraire les informations utiles. Nous avons alors pu commencer à alimenter la partie nos [Travaux](#travaux) 


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


## Sources

- http://images.math.cnrs.fr/Modelisation-d-une-epidemie-partie-1.html 
- https://scienceetonnante.com/2013/02/25/propagation-depidemies-et-graphes-aleatoires/
- https://culturemath.ens.fr/thematiques/mathematiques-appliquees/propagation-d-epidemies

