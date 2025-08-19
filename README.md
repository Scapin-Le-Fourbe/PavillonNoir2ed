<p align="center">
  <img src="https://i.ibb.co/N6YFyMPx/Background-Scene-Principale.webp" alt="Background Scene Principale" width="900">
</p>

# Pavillon Noir 2e édition - Module pour Foundry VTT
Module Foundry VTT pour le jeu de rôle Pavillon Noir 2ème édition

Ahoy Pirates, Flibustiers et Frères de la Côte ! 

Voici les étapes à réaliser pour installer le module Pavillon Noir 2 ème édition sur Foundry VTT : 
-----------------------------------------------------
SOMMAIRE
-----------------------------------------------------
- <a href="https://github.com/Scapin-Le-Fourbe/PavillonNoir2ed/blob/main/README.md#introduction">Introduction et pré-requis</a>
- <a href="https://github.com/Scapin-Le-Fourbe/PavillonNoir2ed/blob/main/README.md#etapes-installation-module-sur-foundry">Installation</a>
- <a href="https://github.com/Scapin-Le-Fourbe/PavillonNoir2ed/blob/main/README.md#mise-en-place-du-module-dans-votre-monde">Mise en place du module</a>
- <a href="https://github.com/Scapin-Le-Fourbe/PavillonNoir2ed/blob/main/README.md#creer-une-fiche-personnage--pnj--navire">Créer une fiche personnage</a>
- <a href="https://github.com/Scapin-Le-Fourbe/PavillonNoir2ed/blob/main/README.md#items-armes">Les armes</a>
- <a href="https://github.com/Scapin-Le-Fourbe/PavillonNoir2ed/blob/main/README.md#conclusion-et-remerciements">Conclusion et remerciements</a>

-----------------------------------------------------
INTRODUCTION
-----------------------------------------------------
Modules pré-requis et conseillés pour l'installation du module PN 2ed : 

- Custom System Builder 4.4.2 ([https://foundryvtt.com/packages/custom-system-builder](https://gitlab.com/custom-system-builder/custom-system-builder/-/releases/4.4.2/downloads/system.json))
- Requestor (https://foundryvtt.com/packages/requestor)
- Dice So Nice! (https://foundryvtt.com/packages/dice-so-nice)

Pour ceux utilisant les cartes d'escrime, un module pour leurs gestions : 
- Card Hands List (https://foundryvtt.com/packages/card-hands-list)

Testé et créé sous : 
Foundry VTT 12.343
CSB 4.4.2

-----------------------------------------------------
ETAPES INSTALLATION MODULE SUR FOUNDRY
-----------------------------------------------------
1) Télécharger/Dézipper le module "pavillon-noir-2ed"

2) Placer le dossier "pavillon-noir-2ed" dans votre dossier modules de Foundry VTT : 

- Sur Windows : Par défaut, {userData} se trouve dans C:\Users\<VotreNom>\AppData\Local\FoundryVTT\Data\modules

- Sur MacOS : Par défaut, {userData} est dans ~/Library/Application Support/FoundryVTT/

- Sur Linux : Par défaut, {userData} est dans ~/.local/share/FoundryVTT/

3) Installez la police d'écriture AqulineTwo, qui se trouve ici : pavillon-noir-2ed\PavillonNoir\font

4) Créer un monde sous le système "Custom System Builder"

5) Activer le module "pavillon-noir-2ed" dans votre monde.

<a href="https://ibb.co/b5jsB9Wz"><img src="https://i.ibb.co/9HmbT58s/Screenshot-17.png" alt="Screenshot-17" border="0"></a>

-----------------------------------------------------
MISE EN PLACE DU MODULE DANS VOTRE MONDE
-----------------------------------------------------

1) Depuis l'onglet Compendium Packs : 

- Sélectionner le Compendium "Installation Module" puis le fichier "installation Module Pavillon Noir"

- Cliquez sur Execute Macro et laisser l'installation se dérouler quelques secondes, jusqu'a ce que les notifications disparaisse

<a href="https://ibb.co/DDFmrpDs"><img src="https://i.ibb.co/ynCK4SnG/Installation.png" alt="Installation" border="0"></a>

2) Modifier les autorisations d'éxécution des macros depuis la fênetre des macros, sur la gauche de la barre de raccourcis, comme ceci : 

<a href="https://ibb.co/TqPY9VqP"><img src="https://i.ibb.co/dJkj8dJk/Autorisation-Macro.png" border="0"></a>

Avec un clic droit sur le dossier "Macros Pavillon Noir": 

<a href="https://imgbb.com/"><img src="https://i.ibb.co/DHRhRwc7/Autorisation-Macro-02.png" border="0"></a>

Choisissez Owner/Propriétaire

