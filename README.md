# XDK Chest Counter — téléchargements

<img src="logo.png" alt="XDK Chest Counter" width="110" align="right">

Logiciel Windows (10 et 11) **gratuit** de **XDK TEAM DEV** qui **compte les coffres que tu ouvres dans Fortnite**,
partie après partie, avec tes trésors et tes **stats de combat**, et un overlay qui se fond dans le HUD du jeu.

## Télécharger

1. Ouvre la [dernière version](https://github.com/XDTEAMDev/XDK-Chest-Counter-releases/releases/latest)
   (ou installe-le en un clic depuis le **XDK Hub**).
2. Télécharge **`XDKChestCounter.exe`** : un seul fichier, rien à installer (pas besoin de .NET).
3. Lance-le et suis la courte configuration (flèches + Entrée).

Au premier lancement, Windows peut afficher « Windows a protégé votre ordinateur » : clique sur
« Informations complémentaires » puis « Exécuter quand même ».

## Avant de jouer : active les rediffusions

Dans Fortnite : *Paramètres → Jeu → Rediffusions → Enregistrer les rediffusions : **Activé***. Sans replays, le
compteur n'a rien à lire. Fortnite n'écrit la clé du replay qu'à la fin de la partie : les coffres sont comptés
**quelques secondes après chaque partie** (pendant la partie, l'overlay affiche « ● En partie »).

## Ce qu'il compte

- **Coffres** ouverts ou cassés par toi : normaux, rares, enterrés, d'esprit, des affiches ; à part : caisses de
  munitions, caisses de nourriture, canons à butin.
- **Trésors** de la chasse au trésor (coffre doré, gizmos), et ceux de ton équipe (estimation).
- **Combat** : éliminations, assistances, dégâts infligés et subis, précision, réanimations, Top 1.
- **Déplacements** : distance parcourue, matériaux récoltés et utilisés, dégâts aux structures.
- **Overlay** en jeu (style HUD ou classique) : total, dernière partie, session, trésors, types de coffres et combat.
  Ctrl+Maj+O pour l'afficher / le masquer, Ctrl+Maj+L pour le verrouiller. Mets Fortnite en « Plein écran fenêtré ».
- **Rapport** dans ton navigateur (coffres par jour, types, trésors, combat, chaque partie), export CSV, et
  `overlay.html` pour une source navigateur OBS.

## Sans risque

- Il lit **seulement** les fichiers `.replay` de Fortnite (`%LOCALAPPDATA%\FortniteGame\Saved\Demos`), en lecture seule.
- Aucune modification du jeu, **aucun accès à la mémoire** de Fortnite, aucune connexion à ton compte Epic.
- Aucune donnée envoyée, aucun accès réseau : les mises à jour arrivent par le XDK Hub ou par cette page.

## Tu avais déjà le Chest Counter de LED-N ?

Ton historique est **copié** au premier lancement (l'original n'est pas modifié) et tes replays encore sur le PC sont
réanalysés avec les nouvelles stats. Ferme l'ancien compteur pour ne pas avoir les deux en même temps, et désactive son
« Ouvrir avec Fortnite » si tu l'avais activé.

## Aide

Discord **XDK TEAM DEV** : https://discord.gg/zEC35KSuxt

## Crédits et licence

Version modifiée du [Fortnite Chest Counter](https://github.com/LED-N/Fortnite-ChestCounter) de **LED-N** (licence MIT).
Lecteur de replays : FortniteReplayDecompressor de Shiqan (MIT). Police des titres : Pirata One (SIL OFL).
Toutes les licences : [LICENCES.txt](LICENCES.txt).

## Ce dépôt

Il ne contient que les versions à télécharger de XDK Chest Counter. Les autres logiciels de XDK TEAM DEV ont leurs
propres pages.
