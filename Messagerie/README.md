# Outils de messagerie, carnets d'adresse, agendas partagés, signatures au Parc National du Mercantour

Ce document explique comment configurer Zimbra, Thunderbird et les applications mobiles android de votre smartphone pour partager les agendas, carnets d'adresse (et même les dossiers de messagerie).

L'application web http://agenda.mercantour.local , accessible sur le réseau interne ou via le VPN, vous permet de consulter sans configuration préalable les agendas de  _tous_ les agents et services du Parc, sous une forme expurgée. Cet outil est utile pour une recherche ponctuelle, ou pour consulter rapidement l'agenda du jour, de la semaine ou du mois de tous les membres d'un service.  
Cette application remplace l'ancien agenda partagé http://192.168.80.14/agenda/ qui ne peut pas fonctionner dans un environnement sécurisé.
Pour en savoir plus : l'[application agenda](agenda.mercantour.local/README.md) 

## Configuration des outils de messagerie, carnets d'adresse et agendas

La configuration ne nécessite pas de droits administrateur, vous pouvez donc la réaliser vous-même si cela ne vous rebute pas.  
Sinon, prenez rendez-vous avec le SI qui réalisera la configuration pour vous (votre présence reste nécessaire, car le SI n'a pas accès à votre mot de passe de messagerie) et vous montrera comment personnaliser vos partages.

Notre serveur de messagerie Zimbra permet de partager les agendas, les carnets d'adresses et les boîtes mail, collectivement appelés `dossiers` par Zimbra.  
La première étape consiste à configurer le serveur [Zimbra](Zimbra/README.md) pour [partager vos dossiers](Zimbra/README.md#partager-son-agenda-son-carnet-dadresses-sa-boîte-mail) et [accéder aux dossiers partagés par un collègue](Zimbra/README.md#accéder-à-un-agenda-un-carnet-dadresses-ou-une-boîte-mail-partagés-avec-moi).

Après avoir configuré Zimbra, vous pourrez simplement accéder aux partages depuis [Thunderbird](Thunderbird/README.md) ou sur votre [smartphone android](android/README.md).

## Configuration et génération de la signature 

Pour configurer sa signature il suffit de se rendre sur l'url suivante : [http://signature.mercantour.local/] 
Rédiger votre signature comme bon vous semble en remplissant correctement les cases à remplir et à supprimer les éléments non nécessaire. (numéro de téléphone portable si nul besoin est par exemple)
Cliquer ensuite sur "Générer la signature" et glisser le fichier télécharger dans "Documents" trouvable dans "Explorateur de fichiers" de Windows. Se rendre ensuite sur le compte thunderbird où l'on souhaite apporter une signature et naviguer vers "Outils" dans la barre d'outils se trouvant en haut d'écran, puis sur "Paramètres des comptes". Une fois à ce niveau sur la première page, sélectionner "Apposer la signature à partir d'un fichier", puis cliquer sur la case "Choisir" se trouvant directement à droite. Enfin, sélectionner la signature précedémment téléchargé.
