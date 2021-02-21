
# Lexique du vocabulaire du Web

Ce Fichier a pour but de répértorier les différents mots et conceptes en rapport avec l'apprentissage effectué la première semaine de formation.
Il pourra être étoffé par la suite et servira de rappel en cas de nécessité.
Vous trouverrez donc a liste des termes récupant dans le lexique ainsi qu'un détail dans les rubriques suivantes. 



## Lexique

Vous trouverez ici la liste des termes employés dans le domaine du web ainsi que leurs définitions.

- **Back-end** : La partie invisible pour l'utilisateur
- **Base de données** : 
- **CSS** : *Cascading Style Sheets* Language front-end utilisé pour mettre en Pages le code HTML
- **Client** : 
- **Framework** : 
- **Front-end** : La partie graphique visible par l'utilisateur
- **git** : Logiciel de versionning
- **github** : Logiciel de gestion et plateforme de gestion de sauvegarde de projets- **Internet** : Réseau reliant plusieurs machine afin d'échanger des données
- **HTML** : *Hypertext Markup Language* Language front-end utiliser pour gérer les liens entre les pages du web
- **HTTP** : *Hypertext Transfert Protocol* Protocole utilisé pour communiquer sur le Web
- **intégration** : Principe de "fusion" des différents languages du Web
- **Javascript** : Language front-end utiliser pour dynamiser une page web
- **ligne de commande** : Ensemble de caractères envoyé dans un terminal pour communiquer avec la machine 
- **Markdow** : Language de traitement de texte, ce fichier est rédigé en Markdown
- **PHP** : Language de script orienté objet, conçu pour le développement d'application web
- **Serveur** : 
- **SQL** : 
- **Terminal**": Interface utilisateur en lignes de commandes
- **URL** : 
- **Web** : Servie interne à internet de consultation de pages HTML




## Pour aller plus loin
 
Cette rubrique permet d'approfondir certain concepte et sera étoffé au fil de la formation.


### Le Back-End

Le back-end est la partie invisible à l'utilisateur, elle comprend les applications web, les bases de données, les serveur d'hebergements.
Pour développer cela il existe différents language, tels que **PHP**, **SQL**, **Ruby** ou encore **Python**.
Comme pour le front-end le développeur back-end peut utiliser différents Framework dans le même but visé, gagné du temps.


### Le Front-End

Le front-end est la section destiné à l'affichage utilisateur, la partie graphique en somme.
Elle comprend donc le **HTML** *(HyperText Markup Launguage)*, le language permettant de créer les liens entre les pages, le **CSS** *(Cascading Style Sheets)*, le language permettant la mises en pages 
du language HTML et le **JavaScript**, un language orienté objet permettant de dynamiser les pages web.
C'est au développeur front-end que revient le rôle d'intégrer les différents languages dans le code HTML, afin de rendre l'expérience utilisateur la plus fluide possible tout en respectant le 
cahier des charges imposé par le client.
Le développeur front-end a à disposition différents Framework (jQuery, Bootstrap...etc) lui permettant de gagné du temps dans le dévoppement.

### git/github

- **git** : git est un logiciel de versionning permettant de sauvegarder l'historique de modification d'un projet. 
Cela permet de pouvoir rapidement identifier les différents changements effectués afin de revenir à une version précédente en cas de besoin.
Il est très utile car permet de travailler avec un système de branches, permettant à chaques développeurs du projet de travailler de manière indépendante.
	 

- **github** : Github est un logiciel et une plateforme web permettant grâce à un systeme de "pull" et de "push" de déposer les différentes versions du code des projets en cours.
	 
#### Utilisation et commandes

- **git init** : initialise la détection de git
- **git status**: Etat de git, permet de voir les modifications apporté aux fichiers
- **git add -A**: ajoutes tout les fichiers en zone de staging pour préparer un commit
- **git commit -m "message"** : procéde à un commit, c'est à dire une sauvegarde de l'historique et y ajoute un message
- **git log** : permet d'afficher la liste des commit
- **git diff** : affiche les différences entres commit
- **git branch** : voir la branche de travail
- **git branch dev** : créé une nouvelle branche dev, (le dev peut être changé par le nom souhaité)
- **git checkout dev** : quitte la branche actuelle vers la branche dev
- **git push origin dev** : envoi le commit vers github, sur le serveur origin, dans la branche dev
- **git pull origin master** : récupère depuis github, sur le serveur origin, dans la branch master
- **git merge dev** : Fusionne la branch dev dans la master

Donc pour résumé, afin de maintenir un espace de travail sur, on commence par vérifier l'état de git *(git status)*, puis on prépare les fichiers pour le commit *(git add -A)*,
on fait le commit *(git commit -m "mon message")* et on affiche les log *(git log)* pour être assuré que cela fonctionne.
Il ne reste plus qu'à faire un **push** vers git hub pour mettre à jour la branche de travail *(git push origin dev)*.
On pourra enfin faire un **pull request** depuis github afin de mettre à jour la branche master et la récupérer avec un **git pull** vers notre branche dev afin de travailler sur une branche saine.



### Le modèle client/serveur/base de donnée

Afin de naviguer sur le web, les utilisateurs doivent passer par différentes étapes de transmission de l'information:


Le client est le navigateur Web, il interprète le code HTML, CSS et Javascript pour rendre un affichage dynamique à l'utilisateur.
A l'aide du protocole **HTTP** (Hypertext Transfert Protocol), le client envoi des requêtes via internet à des serveurs physique, mises à disposition par un hébergeur.
Le serveur interprète alors le language back-end *(PHP)* et envoi une requête à la base de données.
La base de données renvoi alors les informations au serveur *(SQL)* qui renvoi à son tour une page web dynamisé via internet jusqu'au client qui affiche la page à l'utilisateur.

 
