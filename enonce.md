

# Sécurité Web

Le projet sera rendu sur un github ou un gitlab privé, voici mes identifiants pour me partager vos réalisation. Projet à réaliser par 1, 2 ou 3. 

identifiant github: olivier.barais@gmail.com
identifiant gitlab: olivier.barais@gmail.com

Le langage de programmation de la partie backend est de votre ressort, (Java, Kotlin, Scala, Rust, Go, python ou tout autre). Si vous mettez en oeuvre un frontend, même chose framwork de développement libre. 

  * [Exercice 1](#exercice-1)
  * [Exercice 2](#exercice-2)
    + [Exemple 1](#exemple-1)
    + [Exemple 2](#exemple-2)
    + [Exemple 3](#exemple-3)
    + [Exemple 4](#exemple-4)
    + [Exemple 5](#exemple-5)

## Exercice 1

Pour ce TP le premier exercice est d'analyser le code source fourni dans le pdf joint. 

Préparer dans un fichier reponsecodecluedo.md à la racine de votre repository un critique de cette mise en oeuvre au regard de la sécurité. 

## Exercice 2 

Le but du projet est de créer un démonstrateur d'un ou plusieurs problèmes de sécurité Web en mettant en oeuvre un projet avec une faille et le même projet avec un ensemble de contre-mesures. 

Je vous rappelle les [10 problèmes classiques](https://owasp.org/www-project-top-ten/) de sécurité Web. 

### Exemple 1

- Vous pouvez proposer une API Web dont le service interagi avec une base de donnée senseible aux injections SQL
- contre mesure possible, *sanitisation* des entrées ou utilisation d'un framework de mapping objet relationnel

### Exemple 2

- Vous pouvez proposer une API Web dont le service interagi avec le système de fichiers permettre la création de fichier potentiellement malveillant

- contre mesure possible, *sanitisation* des entrées ou utilisation d'un framework de mapping objet relationnel


### Exemple 3

- Vous pouvez mettre en place une petite application Web dont le code est sensible aux attaques XSS.  

- contre mesure possible, *sanitisation* des entrées ou utilisation d'angular, vue.js ou React pour une protection par défaut

### Exemple 4

- Vous pouvez mettre en place une petite application Web dont l'authentification a été mis en oeuvre manuellement avec faiblesse pour la mise en place de règles sur l'authentification

- contre mesure possible, utilisation d'openid connect, déploiement de keycloak pour l'authentification

### Exemple 5

- Vous pouvez mettre en place une petite application Web simple dont tout l'aspect monitoring n'est pas globalisé
- contre mesure possible, mise en place d'une stack ELK et remonté des informations de logs dans un environnement unifié

