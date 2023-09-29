# TP d'OSINT 🔍
## Le scénario
Vous êtes actuellement en recherche d'une PS5 sur leboncoin. Une annonce très agichante vous attire l'oeuil et vous passez commande ! Malheureusement, il s'agissait d'une arnaque. Vous avez accès à la conversation qui a eu lieu via le chat leboncoin pour trouver la localisation de la personne et son véritable nom. Utilisez ce qui vous a été présenté pendant le cours pour y parvenir.<br><br>
**À vous de jouer** !

## Recherche du mail ✉️

Premièrement, concentrez vous sur la recherche du mail de l'arnaqueuse. Étudiez toutes les pistes.

## Le mail a été trouvé ? Trouvez maintenant la localisation 📍

L'outil que vous allez utiliser s'appelle GHunt. Il est très réputé en OSINT pour l'analyse de compte Gmail car il peut vous apporter des informations précieuses.

### Installation de GHunt 🕵️

Clonez le répertoire GitHub suivant sur votre ordinateur.<br>
https://github.com/mxrch/ghunt
<br>
Placez vous dans le répertoire contenant le dossier ghunt et créez un environnement python (ceci vous évite d'installer les dépendances directement sur votre machine). Pour ce faire, utilisez la commande suivante.
```
python -m venv /path/to/directory/ghunt
```
Pour utiliser GHunt, il faut nécéssairement se connecter avec un compte gmail. Pour celà, il va falloir récupérer les cookies de connexion de votre compte. Si vous n'êtes pas rassurés à l'idée d'utiliser vos cookies de connexion, créez vous un autre compte.<br>

Pour récuperer les cookies, installez l'extension suivante dans votre navigateur.<br><br>
[![Firefox](https://files.catbox.moe/5g2ld5.png)](https://addons.mozilla.org/en-US/firefox/addon/ghunt-companion/)&nbsp;&nbsp;&nbsp;[![Chrome](https://storage.googleapis.com/web-dev-uploads/image/WlD8wC6g8khYWPJUsQceQkhXSlv1/UV4C4ybeBTsZt43U4xis.png)](https://chrome.google.com/webstore/detail/ghunt-companion/dpdcofblfbmmnikcbmmiakkclocadjab)


