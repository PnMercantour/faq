# Guide d'impression de documents

Votre PC est normalement configuré pour proposer l'impression de documents sur l'imprimante de votre site de rattachement.  En cas de besoin, demandez au SI de paramétrer votre imprimante.

## L'impression ne fonctionne pas

Assurez-vous en premier lieu que l'imprimante est allumée et que votre PC est connecté au réseau interne (l'impression n'est pas permise depuis le réseau visiteurs).  

Il arrive que le client d'impression (spouleur) se bloque sur le PC, l'imprimante semble être hors connexion. Il faut dans ce cas relancer le spouleur.

- pour relancer le spouleur, taper `services` dans la barre de rechercher Windows, rechercher le service `Spouleur d'impression`, clic droit et sélectionner `redémarrer`.
- Autre technique, réservée aux administrateurs : ouvrir un terminal powershell en mode administrateur et taper les commandes 

```powershell
net stop spooler
net start spooler
```

Voir également la page de [résolution des erreurs d'exécution du service spouleur](https://support.microsoft.com/fr-fr/windows/correction-des-erreurs-d-ex%C3%A9cution-du-service-spouleur-d-impression-dans-windows-bb0de80a-8c4a-4938-a36a-f89a859113f0) sur le site Microsoft.