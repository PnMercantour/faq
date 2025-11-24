# Connexion Wifi au PNM

Deux réseaux Wifi sont configurés dans les sites PNM (valable pour tous les sites, à l'exclusion de Allos qui sera prochainement équipé) : pnm-utilisateurs et pnm-visiteurs .
IMPORTANT : l'accès au réseau pnm-utilisateurs est strictement réservé aux ordinateurs et mobiles de l'établissement.  
Utilisez le réseau pnm-visiteurs pour la connexion de vos matériels personnels et pour vos invités.

## Connexion au réseau pnm-utilisateurs

Cette connexion vous donne accès aux serveurs de fichiers, aux applications internes (intranet, agenda, etc) et au réseau intersites (services territoriaux, services OFB, services RIE).  
Vous devrez vous authentifier avec votre identifiant Windows.  
N'utilisez ce réseau qu'avec des ordinateurs et mobiles de l'établissement.

### Windows - Installation du profil Wi-Fi
Le profil Wi-Fi pnm-utilisateurs est installé par le SI sur les nouveaux ordinateurs Windows.  
Vous pouvez télécharger le profil et l'installer vous-mêmes sur votre ordinateur professionnel.

Télécharger le profil ci-dessous.
https://configuration.mercantour.local/Wi-Fi-pnm-utilisateurs.xml


Ouvrir une fenêtre powershell (t)
```powershell
# Pour aller dans le répertoire de téléchargement
cd .\Downloads\
# Liste des profils installés
netsh wlan show profiles
# Installation du profil pnm-utilisateurs
netsh wlan add profile Wi-Fi-pnm-utilisateurs.xml
# Détail du profil pnm-utiisateurs
netsh wlan show profile pnm-utilisateurs
# Connexion au profil pnm-utilisateurs
netsh wlan connect pnm-utilisateurs
# Déconnexion du profil courant
netsh wlan disconnect
# Aide netsh
netsh wlan help
```

### Windows 10
  - Afficher les réseaux wifi ( logo de planète ou wifi en bas à droite ), si l'ordinateur est connecté à "mercantour" se déconnecter et s'assurer que "Se connecter automatiquement" est décoché
  - Sélectionner dans la liste pnm-utilisateurs
  - Laisser cochée la case "se connecter automatiquement"
  - Cliquer sur "se connecter"
  - Cocher la case "Utiliser mon compte d'utilisateur Windows" cela renseigne automatiquement l'identifiant et le mot de passe
  - Si la case "Utiliser mon compte d'utilisateur Windows" et le bouton "OK" sont grisés, renseigner manuellement le compte sous la forme mercantour\compte et le mot de passe de l'ordinateur. Le bouton "OK" devient actif.
  - Cliquer sur "OK"
  - Cliquer sur "Se connecter"

### Windows 11
  - Cliquer sur le logo de planète (ou wifi) en bas à droite, une fenêtre s'affiche avec, en haut à gauche de celle-ci, le wifi
  - Cliquer sur la flèche-droite du wifi, les réseaux s'affichent.
  - Si "mercantour" est connecté, se déconnecter et s'assurer que "Se connecter automatiquement" est décoché
  - Ensuite, faire défiler les réseaux pour afficher "pnm-utilisateurs"
  - Garder "Se connecter automatiquement" coché et cliquer sur "Se connecter"
  - Cocher "Utiliser mon compte d'utilisateur Windows" , les champs d'identifiant et de mot de passe se remplissent automatiquement
  - Si la case "Utiliser mon compte d'utilisateur Windows" et le bouton "OK" sont grisés, renseigner manuellement le compte sous la forme mercantour\compte et le mot de passe de l'ordinateur. Le bouton "OK" devient actif.
  - Cliquer sur "OK" puis sur "Se connecter"

### Android
  - Indiquez votre adresse mail
  - Saisissez votre mot de passe Windows.
Il est recommandé de contrôler également les paramètres avancés. Sélectionner `Afficher plus` puis :
  - Type d'adresse MAC: Adresse MAC du téléphone  
    
## Connexion au réseau pnm-visiteurs

Vos visiteurs peuvent connecter leur ordinateur ou smartphone au réseau wifi pnm-visiteurs. Vous pouvez également utiliser ce réseau avec vos téléphones personnels.  
Ce réseau permet d'accéder à Internet. Les serveurs de fichiers et applications internes et les imprimantes ne sont pas accessibles par cette connexion.

Le mot de passe d'accès à ce réseau est diffusé en interne (demandez au SI si besoin).

## Problèmes de connexion

En cas de problème de connexion à l'un de ces réseaux, contactez le SI.
