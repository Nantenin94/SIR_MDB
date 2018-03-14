# SIR_MDB
# TP3: MongoDB

## Description de MongoDB
MongoDB est un système de gestion de base de données orientée documents, répartissable sur un nombre quelconque d'ordinateurs et ne nécessitant pas de schéma prédéfini des données. Il est écrit en C++.
MongoDB est autonome et n'a aucune autre dépendance du système. Vous pouvez exécuter MongoDB à partir de n'importe quel dossier que vous choisissez.

## Installation MongoDB

-Installer MongoDB

-Telecharger depuis https://www.mongodb.com/ 

lancez l'invite de commandes et sélectionnez Exécuter en tant qu'administrateur dans le menu contextuel.
cd \
déplacer w: \ mongodb-win32- * w: \ mongodb

-L'emplacement par défaut du répertoire de données MongoDB est w: \ data \ db. Créez ce dossier en utilisant l'invite de commande.
md w: \ mongodb \ données
md w: \ mongodb \ données \ db

-Demarrer MongoDB: w: \ mongodb \ bin \ mongod.exe --dbpath w: \ mongodb \ data \ db

-Connectez-vous à MongoDB en utilisant le shell mongo.exe
-exécutez la commande suivante:
w: \ mongodb \ bin \ mongo.exe

Après une installation réussie de mongoDB, ouvrez le shell mongoDB et créez un utilisateur / mot de passe, par exemple:
-> utiliser txppdb
-> db.createUser ({utilisateur: "txpapi", pwd: "txp", rôles: [{role: "dbAdmin", db: "txpdb"}]})
-Vous pouvez utiliser n'importe quel mot de passe et hôte. Cependant, user, role et db doivent être respectivement "txpapi", "dbAdmin" et "txpdb"

## Redis
Redis est un système de gestion de base de données clef-valeur scalable, très hautes performances, écrit en C ANSI et distribué sous licence BSD. Il fait partie de la mouvance NoSQL et vise à fournir les performances les plus élevées possibles.
les differentes données qui peuvent etre stockés dans Redis:
-Ensembles de données
-Bitmaps
-données simples
-List
-Char
-Tableaux....


		