<a href="https://imgbb.com/"><img src="https://i.ibb.co/cS4jMfyf/Autorisation-Macro-03.png" border="0"></a>

Sauvegarder vos changements (Save Changes).

2) Depuis l'onglet Compendium Packs, importer manuellement les items et leurs templates :

- Selectionner le Compendium "Items"
- Glisser les dossiers Template Armes CaC, Template Armes Distances, 01 - Armes CaC et 02 - Armes Distance dans votre onglet items de Foundry

<a href="https://ibb.co/8nKkNszJ"><img src="https://i.ibb.co/RGv8Ybh1/Screenshot-10.png" border="0"></a>


-----------------------------------------------------
CREER UNE FICHE PERSONNAGE / PNJ / NAVIRE
-----------------------------------------------------
1) Depuis l'onglet Actors/Acteur, créer un Acteur, puis séléctionnez le type d'acteur (Fiche Joueur/Fiche Navire/Fiche PNJ) à créer, et rafraîchissez la fiche.

La taille des images pour les avatars sur la fiche Personnage/PNJ : 140x140px
La taille des images pour les avatars sur la fiche Navire : 250x140px

<a href="https://ibb.co/BHCDR1D2"><img src="https://i.ibb.co/HLHvQJvT/Screenshot-23.png" border="0"></a>

<a href="https://imgbb.com/"><img src="https://i.ibb.co/bRCBsSRr/Screenshot-11.png" alt="Screenshot-11" border="0"></a>

PS 1 : Une fois la/les fiches créées, je vous conseille d'actualiser avec F5, pour que tout se mette bien en place. (ex : la bonne limitation de la taille de la fenêtre de la fiche perso)

PS : Si en cliquant sur une des compétences, vous avez "la compétence XXX n'existe pas", passez une des compétences au score de 0, et cela débloquera tous les lancers de compétences. Ceci n'arrive qu'en cas de fiche vierge

-----------------------------------------------------
ITEMS ARMES
-----------------------------------------------------
Si vous souhaitez doter un de vos personnages d'une arme, vous pouvez la glisser déposer depuis l'onglet Items vers la fiche de personnage dans l'onglet combat.

<a href="https://ibb.co/qYrv3K3M"><img src="https://i.ibb.co/QvK43L3F/Screenshot-25.png" border="0"></a>

-----------------------------------------------------
INFOS DIVERSES MJ
-----------------------------------------------------
Maître de jeu, vous avez des macros spécifiques disponibles pour vous aider dans vos parties, les macros sont nommés : 

- Générateur Nom PNJ : Vous donnera un nom et prénom de PNJ aléatoire dans le chat (uniquement visible par les MJ)
- LancerDesEquipagePNJ : Vous permet de faire différents tests inhérents à un groupe type de PNJ que vos joueurs peuvent rencontrer (cf Tableau AFAS p133.)

Depuis la fenêtre des macros (a gauche de la barre de raccourci) vous pouvez cliquez-glissez la macro vers votre barre de raccourci pour l'utiliser.

-----------------------------------------------------
CONCLUSION ET REMERCIEMENTS
-----------------------------------------------------
Je souhaite remercier : 

- Renaud Maroy, créateur du JDR Pavillon Noir, qui nous à honoré d'un travail dantesque et documenté aux limites de l’encyclopédie sur la Marine et le monde de la piraterie. 
- Black Book Editions (BBE) pour l'édition de ce jeu et le travail fabuleux qui a été fait sur les différents livres (si vous avez une version physique pour moi, je suis preneur :D)
- LinkedFluuuush pour la création de son module CSB, sans qui, le portage de multiples JDR n'existeraient pas.
- Le Discord FR de Foundry VTT, spécialement le channel CSB, et à tous ceux qui partagent leur expertise pour aider les débutants à se lancer dans la création et la passion pour le JDR.
- Le Discord FR de Pavillon Noir pour leurs conseils et soutien.
- Amatheus/Mickael, pour ses idées, son aide, son soutien, son approche et aide graphique sur le projet. Son site internet : https://amatheus.fr/
- Lucky/SoLeKalt, pour ses conseils, pour son amour du JDR et sa façon singulière de toujours vouloir me pousser à "le faire", même si ça prends une semaine de plus de taff.
- Aux autres copains et copines (qui se reconnaitront), et qui supportent mon amour pour la piraterie et mes " Hey mais tu savais pourquoi certains pirates portent le cache-œil ?! Alors écoute bien .." à trois heures du mat'

Et merci à vous, d'avoir été jusqu'ici et peut être, fait rêver d'autres personnes dans vos parties, sur cet univers fantastique qu'est le JDR, la piraterie, et la camaraderie.

Si vous voulez m'offrir un café, c'est par ici que ça se passe ;) Merci à tous ! https://ko-fi.com/scapin



