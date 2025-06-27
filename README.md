# PavillonNoir2ed
Module Foundry VTT pour le jeu de rôle Pavillon Noir 2ème édition

Bonjour Pirates ! 

Voici les étapes à réaliser pour installer le module Pavillon Noir 2 ème édition sur Foundry VTT : 
-----------------------------------------------------
SOMMAIRE
-----------------------------------------------------
- <a href="https://github.com/Scapin-Le-Fourbe/PavillonNoir2ed/blob/main/README.md#introduction">Introduction et prè-requis</a>
- <a href="https://github.com/Scapin-Le-Fourbe/PavillonNoir2ed/blob/main/README.md#etapes-installation-module-sur-foundry">Installation</a>
- <a href="https://github.com/Scapin-Le-Fourbe/PavillonNoir2ed/blob/main/README.md#mise-en-place-du-module-dans-votre-monde">Mise en place du module</a>
- <a href="https://github.com/Scapin-Le-Fourbe/PavillonNoir2ed/blob/main/README.md#creer-une-fiche-personnage--pnj--navire">Créer une fiche personnage</a>
- <a href="https://github.com/Scapin-Le-Fourbe/PavillonNoir2ed/blob/main/README.md#items-armes">Les armes</a>
- <a href="https://github.com/Scapin-Le-Fourbe/PavillonNoir2ed/blob/main/README.md#conclusion-et-remerciements">Conclusion et remerciements</a>

-----------------------------------------------------
INTRODUCTION
-----------------------------------------------------
Modules pré-requis et conseillés pour l'installation du module PN 2ed : 

- Custom System Builder (https://foundryvtt.com/packages/custom-system-builder)
- Requestor (https://foundryvtt.com/packages/requestor)
- Dice So Nice! (https://foundryvtt.com/packages/dice-so-nice)

Testé et créer sous CSB 4.4.2 et Foundry V12 Build 331

-----------------------------------------------------
ETAPES INSTALLATION MODULE SUR FOUNDRY
-----------------------------------------------------
1) Télécharger/Dezipper le module "pavillon-noir-2ed"

2) Placer le dossier "pavillon-noir-2ed" dans votre dossier modules de Foundry VTT : 

- Sur Windows : Par défaut, {userData} se trouve dans C:\Users\<VotreNom>\AppData\Local\FoundryVTT\Data\modules

- Sur MacOS : Par défaut, {userData} est dans ~/Library/Application Support/FoundryVTT/

- Sur Linux : Par défaut, {userData} est dans ~/.local/share/FoundryVTT/

3) Installez la police d'écriture AqulineTwo, qui se trouve ici : pavillon-noir-2ed\PavillonNoir\font

4) Crèer un monde sous le système "Custom System Builder"

5) Activer le module "pavillon-noir-2ed" dans votre monde.

<a href="https://ibb.co/b5jsB9Wz"><img src="https://i.ibb.co/9HmbT58s/Screenshot-17.png" alt="Screenshot-17" border="0"></a>

-----------------------------------------------------
MISE EN PLACE DU MODULE DANS VOTRE MONDE
-----------------------------------------------------

1) Depuis l'onglet Compendiums : 

- Selectionner le Compendium "Installation Module" puis le fichier "installation Module Pavillon Noir"

- Cliquez sur Execute Macro et laisser l'installation se dérouler quelques secondes, jusqu'a ce que les notifications disparaisse

<a href="https://ibb.co/DDFmrpDs"><img src="https://i.ibb.co/ynCK4SnG/Installation.png" alt="Installation" border="0"></a>

2) Modifier les autorisations d'éxécution des macros depuis la fênetre des macros, sur la gauche de la barre de raccourcis, comme ceci : 

<a href="https://ibb.co/TqPY9VqP"><img src="https://i.ibb.co/dJkj8dJk/Autorisation-Macro.png" border="0"></a>

