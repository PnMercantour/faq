# Outils de messagerie, carnets d'adresse, agendas partagés, signatures, services Zoom au Parc National du Mercantour

Ce document explique comment configurer Zimbra, Thunderbird et les applications mobiles android de votre smartphone pour partager les agendas, carnets d'adresse (et même les dossiers de messagerie) et se connecter à Zoom.

L'application web [http://agenda.mercantour.local](http://agenda.mercantour.local) , accessible sur le réseau interne ou via le VPN, vous permet de consulter sans configuration préalable les agendas de _tous_ les agents et services du Parc, sous une forme expurgée. Cet outil est utile pour une recherche ponctuelle, ou pour consulter rapidement l'agenda du jour, de la semaine ou du mois de tous les membres d'un service.  
Pour en savoir plus : l'[application agenda](./agenda_mercantour_local.md)

## Configuration des outils de messagerie, carnets d'adresse et agendas

La configuration ne nécessite pas de droits administrateur, vous pouvez donc la réaliser vous-même si cela ne vous rebute pas.  
Sinon, prenez rendez-vous avec le SI qui réalisera la configuration pour vous (votre présence reste nécessaire, car le SI n'a pas accès à votre mot de passe de messagerie) et vous montrera comment personnaliser vos partages.

Notre serveur de messagerie Zimbra permet de partager les agendas, les carnets d'adresses et les boîtes mail, collectivement appelés `dossiers` par Zimbra.  
La première étape consiste à configurer le serveur [Zimbra](./Zimbra.md) pour [partager vos dossiers](./Zimbra.md#partager-son-agenda-son-carnet-dadresses-sa-boite-mail) et [accéder aux dossiers partagés par un collègue](./Zimbra.md#acceder-a-un-agenda-un-carnet-dadresses-ou-une-boite-mail-partages-avec-moi).

Après avoir configuré Zimbra, vous pourrez simplement accéder aux partages depuis [Thunderbird](./Thunderbird.md) ou sur votre [smartphone android](./android.md).

## Configuration et génération de la signature

Pour configurer sa signature rendez-vous sur l'url suivante : [http://signature.mercantour.local/](http://signature.mercantour.local/)

Rédiger votre signature en remplissant correctement les cases à remplir et à supprimer les éléments non nécessaire. (numéro de téléphone portable si nul besoin est par exemple)
Cliquer ensuite sur "Générer la signature" et glisser le fichier téléchargé dans "Documents" trouvable dans "Explorateur de fichiers" de Windows.

Se rendre ensuite sur le compte thunderbird où l'on souhaite apporter une signature et naviguer vers "Outils" dans la barre d'outils se trouvant en haut d'écran, puis sur "Paramètres des comptes". Une fois à ce niveau sur la première page, sélectionner "Apposer la signature à partir d'un fichier", puis cliquer sur la case "Choisir" se trouvant directement à droite. Enfin, sélectionner la signature précedémment téléchargée.

En dernier lieu, se rendre à nouveau vers "Outils" dans la barre d'outils, puis sur "Paramètres". Ensuite, cliquer sur l'onglet "Vie privée et sécurité", cocher la case "Autoriser le contenu distant dans les messages" et cliquer sur "Exceptions". Renseigner dans "Adresse du site web" : \*@mercantour-parcnational.fr puis "Autoriser", enfin, cliquer sur "Enregistrer les modifications".

## Message d'absence  

Il faut se rendre sur Zimbra.  
Dans l'onglet "préférences" , cliquer dans la colonne de gauche sur "hors du bureau".  
Le message automatique sera paramétrable dans son contenu et sa programmation de date de début à date de fin (optionnel)  
Il est impératif de l'activer par Zimbra et non par Thunderbird car ce dernier enverra en masse les messages à son démarrage et provoquera une alerte spam chez le prestataire avec une suspension de la messagerie.

## Services Zoom

[Procédure de connexion à Zoom et services associés.](./Zoom.md)
