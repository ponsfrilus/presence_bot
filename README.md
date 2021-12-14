# Cahier des charges  
![](https://i.imgur.com/4u4tx9r.jpg)

## Contexte 

Personne ne veut se retrouver seul par surprise sur le site de l'EPFL. La plupart des apprentis sont confrontés à une perte de motivation lorsqu'ils sont dans cette situation. On peut pourtant préciser si on fait du télétravail dans absences.epfl.ch, seulement voilà : informer ces collègues de sa présence tous les jours peut être chronophage ou encore peu pratique pour certaines personne. 

## Objectif 
C'est la raison pour laquelle nous avoir eu l'idée de ce bot. Le but étant de faciliter la communication des présences sur site des membres de IDEV-FSD.

### KSP
* Extrêmement rapide d’utilisation
* Ui minimaliste
* Utilisable n’importe quand et n’importe ou 

### Fiche signalétique
> Nombre d’utilisateur simultané : **1 personne**
> Personne cible : **Membres IDEV-FSD**
> Prix : **Gratuit** 
> Plateforme : **Telegram(app & browser)**
> Language de programmation : **JavaScript**
> Dépendance : **telegraf, nodeJs** 

## Description fonctionnelle des besoins
#### Mettre à jour les informations du planning :
* Image
* Tableau à double entrée  
#### Afficher les boutons :
* Inline command
* Telegraf  
#### Utilisation des boutons :
* Inline command 
* Telegraf  
#### Telegraf :
* Afficher les boutons
* Utilsation des boutons

## Délais
**17 Décembre 2021**

# MakeFile 

## build:
> docker-compose build 

## run:
> docker run -it botpresence bash

## start:
> docker-compose up --build botpresence

## stop:
> docker stop botpresence:latest

## kill:
> docker kill $$(docker ps)