Avec un clic droit sur le dossier "Macros Pavillon Noir": 

<a href="https://imgbb.com/"><img src="https://i.ibb.co/DHRhRwc7/Autorisation-Macro-02.png" border="0"></a>

Choisissez Owner/Propriétaire

<a href="https://imgbb.com/"><img src="https://i.ibb.co/cS4jMfyf/Autorisation-Macro-03.png" border="0"></a>

Sauvegarder vos changements (Save Changes).

-----------------------------------------------------
CREER UNE FICHE PERSONNAGE / PNJ / NAVIRE
-----------------------------------------------------
1) Depuis l'onglet Actors/Acteur, créer un Acteur, puis séléctionnez le type d'acteur (Fiche Joueur/Fiche Navire/Fiche PNJ) à créer, et rafraichissez la fiche.

La taille des images pour les avatars sur la fiche Personnage/PNJ : 140x140px
La taille des image pour les avatars sur la fiche Navire : 250x140px

<a href="https://ibb.co/BHCDR1D2"><img src="https://i.ibb.co/HLHvQJvT/Screenshot-23.png" border="0"></a>

<a href="https://ibb.co/9kVf62J5"><img src="https://i.ibb.co/W4PdZFQJ/Screenshot-24.png" border="0"></a>

PS : Si en cliquant sur une des compétences, vous avez "la compétence XXX n'existe pas", passez une des compétences au score de 0, et cela débloquera tous les lancer de compétences. Ceci n'arrive qu'en cas de fiche vierge

-----------------------------------------------------
ITEMS ARMES
-----------------------------------------------------
Si vous souhaitez doté un de vos personnages d'une arme, vous pouvez la glisser déposer depuis l'onglet Items vers la fiche de personnage dans l'onglet combat.

<a href="https://ibb.co/qYrv3K3M"><img src="https://i.ibb.co/QvK43L3F/Screenshot-25.png" border="0"></a>

-----------------------------------------------------
INFOS DIVERSES MJ
-----------------------------------------------------
Maître de jeu, vous avez des macros disponibles pour vous aider dans vos parties, les macros sont nommés : 

- Générateur Nom PNJ : Vous donnera un nom de PNJ aléatoire dans le chat (uniquement visible par les MJ)
- LancerDesEquipagePNJ : Vous permet de fairte différent tests inhérents à un groupe type de PNJ que vos joueurs peuvent rencontrer (cf Tableau AFAS p133.)

Depuis la fenetre des macros (a gauche de la barre de raccourci) vous pouvez cliquez-glissez la macro vers votre barre de raccourci pour l'utiliser.

-----------------------------------------------------
CONCLUSION ET REMERCIEMENTS
-----------------------------------------------------
Je souhaite remercier : 

- Renaud Maroy, créateur du JDR Pavillon Noir, qui nous à honoré d'un travail dantesque et documenté à la limite de l'encyclopédie sur la Marine et le monde de la piraterie. 
- LinkedFluuuush pour la création de son module CSB, sans qui, le portage de multiples JDR n'existeraient pas.
- Le Discord FR de Foundry VTT et à tout ceux qui partagent leur expertise pour aider les débutants à se lancer dans la création et la passion pour le JDR.

- Amatheus, pour ses idées, son aide et son approche et aide graphique sur le projet.
- Lucky/SoLeKalt, pour ses conseils, pour son amour pour le JDR et sa façon singulière de toujours vouloir me pousser à "le faire", même si ça prends une semaine de plus de taff.
- Aux autres copains et copines (qui se reconnaitront), et qui supporte mon amour pour la piraterie et mes " Hey mais tu savais pourquoi certains pirates porte le cache-oeil ?! Alors écoute bien .." à trois heures du mat'

Et merci à vous, d'avoir été jusqu'ici et peut être, fait rêver d'autres personnes sur cet univers fantastique qu'est le JDR, la piraterie, et la camaraderie.



