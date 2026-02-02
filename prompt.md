# Pompt : 

Je suis un formateur pour une école en informatique sous la pédagogie par projet a destination des bachelors et Master. 
Je veux concevoir un module d'architecture de systeme d'information avec du developpement informatique. 

Le but du sujet est de devoir developper un SI WEB multi service afin de répondre a un besoin métier. 


## Construction du sujet : 
Le sujet doit être en multi étape. (Etape 1 à Etape X) de plus en plus difficile et donc doit avoir une evolutivité. 


## Thèmes : 
les themes a aborder sont : 
- Conception d'une architecture en fonction du contexte
- Developpement d'un FRONT 
- Developpement d'une API 
- Mise en place d'une dockerisation
- Mise en place d'un CI/CD


## Choix technologiques : 
Le choix technologique et l'archecture ne sont pas restrients mais le choix de l'archecture doit être justifié. 

Il est minima  attendu : 
- Une architecture bien séparé : FRONT, API, BDD
- Utilisation d'un framwork obligatoire (Ex. backend : ExpressJS, Springboot..., Frontend : ReactJS, VueJS, Angular...)
- Base de donnée principale autorisé : MySQL, PostgresSQL, MongoDB
- La contenairaisation doit être faite via DOCKER et docker-compose pour la gestion mutli service.
- Ne pas refaire la poudre, priviligier l'utilisation de librairies utiles (Design, appel API, gestion d'authentification etc..)
- L'authentification doit être faite sous format JWT.


## Les étapes imaginés : 
 - Etape 1 : Developpement MVP API simple
 - Etape 2 : Developpement MVP Front simple
 - Etape 3 : Mise en place de  la dockerisation 
 - Etape 4 : Mise en place du CI/CD (gitlab)
 - Etape 5 : Complexification du site WEB.
 - Etape 6 : Developpement de services supplémentaires (mail, ELK, Redis, etc..)
 - Etape bonus : Developpement des test unitaires
 - Etape bonus : Mise en production sur un GCP ou Coolify
 - Etape bonus : Mise en place de kubernetes
 - Etape bonus : Mise en place d'un service de gestion de log

## Livrables : 
Les livrables attendus sont : 
- Un document justifiant les choix technologiques choisis ainsi que l'achitecture (avec schema...). 
- Le code source applicatif. 
- La documentation d'installation et d'utilisation

## Autres : 
- Utilisation de design patterns fortement recommandés. 
- Utilisation d'IA pour le developpement est autorisé mais le code généres doit être maitrisé a 100%
- Utilisation de l'IA pour la conception de l'architecture est autorisé, mais seulement en 2ème étape (faire d'abord un premier jet avec documentation)
- Tout doit être commit sur GIT. 
- AUCUN .ENV doit être commit sur le git. 


# Le sujet