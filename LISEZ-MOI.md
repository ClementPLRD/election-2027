# Site web autonome

Cinq pages HTML sans dépendance à Claude : `index.html` (portail), `economiques.html`, `sociales.html`, `immigration-securite-emploi.html` et `energie-climat-ruralite.html` (tableaux de bord). Les liens entre pages sont relatifs : gardez les cinq fichiers dans le même dossier.

Les pages comparent sept partis : FH, LE, LFI, LR, NE, PP et RN (le PS a été remplacé par Place publique).

## Ouvrir en local
Double-cliquer sur `index.html`. Le site s'ouvre dans le navigateur, sans serveur.
- Les polices (IBM Plex Sans, Newsreader) viennent de Google Fonts : sans connexion Internet, la page s'affiche avec une police de remplacement.
- Le bouton rond en haut à droite bascule entre thème clair et thème sombre ; le choix est mémorisé par le navigateur. Par défaut, le thème suit celui du système.

## Mettre en ligne
Le dossier est un site statique : il se publie tel quel sur n'importe quel hébergeur de fichiers (GitHub Pages, Netlify, Cloudflare Pages, hébergement d'une association ou d'un site personnel). Exemples :
- **Netlify Drop** : glisser le dossier `Site_web` sur la page « Drop » de Netlify ; un lien public est généré.
- **GitHub Pages** : déposer les cinq fichiers à la racine d'un dépôt public, puis activer Pages sur la branche principale.

Aucune publication n'a été faite : rien n'est en ligne tant que vous ne le faites pas.

## Mettre à jour
Ces fichiers sont la source des pages. Pour republier la version Artifact Claude, lancer `node Outils/build_artifact.mjs <dossier_de_sortie>`, puis publier le dossier créé.
Les chiffres des pages viennent des documents du dossier ; les estimations (déficit, probabilités) sont indicatives, pas un chiffrage officiel.
