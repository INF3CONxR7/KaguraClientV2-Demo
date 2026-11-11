# KaguraClient V2 · Démo

**KaguraClient V2** est un client SPRX créé par **AzeY** pour *Minecraft: PlayStation 3 Edition*. Avec WorldEdit, tu peux sélectionner deux coins d’une construction à la hache en bois, puis vider ou remplir toute la zone en une action.

## Installation sur PS3

La notice d’AzeY prévoit une **PS3 avec HEN ou CFW** et trois éléments : `MC.sprx`, le dossier `KaguraClientV2Demo/` et un `EBOOT.BIN` adapté à ton édition du jeu. Le transfert peut se faire par FTP avec WinSCP ou FileZilla, ou par clé USB avec mmCM.

1. Repère ton édition dans le tableau et conserve une copie de ton `EBOOT.BIN` d’origine.
2. Place l’`EBOOT.BIN` prévu pour le client dans le dossier indiqué.
3. Copie `MC.sprx` et le dossier entier `KaguraClientV2Demo/` dans `/dev_hdd0/tmp/`.
4. Lance Minecraft.

| Édition | Dossier de destination de l’EBOOT.BIN |
| --- | --- |
| Europe · numérique | `/dev_hdd0/game/NPEB01899/USRDIR/` |
| Europe · disque | `/dev_hdd0/game/BLES01976/USRDIR/` |
| Amérique du Nord · numérique | `/dev_hdd0/game/NPUB31419/USRDIR/` |
| Amérique du Nord · disque | `/dev_hdd0/game/BLUS31426/USRDIR/` |
| Japon · numérique | `/dev_hdd0/game/NPJB00549/USRDIR/` |

## WorldEdit

Équipe-toi d’une **hache en bois**. Une notification affiche les coordonnées de chaque coin sélectionné.

| Touche | Action |
| --- | --- |
| **L2** | Sélectionner le premier coin. |
| **R2** | Sélectionner le coin opposé. |
| **→** (croix directionnelle) | Choisir `Break` pour supprimer les blocs ou `Place` pour remplir la zone (ID de bloc par défaut : 57). |
| **↑** (croix directionnelle) | Appliquer l’action à toute la sélection. |

La **pelle en pierre**, qui permet de générer des formes, est réservée à l’édition Premium. [Guide WorldEdit en français et en anglais](HowToUseWorldEdit.txt)

## Kaura 4.0

Kaura 4.0 fonctionne ici en mode démonstration. Les actions de combat sur les joueurs sont réservées à l’édition Premium. [Notice de Kaura 4.0](HowToUseKaurav4.0.txt)

## Images personnalisées

Les arrière-plans, bannières et textures de ciel se trouvent dans `KaguraClientV2Demo/`. Pour les afficher, utilise l’édition **numérique** et règle le **HUD sur 1**, comme le recommande AzeY. Dans cette démo, l’édition disque ne prend pas en charge ces images.

Pour **CustomSky**, la résolution maximale est de **2280 × 1520 pixels**. Une image plus grande peut faire planter le jeu.

## Problèmes connus

- **Health Indicator** peut faire planter le jeu avec certaines langues asiatiques. AzeY conseille de passer le jeu en anglais si tu rencontres ce problème.
- Les packs de textures DLC peuvent perturber l’affichage des images personnalisées.

## Crédits et partage

**AzeY** est le créateur du SPRX. Si tu le partages, conserve son crédit. L’auteur interdit de revendre le SPRX ou de le présenter comme ta propre création. [Notice originale d’AzeY](Readme.txt)

Pour signaler un bug ou proposer une amélioration, rejoins le [serveur Discord d’AzeY](https://discord.gg/khBMAnZQcW).
