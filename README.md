# BrokOS

BrokOS transforme un PC Windows en console de salon. On allume le PC, BrokOS se lance en plein écran et tout se fait à la manette : les jeux, les vidéos, la musique, Discord, Twitch. Si vous avez plusieurs écrans, ils servent aussi : tableau de bord, chat Twitch, raccourcis du bureau.

Ce dépôt contient uniquement les installateurs et les mises à jour. BrokOS est encore en test, entre amis : attendez-vous à quelques bugs, et surtout, signalez-les.

**[Télécharger la dernière version](https://github.com/tiiolando/brokos-releases/releases/latest)**

---

## Installation

1. Ouvrez la page [Releases](https://github.com/tiiolando/brokos-releases/releases/latest) et téléchargez `BrokOS_x.y.z_x64-setup.exe`.
2. Lancez le fichier. Windows peut afficher **« Windows a protégé votre ordinateur »** : l'installateur n'est pas encore signé par un certificat payant. Cliquez sur **Informations complémentaires**, puis **Exécuter quand même**.
3. L'installation ne demande pas de droits administrateur. Si WebView2 manque sur le PC (rare sous Windows 10/11), il est installé au passage.
4. Au premier lancement, un assistant vous guide : écrans, ville pour la météo, dossiers de films et de musique, compte Twitch. Tout reste modifiable ensuite dans **Paramètres**.

### Configuration conseillée

| | |
|---|---|
| Système | Windows 10 ou 11, 64 bits |
| Manette | Xbox, PlayStation (DualSense / DualShock 4) ou toute manette reconnue par Windows |
| Écrans | Un seul suffit. Deux ou trois, c'est mieux |
| Jeux | Steam et Epic Games sont détectés automatiquement, les autres jeux et programmes s'ajoutent à la main |

---

## Ce que fait BrokOS

**L'Accueil, sur l'écran principal**
Vos jeux Steam et Epic avec leurs jaquettes, les jeux installés récemment, la météo et l'actualité de votre ville. On lance un jeu avec A, on revient sur BrokOS avec le bouton Home de la manette.

**Les autres écrans**
Chaque écran secondaire a son rôle, que l'on change à la manette :

- **Control Center** : performances du PC en direct (processeur, carte graphique, mémoire, températures), connexion internet, météo et actualité locale.
- **Bureau** : vos raccourcis et applications, utilisables à la manette.
- **Console étendue** : l'image et les infos du jeu sélectionné sur l'Accueil.
- **Twitch** : en live, un vrai tableau de bord de streamer (courbe des viewers, follows, abonnements, raids, clip, marqueur, pubs, modes du chat, titre et catégorie). Hors live, les chaînes suivies en direct, les prochains streams, les clips et les rediffusions.

**Le reste**
- Discord, YouTube (interface TV, pilotable à la manette), Google et Twitch dans des fenêtres plein écran.
- Twitch : connexion par QR code, streams suivis, chat, modération à la manette.
- Films, séries et musique depuis vos dossiers, y compris sur le réseau.
- Clavier à l'écran dès qu'un champ de texte s'ouvre : plus besoin de reprendre la souris.
- Fonds animés, Wallpaper Engine, sons d'interface, vibrations.
- Démarrage automatique en mode console à l'ouverture de session.

---

## Commandes

| Manette | Clavier | Action |
|---|---|---|
| A | Entrée | Valider |
| B | Échap | Retour |
| Home / Guide / PS | Ctrl + Alt + Origine | Revenir sur BrokOS (menu rapide en jeu) |
| Home maintenu | Ctrl + Alt + Origine maintenu | Applications ouvertes, avec aperçu |
| L3 | F2 | Piloter l'écran suivant (B pour revenir) |
| L3 + R3 | F2 + F3 | Gestionnaire d'écrans : rôles, résolution, orientation |
| View / Select | Tab | Changer le mode de l'écran 2 |
| Menu / Start | M | Paramètres |
| LB / RB | Q / E | Onglet précédent / suivant |
| Y | Y | Masquer l'élément sélectionné |
| | Ctrl + Alt + Fin | Fermer le jeu en cours |
| | Ctrl + Alt + M | Couper ou rétablir les sons |

Avec le clavier à l'écran : A tape la lettre, X efface, Y ajoute un espace, Start valide, B ferme.

---

## Mises à jour

BrokOS vérifie tout seul s'il existe une nouvelle version, au démarrage puis toutes les quatre heures. Quand c'est le cas, un bandeau apparaît en haut de l'Accueil. L'installation se lance dans **Paramètres → Système → Installer BrokOS x.y.z** : BrokOS se ferme, se met à jour et redémarre en moins d'une minute.

Les mises à jour sont signées : BrokOS refuse tout fichier qui ne vient pas d'ici.

---

## Signaler un problème

C'est le but de cette phase de test. Ouvrez une [issue](https://github.com/tiiolando/brokos-releases/issues/new) et indiquez :

- **la version** (Paramètres → Système) ;
- **ce que vous faisiez** juste avant, étape par étape ;
- **ce qui s'est passé** et ce que vous attendiez ;
- votre configuration : nombre d'écrans, modèle de manette ;
- une capture ou une vidéo si possible, ça aide énormément.

Une idée ou une envie plutôt qu'un bug ? Ouvrez aussi une issue, en commençant le titre par **Idée :**.

---

## Désinstaller

**Paramètres Windows → Applications → BrokOS → Désinstaller.** Vos réglages restent dans `%APPDATA%\com.brokos.launcher` : supprimez ce dossier pour repartir de zéro.

---

<sub>BrokOS est un projet perso de [brok_n_one](https://twitch.tv/brok_n_one), fait sur son temps libre. Il n'est affilié ni à Microsoft, ni à Valve, ni à Epic Games, ni à Twitch.</sub>
