<p align="center">
  <img src="docs/images/banniere.png" alt="BOB MUSIC" width="720">
</p>
<p align="center">
  <b>Le lecteur de musique de bureau pour ton serveur Plex.</b><br>
  Qualité Lossless, statistiques d'écoute, nouveautés de tes artistes, et mises à jour automatiques.
</p>
<p align="center">
  <a href="https://github.com/lepretrevincent89-source/BOBMUSIC/releases/latest"><b>⬇️ Télécharger la dernière version</b></a>
  &nbsp;•&nbsp; Windows 10 / 11 &nbsp;•&nbsp; Gratuit
</p>
---
✨ En bref
BOB MUSIC se connecte à ton serveur Plex et te donne accès à toute ta bibliothèque musicale dans une application Windows rapide et élégante :
artistes, albums, titres, playlists, recherche, file d'attente… avec une vraie attention portée à la qualité du son.
📥 Installation
Va sur la page des versions (Releases).
Dans Assets, télécharge `BOB-MUSIC-Setup-x.y.z.exe`.
Lance-le et suis l'installation : pas besoin d'être administrateur. Les raccourcis Bureau et menu Démarrer sont créés.
> **Windows affiche « Windows a protégé votre ordinateur » ?**
> C'est normal pour un logiciel indépendant non signé. Clique sur **Informations complémentaires → Exécuter quand même**.
Version portable : le fichier `BOB-MUSIC-x.y.z-portable.exe` se lance sans installation, depuis une clé USB par exemple. Elle ne se met pas à jour toute seule.
🔑 Première connexion
Clique sur Se connecter avec Plex : ton navigateur s'ouvre, connecte-toi et autorise l'application.
BOB MUSIC trouve tes serveurs et tes bibliothèques musicales automatiquement.
La connexion est mémorisée pour les fois suivantes.
Tu peux aussi te connecter manuellement avec l'adresse du serveur (ex. `http://192.168.1.10:32400`) et ton jeton `X-Plex-Token`.
🎧 Qualité de lecture : Lossless, sans rien installer
<p align="center"><img src="docs/images/lecture.png" alt="Réglages de qualité de lecture" width="620"></p>
BOB MUSIC lit le fichier original. Les formats que Windows ne sait pas lire (ALAC / Apple Lossless, AIFF, WMA, APE, WavPack, DSD…) sont décodés sur ton PC, sans aucune perte, par le décodeur intégré. Il est fourni avec l'application : aucun codec à installer.
Dans ⚙ → Lecture et conversion, choisis ton mode :
Mode	Pour qui ?
Automatique (recommandé)	Le meilleur des deux : l'original en priorité, et une conversion en MP3 320 kbps seulement si un fichier est illisible.
Lossless	Les puristes : jamais de conversion, la qualité d'origine garantie.
Tout en MP3 320 kbps	Les connexions lentes ou l'écoute à distance : 2 à 4 fois moins de données.
Des badges indiquent la qualité du titre en cours : Sans perte, Hi-Res, MP3 320 kbps…
📊 Statistiques d'écoute (Last.fm)
<p align="center"><img src="docs/images/stats-accueil.png" alt="Résumé de la semaine sur l'accueil" width="100%"></p>
Relie ton compte Last.fm (⚙ → Last.fm et statistiques) pour obtenir :
un résumé de la semaine sur l'accueil : nombre d'écoutes, comparaison avec la semaine précédente, graphique jour par jour, artistes, titre et album de la semaine ;
une page Statistiques complète : artistes, albums et titres les plus écoutés, écoutes par jour et par heure, écoutes récentes ;
des périodes au choix : Aujourd'hui, 7 jours, 1 mois, 3 mois, 6 mois, 12 mois, depuis toujours ;
l'envoi de tes écoutes à Last.fm (scrobbling).
🎵 Toutes les fonctions
Accueil personnalisable : glisse-dépose les catégories et les modules (Nouveautés, Statistiques), masque ce que tu ne veux pas voir, ajoute des rangées par genre, décennie ou playlist.
Nouveautés : les albums, EP et singles récents ou à venir de tes artistes préférés, avec écoute des extraits.
Page artiste : titres populaires, discographie, biographie traduite automatiquement.
Paroles synchronisées, écran « En cours de lecture » plein écran.
Mini lecteur détachable et toujours visible, plus les boutons de lecture dans l'aperçu de la barre des tâches.
Touches multimédia du clavier, panneau média de Windows, boutons Précédent / Suivant de la souris.
Raccourcis : `Espace` lecture/pause, `← / →` ±10 s, `Ctrl + ← / →` titre précédent/suivant.
10 thèmes en dégradé et un thème sur mesure.
Modifier les informations (titres, jaquettes, genres…), réservé au propriétaire du serveur Plex.
La lecture apparaît dans le tableau de bord Plex (« En cours de lecture »), et les titres écoutés sont marqués comme lus.
Application en français et en anglais.
🔄 Mises à jour automatiques
<p align="center"><img src="docs/images/a-propos.png" alt="À propos et mises à jour" width="560"></p>
La version installée vérifie toute seule s'il existe une nouvelle version, au démarrage puis toutes les 4 heures. Elle la télécharge en arrière-plan et te propose de redémarrer pour l'installer. Tes réglages sont conservés.
Ta version est affichée en bas du menu ⚙ et dans ⚙ → À propos et mises à jour.
❓ Questions fréquentes
<details>
<summary><b>Faut-il un abonnement Plex Pass ?</b></summary>
Non. Il faut simplement un serveur Plex avec une bibliothèque de musique, et un compte qui y a accès.
</details>
<details>
<summary><b>Pourquoi je ne peux pas modifier les albums ?</b></summary>
Seul le <b>propriétaire</b> du serveur Plex peut modifier les informations de la bibliothèque. Si le serveur t'est partagé, ces boutons sont masqués.
</details>
<details>
<summary><b>Un titre est passé avec un message « conversion désactivée »</b></summary>
Tu es en mode <b>Lossless</b> et ce fichier est illisible sans conversion. Passe en mode <b>Automatique</b> dans ⚙ → Lecture et conversion.
</details>
<details>
<summary><b>Comment profiter du Hi-Res (24 bits / 96 kHz et plus) ?</b></summary>
BOB MUSIC passe par le mixeur audio de Windows. Règle la fréquence de ta sortie audio dans
<i>Paramètres → Son → ton périphérique → Format</i>, par exemple 24 bits, 96 000 Hz.
</details>
<details>
<summary><b>Comment désinstaller ?</b></summary>
Paramètres Windows → Applications → <b>BOB MUSIC</b> → Désinstaller.
</details>
---
<p align="center"><sub>BOB MUSIC est un projet indépendant, non affilié à Plex Inc. ni à Last.fm.</sub></p>
