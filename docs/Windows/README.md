# Mon profil Windows

Selon votre poste et la politique d'équipement de votre service, on a configuré pour vous soit un profil fixe sur un PC (en général portable) mis à votre disposition ou bien un profil itinérant qui vous permet de vous connecter sur n'importe quel PC de votre site.

## Les profils fixes
Avec un profil fixe, vos préférences mail et navigateur sont enregistrées sur votre PC, de même que les documents que vous choisissez d'enregistrer sur le PC.  
Attention, ces documents ne sont pas partagés avec vos collègues ni automatiquement sauvegardés, il est conseillé d'utiliser le disque réseau de votre site ou du siège pour enregistrer les documents
dans un espace partagé ou votre espace personnel.  
L'intérêt des profils fixes, c'est que les sessions s'ouvrent et se ferment rapidement, car les données restent sur le PC.  
Si vous changez de PC, vous devez configurer l'environnement (mail, navigateur, etc).

## Les profils itinérants
Avec un profil itinérant, toutes vos préférences et vos données résident sur le serveur de votre site et sont téléchargées sur le PC lorsque vous ouvrez une session. A l'inverse, vos données de travail sont resynchronisées avec le serveur de site lorsque vous fermez votre session Windows.
L'intérêt de ce mode de fonctionnement est que vous retrouvez votre environnement de travail habituel sur n'importe quel PC lorsque vous arrivez dans le bureau, y compris l'un des PC attribués à un collègue. Et contrairement à votre PC, le serveur est sauvegardé.  

Mais il y a aussi des inconvénients si l'on n'applique pas strictement quelques règles qu'il est important de connaître:

- Faire en sorte que la taille du profil reste raisonnable en évitant d'enregistrer des fichiers volumineux sur le bureau ou dans les répertoires Documents, Téléchargements, Images, etc.
- Ne pas ouvrir de session sur un ordinateur tant que la session précédemment ouverte sur un autre ordinateur n'est pas complètement synchronisée. Autrement dit, il est risqué de basculer rapidement d'un pc à un autre.
- Ne pas ouvrir de session lorsque vous êtes sur un autre site (même avec la fibre, il faut du temps pour copier votre profil d'un site à l'autre).

Les problèmes, lorsqu'ils apparaissent, se manifestent par des sessions très lentes à ouvrir ou fermer, puis par des désynchronisations entre le serveur et un ou plusieurs PC.

## Quel type de profil pour moi?
- On vous a attribué un PC portable, votre profil est automatiquement configuré comme fixe.

- On ne vous a pas attribué de PC, mais vous utilisez toujours le même PC. Dans ce cas, vous pouvez demander que votre profil soit configuré comme un profil fixe. Vous perdrez la flexibilité des profils itinérants, mais vous gagnerez sur le temps d'ouverture/fermeture de session.
- On ne vous a pas attribué de PC, et vous utilisez alternativement plusieurs PC. Dans ce cas, votre profil est itinérant.

## J'ai un profil itinérant et cela ne marche pas bien
Votre profil est trop gros et ne se synchronise plus avec le serveur.  
- Connectez-vous sur le dernier PC que vous avez utilisé,
- identifiez les fichiers volumineux que vous avez mis sur le bureau, dans `Documents`, les téléchargements, les images et vidéos,
- Déplacez ces fichiers sur votre serveur de site ou effacez-les s'ils ne sont plus utiles.
- Fermez votre session et contactez le SI pour un contrôle de la synchronisation entre le PC et le serveur.
