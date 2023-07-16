# Messagerie sur un smartphone android

Ce document explique comment configurer un smartphone android pour se connecter aux services de mail, d'agenda et de carnet d'adresse de Zimbra.  
Il est nécessaire d'installer l'application [DAVx5](#installation-davx5) qui permet au smartphone de se connecter à Zimbra en utilisant les protocoles standard CALDAV et CARDDAV pour accéder aux calendriers et carnets d'adresse réseau personnels ou partagés avec vous.

## Mail

Ouvrez l'application E-mail de votre smartphone.

Les protocoles IMAP ou Exchange fonctionnent, préférez IMAP pour une nouvelle configuration.

- compte IMAP
- ou compte Exchange

## Installation DAVx5

_N'hésitez pas à faire appel au SI pour installer les applications sur votre smartphone professionnel._

Installez f-droid https://f-droid.org/F-Droid.apk . [f-droid(https://f-droid.org)] est un magasin d'applications libres, distinct du play store de google. De ce fait, l'installation est un peu plus complexe et réservée aux utilisateurs avertis.

Installation manuelle de f-droid, google play protect doit être désactivé pour autoriser l'installation.

Lancez f-droid et installez DAVx5.

## Configuration

Il faut d'abord paramétrer DAVx5 pour qu'il se connecte au serveur Zimbra. Ensuite il faut paramétrer les clients de calendrier/contacts (samsung, google, ...) pour qu'ils voient les dossiers (contacts et agendas) proposées par DAVx5.

### Paramétrage DAVx5

Il suffit de rentrer l'URL du serveur et le compte utilisateur.

- URL du serveur: `https://mail.espaces-naturels.fr/dav`

- L'identifiant de l'utilisateur est son adresse mail.

### Paramétrage agenda/contacts

Ouvrez l'application mobile d'agenda ou de contacts (google ou samsung) et ajoutez le compte DAVx5 en suivant la procédure propre à cette application.

## Compatibilité Samsung

Vérifiez que la synchronisation n'est pas bloquée. Les astuces (au lancement de DAVx5 expliquent quoi faire).

Tant qu'on n'a pas acquitté les astuces, elles réapparaissent à chaque utilisation de DAVx5.

En cas de problème, on peut réinitialiser les astuces déjà acquittées dans `paramètres de l'application / Réinitialiser les astuces`
