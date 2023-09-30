# TP d'OSINT 🔍
## Le scénario
Vous êtes actuellement en recherche d'une PS5 sur leboncoin. Une annonce très agichante vous attire l'œil et vous passez commande ! Malheureusement, il s'agissait d'une arnaque. Vous avez accès à la conversation qui a eu lieu via le chat leboncoin pour trouver la localisation de la personne et son véritable nom. Utilisez ce qui vous a été présenté pendant le cours pour y parvenir.<br><br>
**À vous de jouer** !

## Recherche du mail ✉️

Premièrement, concentrez vous sur la recherche du mail de l'arnaqueuse. Étudiez toutes les pistes.<br>
Voici le lien vous permettant d'accéder à la conversation que vous avez eu avec elle :<br>
https://lemauvaiscoin.ddns.net

## Le mail a été trouvé ? Trouvez maintenant la localisation 📍

L'outil que vous allez utiliser s'appelle GHunt. Il est très réputé en OSINT pour l'analyse de compte Gmail car il peut vous apporter des informations précieuses.

### Installation de GHunt 🕵️

⚠️ Prérequis ⚠️<br>
 Python 3.10 ou supérieur<br>
 Navigateur Google Chrome<br>
 PyCharm (de préférence)<br>
 Compte Google<br>

Clonez le répertoire GitHub suivant sur votre ordinateur.<br>
https://github.com/mxrch/ghunt
<br>

Ouvrez le dossier avec PyCharm afin de créer un environnement virtuel (venv) permettant de ne pas installer les dépendances utilisées par le projet directement sur votre machine. Vous pouvez aussi le faire en ligne de commande si vous le souhaitez. Installez ensuite les dépendences nécéssaires à l'aide du fichier requirements.txt<br>

Pour utiliser GHunt, il faut nécessairement se connecter avec un compte gmail. Pour celà, il va falloir récupérer les cookies de connexion de votre compte. Si vous n'êtes pas rassurés à l'idée d'utiliser vos cookies de connexion, créez vous un autre compte.<br>

Pour récuperer les cookies, installez l'extension suivante dans Google Chrome.<br><br>
[![Chrome](https://storage.googleapis.com/web-dev-uploads/image/WlD8wC6g8khYWPJUsQceQkhXSlv1/UV4C4ybeBTsZt43U4xis.png)](https://chrome.google.com/webstore/detail/ghunt-companion/dpdcofblfbmmnikcbmmiakkclocadjab)<br>
Connectez-vous avec votre compte Google.<br><br>
Rendez vous dans le projet et lancez le main.py avec l'argument login.<br>
Le plus simple est de le lancer sans argument avec le bouton Run. Ensuite vous copiez la commande qui a été insérée dans votre terminal pour lancer le main. Copiez-là et ajoutez l'argument login à la fin.<br>
Si vous êtes sur Windows, le chemin pour accéder à python peut comprendre des espaces. Si c'est le cas, utilisez des guillemets.<br>
> Ex : C:\Users\example path\python3.10 mettez des guillemets autour de example path pour obtenir C:\Users\'example path'\python3.10<br>

Utilisez la méthode 1 ou 2 comme vous le souhaitez pour vous connecter.<br>

Pour analyser un mail Google, utilisez simplement l'argument email \<mail\>.


