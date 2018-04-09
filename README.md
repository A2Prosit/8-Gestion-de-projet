# Prosit 5.8 - Gestion de projet

## Mots clés :

* Prévision
* Temps
* Organiser
* Gestion
* Besoin
* Croissance
* Coût
* Devis
* Déménagement
* Prioritaire
* Étude



## Contexte :
Quoi ?


Gérer un déménagement d’entreprise

Pourquoi?

* Pour que l’entreprise se dvp
* Pour tenir les délais
* Opti les ressources


Comment ?

En réalisant une gestion de projet


## Contraintes :

Temps : 1 mois


### Problématique:
* Comment déménager efficacement à l’aide d’une gestion de projet ?
* Quels sont les outils utilisés pour mettre en place une gestion de projet efficace ?
* Comment planifier un projet ?
* **Comment planifier le déménagement de l’entreprise via une gestion de projet ?**


##Généralisation:
Plannificaton
Gestion des ressources


## Hypothèses:

Définir un temps pour chaque tâche aide pour la planification
Il faut faire des réunions régulières pour vérifier l'avancement du projet
Il existe des outils logiciel pour aider la planification de projet


## Plan d’action:

### **Études :**
### Coûts/Délais/Qualité (trinité)

![](http://www.geek-directeur-technique.com/wp-content/uploads/2012/09/triangle-qualite-cout-delai.jpg)

triangle de la triple contrainte ou triangle de la performance  si on privilégie un c'est au détriment d'un ou des 2 autres


**cycle de vie d'un projet** :

analyse préliminaire
architechture
analyse fonctionnelle
analyse organique
codage
intégration
implantation
exploitation

**SMART**:

Spécifiques
Mesurables
Ambitieux
Réalistes
inscrits dans le Temps

### PERT

Program Evaluation and Review Technique

Représentation chronologique des tâches et de leurs dépendances

On représente chaque activité par une boite et leurs dépendances par des flèches

l'avantage de cette représentation est qu'elle donne la possibilités de délais 

conditions de mise en oeuvre d'un PERT : 

* l'oeuvre doit être div en tâches partielles
* la durée de chaque tâche est connue
* on doit préciser si une tâche doit impérativement être effectuée avant certaines autres tâches

légende :

rond: étape début ou fin d'une tâche. inclut : numéro de l'étape, date au plus tôt, date au plus tard, marge
flèche : étape


### GANTT

planing à barres. Renseigne et situe dans le temps les phases, activités, tâches et ressources du projet.

En ligne, on liste les tâches et en colonne les jours, semaines ou mois. Les tâches sont représentées par des barres dont la longueur est proportionnelle à la durée estimée.

Les tâches peuvent se succéder ou se réaliser en parallèle entièrement ou partiellement.

![](http://www.gestiondeprojet.net/images/gantt.gif)



### Découpage d’un projet

étape 1 : faire l'inventaire des actions à mener

sous forme de tableau : 
lignes = composants créés ou modif par le projet
colones = étapes des différents processus
(en fait c'est le PBS)

étape 2 : enrichir l'inventaire des actions à mener jusqu'à l'inventaire définitif

consulter les acteurs du projet et leur faire valider le tableau
cela nous donne un WBS

étape 3 : choisir à quel niveau de détail on doit définir chaque activité

durée min de chaque activité (10 fois le temps de check les précédentes mais je crois que c est un exemple)
durée max (3fois la période entre chaque point mais peut être un exemple)

étape 4 : finaliser le découpage des activités

apparement on obtient le WBS définitif

étape 5 : chaîner les différents blocs d'activités

pert/gantt : chaîne les activités selon leur dépendances et ajout d'un calendrier. le diagramme montre la subdivision en activités, leur durées, leurs liens e leurs échéances

### WBS/OBS/PBS

**PBS :**
Détaile les composants d'un produit. But est de donner une représentation visuelle des composants d'un produit et leur relations 
On commence par le produit et on le décompose en sous catégories

**WBS : **
Work Breakdown Structure sert d'outil de modé d'outil d'évaluation de la progression du travail. Il permet de découper le travail à accomplir en scetion gérable, ou plus formelement "découpage hiérarchique en livrables spécifiques des travaux à exécuter", chaque niveau permet d'approfondir le détail des tâches jusqu'au niveau final que sont les tâches concrètes à réaliser
Un WBS réponds à la règle des 100% si son niveau le plus haut représente la totalité du projet et les niveaux inférieurs apportent d'avantage de détail 

ex de wbs:
![](http://www.workbreakdownstructure.fr/img-content/wbs-sample-1.jpg)

Structure en arbre où chaque branche est un niveau de décomposition des tâches (précision)

L'application de la règles des 100% donne au chef de projet l'assurance que toutes les tâches requises pour mener à bien le projet ont été prises en compte, qu'il n'y a pas de redondance et que les coûts sont bien justifiés

Le WBS sert à structurer les résultats souhaités avant de passer à la plannification. Bien que les méthodes de travail ou les dates puissent changer au cours d'un projet.

La structure WBS est donc la première étape du processus de planification, dans le sens où il est impossible de décider des méthodes de travail et des échéances avant d'avoir passé en revue tous les résultats souhaités.

construire le WBS :
commencer par un livrable principal (le projet) qui donne lieu à des sous-livrables décomposés à leur tour jusqu'à arriver à des tâches. Les coûts sont ensuite ajoutés, généralement par la compta

régles:

* La structure WBS est donc la première étape du processus de planification, dans le sens où il est impossible de décider des méthodes de travail et des échéances avant d'avoir passé en revue tous les résultats souhaités.
* en principe chaque unitée doit être accomplie en moins de 10 jours
* les unités de travail doivent être indépendantes les une des autres


**OBS :**

Organizational Breakdown Structure schéma représentant les responsabilités de chaque membre pour chaque tâche

![](https://pmhut.com/wp-content/uploads/2009/02/organization-breakdown-structure-obs.jpg)

**Matrice RACI**: indique les rôles et responabilités des membres d'un projet. Elle regroupe le WBS et le PBS

elle donne une vision simple et claire de qui fait quoi dans le projet et permet d'éviter les redondances de rôles

Les lignes de la matrice référencent les activités identifiées, et les colonnes les rôles (personnels impliqués par métier). Dans chaque cellule (rôle) figure la lettre:

* R : responsible <- réalise l'action, il faut au moins 1 R par action
* A : accountable (approbation) <-s'organise comme il veut pour sous traiter aux R mais c'est le responsable de la tâche si elle n'est pas faite c 'est lui qui prends
* C : consulted
* I : informed

### MS Project

corbeille

### **Réalisation :**
### Corbeille
 

config projet :
en manuel si on décale une tâche les antécédents ne sont pas décalés
