# PORT-GAME

Une petite plateforme de jeux pour apprendre par cœur les ports et protocoles réseau
(liste de soutenance d'oral AIS).

## 👉 Jouer : https://mapics.github.io/PORT-GAME/

## Les jeux

| Jeu | Ce qu'il entraîne |
|---|---|
| 🏆 **Ranked** | 20 questions chronométrées sans aide. Classement de Bronze à Diamant. |
| 🧠 **Apprendre** | Les ports arrivent 4 par 4 avec une astuce, en QCM puis en saisie. Les ports ratés reviennent plus souvent. |
| ⌨️ **Port Quiz** | Révision libre, dans les deux sens. |
| 👾 **Port Invaders** | Tape le port pour détruire l'envahisseur. 3 difficultés. |
| 🐷 **Porc Invaders** | Le même, en version ferme. |
| 🔗 **Relier par familles** | Relie chaque protocole à son port, par familles (Mail, Web, Windows, Infra, VPN). |
| 🃏 **Memory** | Retrouve les paires protocole ↔ port. |
| 🛡️ **Pare-feu** | 18 situations d'admin réseau : autorise ou bloque chaque paquet. |
| 📋 **La liste** | Toute la liste à réviser. |

## Profil

Niveau et XP, 4 missions par jour, graphique de l'XP sur 14 jours, meilleurs scores par
jour et par jeu, et un livret de ports avec une note en étoiles pour chacun des 33 ports.

## Technique

Une seule page HTML, sans dépendance ni serveur. La progression est enregistrée dans le
navigateur de chaque joueur (localStorage) : chacun a la sienne, et rien n'est envoyé nulle part.
