# Système intelligent de prêt de matériel à accès contrôlé — SolidWorks

## Présentation

Ce dépôt est consacré à la **partie mécanique et à la modélisation 3D** de notre projet de prêt de pinces.

L'idée est de concevoir un système capable d'accueillir **48 pinces réparties sur 3 rangées de 16**, tout en permettant de verrouiller et de déverrouiller chaque emplacement de manière individuelle.

Pour le moment, on travaille sur les pièces et les assemblages afin de trouver une solution simple à fabriquer, qui laisse les pinces accessibles uniquement lorsqu'un emprunt est autorisé.

## Ce qu'on cherche à concevoir

- Un support pour les trois types de pinces.
- Un emplacement adapté à chaque pince.
- Un mécanisme de verrouillage pour empêcher le retrait sans autorisation.
- Une fixation pour les servomoteurs et les capteurs.
- Une structure permettant d'intégrer les composants électroniques et l'interface utilisateur.

Ces éléments décrivent le système visé ; ils ne sont pas tous forcément modélisés ou terminés dans les fichiers actuels.

## Fichiers présents

- [`pliers.SLDPRT`](pliers.SLDPRT) : fichier de pièce SolidWorks lié aux pinces.
- [`pliers 1.SLDASM`](pliers%201.SLDASM) : fichier d'assemblage SolidWorks.
- [`Battery - 12V.SLDPRT`](Battery%20-%2012V.SLDPRT) : modèle de pièce nommé « Battery - 12V ».
- [`Zip/`](Zip/) : dossier contenant une archive de travail (`pilier-1.snapshot.2.zip`).

## Ouvrir les fichiers

Les fichiers `.SLDPRT` et `.SLDASM` sont à ouvrir avec **SolidWorks**. Pour un assemblage, il faut aussi garder les fichiers des pièces associées au même endroit afin d'éviter les références manquantes.

Les modèles sont encore en cours de réalisation. On vérifiera ensuite les dimensions, l'assemblage et le fonctionnement du verrouillage avant de considérer la conception comme terminée.

## Documentation et électronique

Les explications du projet, le cahier des charges, le schéma synoptique et les bilans d'entrées/sorties sont disponibles dans l'autre dépôt :

[Voir le dépôt documentation et code](https://github.com/Darkzveller/Doc_Code_conception_et_realisation_d_un_systeme_intelligent_de_pret_de_materiel_a_acces_controle)

## Avancement

Ce dépôt sert à conserver les différentes étapes de la conception mécanique. Il sera complété au fur et à mesure des modifications et des essais réalisés sur le système.
