---
layout: documentation
hide_hero: false
hero_image: "placeholder.png"
hero_darken: true
image: "placeholder.png"
component_toc: true
doc_header: true
type: tutorial

title: Tutoriel Devis
subtitle: Suivez ces étapes pour faire une Devis
description: Ce tutoriel explique les étapes de base pour réaliser une Devis.
author: Looij Dylan

time: 2
difficulty: 1
compatibilities-os: win, mac, lin

prerequisites:
  - label: Excel
    link: ""

softwares: 
  - label: Excel
    link: ""

hardwares: 
  - label: Win
    link: ""

todo: 100
---
# le devis

## Introduction
Lorseque l'association souhaite effectuer une préstation, elle se doit de faire une démarche d'au moins 3 documents

1. devis
2. bon pour commande
3. facture

cela permet de proteger l'association dans des cas précis comme une analyse des financiere, reclamation client, ectect.


{% include message.html title="Défintion: Devis" message="> État détaillé, établi par les fournisseurs, des travaux à exécuter, dans lequel on indique les modalités de leur exécution, la nature, la dimension et le volume des matériaux à utiliser, le prix de chacun et l’évaluation de la dépense totale -Dictionaire de l'Académie française" status="is-info" icon="fas fa-info-circle" %}
https://www.dictionnaire-academie.fr/article/A9D2245


{% include message.html title="Défintion: Facture" message="> Mémoire établi par le vendeur, dans lequel sont détaillés la nature, la quantité, le prix des marchandises livrées ou des services fournis -Dictionaire de l'Académie française" status="is-info" icon="fas fa-info-circle" %}


## Comment faire une devis
Sur le drive, dans la partie administration, aller dans Fichier->Finances->Gestion comptable> aide_Facture et faire "copier dans".

diriger le vers les finances de l'année actuelle.

Rennomez la DEVIS|Année|mois|jour|-|numéro

Le numéro s'incremente si vous faites plusieurs devis le même jour.

Ouvrez ce fichier pour completer le devis:

* ZONE A :
    Ref : la référence du devis. C’est la même que le nom de fichier (voir plus haut)
    Date : la date à laquelle vous éditez votre devis
    Date d'échéance : elle est calculée automatiquement. Ne pas changer
* ZONE B :
    Complétez avec l’adresse complète du client. Si nécessaire rajouter le nom du contact, un téléphone et une adresse mail si vous l'avez.
* ZONE C :
    Indiquez les différentes prestations réalisées
    Indiquez le Prix Unitaire HT
    Indiquez la quantité

{% include message.html title="ATTENTION" message=" laissez la TVA à 0% car vous êtes une association et la TVA est non-applicable (article 293 B du CGI)" status="is-danger" icon="fas fa-exclamation-triangle" %}

* ZONE D :
    Vérifiez le total avant de générer le devis

## Le resultat

Vous enverez le devis sous format PDF



# Le bon pour commande

## a quoi sert t'elle?

le bon pour commande sert de confimation pour les 2 parties que la commande a bien été lancée et ne peut plus etre annulée (sauf cas exceptionnel)
c'est le client qui signe le devis avec ecrit bon pour commande, la date, et le lieu.
Vous pouvez aussi joindre ce document au devis pour avoir plus propre.
[Bon pour commande](./Template-Bon-pour-accord.pdf)

<embed src="./Template-Bon-pour-accord.pdf" type="application/pdf" width="600" height="400">



