Garrys-Mod-Partage de famille Empêchez les joueurs de contourner les bannissements existants sur les serveurs de mods Garrys.

La façon dont ce script fonctionne est qu’il permet aux utilisateurs de partage familial de rejoindre et de jouer (à moins que vous n’activiez la fonctionnalité de blocage de tous les comptes partagés familiaux). Lorsque vous bannissez un joueur de votre serveur, il vérifiera si le compte est partagé, si c’est le cas, il bannira à la fois le compte Steam du propriétaire et le compte partagé via lequel il est actuellement connecté, empêchant ainsi d’autres alts de se joindre.

Ce script empêchera les joueurs de contourner les bannissements actuels / existants en utilisant la fonction de partage familial intégrée de Steam.

Ce script empêchera également les joueurs de contourner les bannissements actuels / existants en achetant un nouveau Garry’s Mod. (Oui, il peut aussi le détecter.) via la fonction de suivi des bannissements.

Cela ajoutera également, « si activé », l’interdiction des utilisateurs par adresse IP à l’ULX et à la commande par défaut.!ban"ulx ban"!banid"ulx banid"

Si vous rencontrez des bugs, des problèmes ou des problèmes, postez simplement une demande de problème. l'adresse: cybernova@gmx.fr

Fonctionnalités: Bannir ceux qui tentent de contourner les interdictions actuelles / existantes. (Par défaut : TRUE)

La durée du bannissement est configurable. (Par défaut : 0 Permament).

La raison du bannissement est configurable.

Bannissez également les utilisateurs par adresse IP. (Par défaut : TRUE)

Bloquez tous les comptes de partage familial configurables. (Par défaut : FALSE)

Bloquer tous les motifs de kick du partage familial configurables.

Vérifie sur les comptes qui se connectent au serveur, si leur adresse IP n’est pas bannie mais que leur SteamID l’est, leur adresse IP sera également bannie quelle que soit la durée de leur interdiction actuelle. (Par défaut : TRUE)

Le message de bannissement informatif rend le message de bannissement ULX par défaut joli et utile pour le joueur qui le lit. (Par défaut : TRUE)

Message de bannissement personnalisé configurable.

Bannissez le traqueur pour empêcher les joueurs d’acheter un nouveau mod GMod Garry’s afin de se connecter. (Par défaut : TRUE)

Bannir les chemins, les paramètres et les options du traqueur, tous configurables.

Comment installer Installez le script dans le dossier."/garrysmod/lua/autorun/"

Le chemin d’accès devrait ressembler à ceci : "/garrysmod/lua/autorun/familysharing.lua"

Emplacement d’installation alternatif : Si vous ne souhaitez pas utiliser le répertoire ci-dessus, vous pouvez installer ce script en tant qu’addon à l’emplacement suivant.

Installez l’addon dans le dossier."/garrysmod/addons/"

La disposition du chemin doit ressembler à ceci : "/garrysmod/addons/familysharing/lua/autorun/familysharing.lua"

Configurez le script et mettez votre clé API Steam Dev : (La clé API Steam Dev peut être obtenue à partir de http://steamcommunity.com/dev/apikey )

Optionnel: Dans votre fichier, assurez-vous que vous avez ce qui suit : (Cela garantit que si vous activez la fonction de bannissement d’IP, elle utilisera réellement la liste de bannissement d’IP.)server.cfg

exec banned_user.cfg

exec banned_ip.cfg

Usage: Afin d’interdire le partage familial des utilisateurs, le script fera tout automatiquement, vous n’avez donc pas à vous soucier de quoi que ce soit, tout ce que vous avez à faire est d’utiliser la commande ou dans le chat ou vous pouvez utiliser le menu ULX ou / via la console. Le scénario fait tout le reste.!ban!banid!menuulx banulx banid

Paramètres recommandés : Je recommande les paramètres par défaut et les seuls paramètres que je recommande à chaque propriétaire de serveur de changer sont les suivants : de cette façon, votre serveur est unique et utilise ses propres chemins pour suivre les joueurs bannis.

Dépendances / Exigences : ULX / ULIB :

http://ulyssesmod.net/downloads.php

La clé API Steam Dev peut être obtenue auprès de :

http://steamcommunity.com/dev/apikey

F.A.Q (Foire aux questions) : Vais-je ajouter le support MySQL / Database ? Je n’en ai pas besoin. C’est quelque chose à ajouter au mod ULX Admin, pas à ce script.
