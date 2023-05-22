# Préparation au brief 6

## Site Web et application DSI sensibilisation au handicap dédié au professionnels.

Après avoir modifier la maquette de landing page sur les recommandations du client (DSI) et de l'ux/ui designer (Pierre), vous devez mettre en place les étapes de collaboration à la gestion du projet et à l’organisation de l’environnement de développement pour le futur site et la future application qui permettra à DSI d'animer ses ateliers de sensibilisation au handicap. 

Retour par groupe du formateur après vos rendus sur Simplonline.
En tant que concepteur développeur d'application, en prenant en compte les besoins du projet et les compétences de chaque individu de votre groupe vous devrez :
- Désigner un chef de projet pour votre groupe,
- Lister les fonctionnalités de la future application,
- Penser à la conception de la future base de données,
- Mettre en place un workflow,
- Concevoir une application.


->UML et MLD de la base de données
->Use Case
->Github (branches et gestion des conflits)
->User flow
->Wireframe
->mind map
->Trello ou Jira (attribution des tâches et décomposition des fonctionnalités en US)
->Compte rendu de vos échanges oraux ou écrits avec le client
->Délimitation du MVP et anticipation des futurs évolutions du projet

### UML et MLD de la base de données

**UML**:

**Diagramme de classe**:
[UML 2 - de l'apprentissage à la pratique](https://laurent-audibert.developpez.com/Cours-UML/?page=diagramme-classes)

Pensez à l’**héritage** quand vous pouvez en faire:
[Héritages (MCD/MLD)](https://help.sap.com/docs/SAP_POWERDESIGNER/856348b84a7c479489d5172a630f014d/c7c34d286e1b1014afdcc9aecdb28247.html?version=16.7.01)

**MLD**:
Base de données SQL (voir Google doc)

### Use case

Imaginez que vous essayez d’expliquer le fonctionnement d’une application à quelqu’un, c’est assez difficile de faire comprendre l'interaction entre l’application et l’utilisateur. 
C’est à cela que servent les Diagrammes de Use Cases.
Ils permettent d’expliquer facilement les interactions et les relations entre différentes entités. 

#### Les composants des diagrammes use case

SYSTEMS (site web, composant logiciel, une application etc…) 
ACTORS (quelque chose ou quelqu’un qui utilise le système)
USE CASES (action à définir)
RELATIONSHIPS (interactions)

<p align="center" width="100%">
    <img width="80%" src="img/composants_use_case1.png">
</p>

##### Systems

<p align="center" width="100%">
    <img width="80%" src="img/composants_use_case2.png">
</p>

##### Actors

PRIMARY ACTORS / Acteur principale, il initie l’utilisation du système 
SECONDARY ACTORS / Acteur secondeur réagit

##### Exemple d’un cas simple pour application bancaire

On veut qu’il y est la possibilité de :
- se connecter
- vérifier l’argent qu’on à sur le compte
- faire un transfert avec un autre compte
- faire des paiements

Qui sont les acteurs?

<p align="center" width="100%">
    <img width="80%" src="img/composants_use_case3.png">
</p>

#### USE CASES / Cas d’utilisations

Les uses cases décrivent ce que fait le système.

Ils sont définis par un oval et représentent une action qui accomplit une tâche du système. 

<p align="center" width="100%">
    <img width="80%" src="img/composants_use_case4.png">
</p>