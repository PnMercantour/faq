# Installation et utilisation de la suite Office (Microsoft 365)

Le Parc dispose de licences **Microsoft 365** pour ses agents. Vous pouvez utiliser **Word**, **Excel** et **PowerPoint** sur votre ordinateur.

!!! warning "Outils collaboratifs non autorisés pour le moment"
    Tant que les postes ne sont pas mieux sécurisés (double authentification, gestion à distance par le SI, etc.), seuls **Word, Excel et PowerPoint** sont autorisés.
    
    Les applications OneDrive, SharePoint ou OneNote, ne sont pas accessibles.

## 1. Installation : rien à faire

La suite Office est déployée progressivement et de façon automatisée sur le poste de tous les agents par le SI (stratégie de groupe).

- L'installation se lance **automatiquement au démarrage de l'ordinateur**.
- Elle est **silencieuse** : aucune fenêtre ne s'affiche et aucune action n'est demandée.
- Votre ordinateur doit être **allumé et connecté au réseau du Parc** (Ethernet, Wi-Fi `pnm-utilisateurs` ou [VPN](../reseau/VPN.md)).

Si Word, Excel et PowerPoint apparaissent dans le menu Démarrer, la suite est installée. Vous serez prévenus lorsque votre service sera concerné par le déploiement. Si la suite ne s'installe pas après plusieurs redémarrages, contacter le SI.

## 2. Première utilisation : se connecter

La première fois, il faut associer Office à votre compte du Parc pour activer la licence.

1. Ouvrez une application Office, par exemple **Word** (tapez `Word` dans la barre de recherche Windows).
2. Cliquez sur **Se connecter**.
3. Saisissez votre adresse mail : `prenom.nom@mercantour-parcnational.fr`.
4. Saisissez votre mot de passe : c'est **le même que celui de votre session Windows**.

Une fois connecté, vous êtes connecté dans toutes les applications Office, vous n'avez pas à recommencer pour Excel ou PowerPoint.

!!! tip "Changement de mot de passe"
    Si vous changez votre mot de passe Windows, Office peut vous demander de vous reconnecter. Utilisez alors votre nouveau mot de passe.

## 3. Quel logiciel pour quel type de fichier ?

Au Parc, deux suites bureautiques coexistent. Pour éviter les problèmes de mise en forme, ouvrez chaque fichier avec la suite adaptée à son format :

| Type de fichier | Extensions | Logiciel à utiliser |
|-----------------|------------|---------------------|
| Fichiers **OpenDocument** | `.odt`, `.ods`, `.odp` | **LibreOffice** |
| Fichiers **Office** | `.docx`, `.xlsx`, `.pptx` | **Microsoft Office** (Word, Excel, PowerPoint) |

!!! info "Choix du format à la première ouverture"
    Lors de la première ouverture d'une application Office, une fenêtre peut vous demander de **choisir le format de fichier par défaut**. Sélectionnez **Office Open XML** (formats `.docx`, `.xlsx`, `.pptx`) et **non** OpenDocument : les fichiers OpenDocument restent à ouvrir avec LibreOffice.

> Privilégiez la création de nouveaux fichiers au format de fichier **Office** et essayez de faire migrer vos anciens documents vers ces formats.

## 4. Où enregistrer mes documents ?

Puisque OneDrive et SharePoint ne sont pas utilisables, enregistrez vos fichiers comme d'habitude :

- pour les documents sur lesquels vous travaillez privilégiez l'enregistrement directement sur le disque dur de votre PC 
- sur les **disques réseau** de votre site ou du siège (Serveur X:, S: ou T:)
- dans votre espace personnel **Perso (P:)**, voir [Stocker ses documents](espace_personnel.md).

Pour travailler à plusieurs sur un même document, vous pouvez utiliser l'outil [Fichiers](https://lasuite.numerique.gouv.fr/produits/fichiers) de la DINUM, utilisable via votre compte ProConnect.

## 5. Un problème ?

| Problème | Solution |
|----------|----------|
| Vous avez été averti du déploiement de la suite Office et Word, Excel ou PowerPoint n'apparaissent pas dans le menu Démarrer | Redémarrez l'ordinateur, connecté au réseau du Parc, et patientez quelques minutes. |
| Impossible de se connecter | Vérifiez votre adresse (`prenom.nom@mercantour-parcnational.fr`) et utilisez le mot de passe de votre session Windows. Les saisonniers, stagiaires et contrats courts n'ont pas accès à la suite Office en version Bureau, ils peuvent accéder à la version Web |
| Office affiche « produit sans licence » ou « fonctionnalités désactivées » | Cliquez sur **Se connecter**. |

Si le problème persiste, écrivez au SI : **si@mercantour-parcnational.fr**, en précisant le nom de votre ordinateur et le message d'erreur affiché (une capture d'écran aide beaucoup).
