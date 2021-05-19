---
title: Nextcloud
description: 
published: true
date: 2021-02-24T14:38:10.256Z
tags: 
editor: undefined
dateCreated: 2021-01-04T16:09:06.092Z
---

[Nextcloud](https://nextcloud.com/) est la meilleure pour ne pas dire la seule alternative libre à Google Drive (plateforme de stockage en ligne et de création de documents).

Mais plus qu'une alternative à Google Drive, il s'agit d'une plateforme permettant de partager et de collaborer sur des documents / tableurs / présentations / cartes géographiques ou heuristiques, de gérer et partager des calendriers, de créer des formulaires / sondages, de discuter par vidéo. Tout ça sans fuite de données.

# Connexion

Comme la majorité des outils, Nextcloud est une application accessible depuis le [portail](/outils-numeriques/le-portail) duquel il faut être connecté.

# Les fonctionnalités

Pour accéder aux autres fonctionnalités, il faut y accéder à l'aide du menu à gauche.


## Fichiers

Une fois connecté, vous arrivez par défaut dans votre espace de stockage dans lequel vous allez non seulement pouvoir créer des documents afin de les partager au collectif mais aussi accéder aux répertoires publics où dont vous avez accès, de par votre appartenance à un cercle précis.
Vous pouvez aussi y accéder en cliquant sur l'élément **Fichiers** du menu.

### Créer un fichier

Pour créer un document, naviguez dans les dossiers déjà créé si vous le souhaitez puis cliquez sur le bouton **+** :
![menu-contextuel-fichiers-add.png](/outils/menu-contextuel-fichiers-add.png)

- **Nouveau dossier**: permet de créer un répertoire. Il est important pour garder l'espace de stockage ordonné de porter une attention au fait de placer les fichiers aux bons emplacements. Ainsi, il faut faire attention aux excès (trop ou pas assez) de structure

- **Nouveau document texte**: permet de créer un document en utilisant le [langage balisier Markdown](https://fr.wikipedia.org/wiki/Markdown). Attention, Markdown est apprécié par les initiés mais peut être déroutant, si vous ne connaissez pas Markdown, vous préférerez certainement le lien Nouveau document qui ressemble plus aux logiciels type Office (Word, Writer etc).

- **Nouvelle mindmap**: permet de créer des cartes heristiques

- **Nouveau document**: vous connaissez les suite Office (MSOffice ou LibreOffice par ex), c'est l'équivalent de Word ou Writer, idéal pour prendre des notes ou pour créer des documents type **odt/doc**

- **Nouvelle feuille de calcul**: vous connaissez Excel ? C'est globalement pareil, ça permet de manipuler des données tabulaires, des chiffres, faire des calculs et créer des graphiques.

- **Nouvelle présentation**: un équivalent léger de PowerPoint. Attention, l'outil est très minimaliste aussi il est déconseillé de l'utiliser pour des besoins avancés.

- **New Whiteboard**: le terme est en anglais mais il permet de réaliser des dessins collaboratifs. Peut être utile pour réaliser des petits schémas rapides. Attention, l'outil est très minimaliste, pour des besoins plus complexes, préférez un outil externe comme par exemple https://excalidraw.com/ (*d'ailleurs, une intégration d'excalidraw est en cours, il faut être patient*)

### Partager un fichier

[Cette page](https://docs.nextcloud.com/server/latest/user_manual/fr/files/sharing.html?highlight=cercles) de la documentation de Nextcloud explique très bien cette partie

## Activité

Il s'agit des actions réalisées précédement sur vos fichiers. Ça peut être vous ou les personnes qui ont la permission de faire des modifications.

## Discussion

Il s'agit d'une application de messagerie instantanée intégrée :
![nextcloud-talk.png](/outils/nextcloud-talk.png)

Rejoignez ou créez des discussions publiques ou privées avec les membres de Gétigné Collectif et cliquez sur le bouton **Commencer l'appel** à partir d'une conversation pour organiser une visio. Attention, s'il y a beaucoup de personnes, il est recommandé de ne pas allumer les caméras sous peine d'expérimenter des dysfonctionnements.

Si vous rejoignez un appel, il vous sera demandé d'autoriser le navigateur ou l'application à utiliser le micro et la caméra les cas échéants. Selon votre navigateur, si vous n'avez pas ou plus cette demande d'autorisation, vous pouvez suivre la procédure, , sur [Firefox](https://support.mozilla.org/fr/kb/gerer-permissions-camera-et-microphone), [Google Chrome](https://support.google.com/chrome/answer/2693767?co=GENIE.Platform%3DAndroid&hl=fr), [Microsoft Edge](https://support.microsoft.com/en-us/windows/windows-10-camera-microphone-and-privacy-a83257bc-e990-d54a-d212-b5e41beba857).

## Contacts

Un annuaire des membres de Gétigné Collectif. Idéal pour se contacter et utilisé par les applications Nextcloud comme Fichiers, Agenda, Discussions, Cercles etc..
[Plus d'infos ici](https://docs.nextcloud.com/server/latest/user_manual/fr/pim/contacts.html)

## Cercles

Les cercles permettent de créer des groupes de travail afin de faciliter [le partage de fichiers](https://docs.nextcloud.com/server/latest/user_manual/fr/files/sharing.html?highlight=cercles) ou l'attribution de permissions groupées.

## Agenda

Il s'agit d'une application permettant d'avoir des agendas partagés entre les membres et les cercles. On y retrouve toutes les fonctionnalités de bases comme le fait de créer des événements, occasionnels ou récurrents, d'y inviter des personnes, d'y définir un lieu, d'y générer un lien visio (outil Discussion), d'y définir la confidentialité de l'événement, de s'abonner au calendrier d'un autre membre ou d'un cercle au sein de Nextcloud ou d'une application spécialisée par exemple.

[Plus d'infos ici](https://docs.nextcloud.com/server/latest/user_manual/fr/pim/calendar.html)

## Formulaires

Nextcloud intègre une fonctionnalité permettant de réaliser des formulaires simples, idéal pour organiser un sondage et collecter des avis sur un sujet particulier.

Exemple:
![nextcloud-form.png](/nextcloud-form.png)

Les réponses au formulaire apparaissent en cliquant sur le bouton **Réponses** et peuvent être exportées au format csv :
![nextcloud-form-responses.png](/nextcloud-form-responses.png)

# Logiciels et applications

> Dans chaque logiciel ou application, le vocabulaire peut varier selon les interfaces mais il faudra choisir de se connecter sur une instance personnelle, ou auto-hébergée. La première chose qui vous sera demandé sera l'adresse de notre serveur nextcloud à savoir :
> 👉 **https://portail.getigne-collectif.fr/cloud**
{.is-info}

## Synchroniser les fichiers 

Ensuite, il faut entrer les identifiants qui vous ont été fournis 

### Sur ordinateur

Synchronisez, gérez vos fichiers facilement, recevez des notifications directement depuis votre ordinateur sous Linux, Windows ou Mac en installant le logiciel NextCloud :
https://nextcloud.com/install/#install-clients

### Sur mobile ou tablette

Sur un terminal Android (smartphone et tablettes) ou iOs (iPhone et iPad), il est possible d'installer l'application Nextcloud :

- <a target="_blank" href="https://play.google.com/store/apps/details?id=com.nextcloud.client">
  <img class="img-responsive" src="https://nextcloud.com/wp-content/themes/next/assets/img/clients/buttons/googleplay.png?x53054"></a>
- <a target="_blank" href="https://itunes.apple.com/us/app/nextcloud/id1125420102?mt=8">
  <img class="img-responsive" src="https://nextcloud.com/wp-content/themes/next/assets/img/clients/buttons/appstore.svg?x53054">
</a>

Et si vous êtes un petit•e champion•ne et que vous êtes sortis de Google et Facebook pour l'installation de vos applications, vous pouvez aussi passer par F-Droid 🎉 <a target="_blank" href="https://f-droid.org/packages/com.nextcloud.client/">
  <img class="img-responsive" src="https://nextcloud.com/wp-content/themes/next/assets/img/clients/buttons/fdroid.png?x53054">
</a>

> Si, pour le travail, pour une autre association ou simplement côté perso, vous avez un accès à un autre Nexcloud, sachez que l'application permet d'ajouter autant de comptes que vous le souhaitez. 
{.is-info}
