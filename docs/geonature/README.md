# FAQ GeoNature

la gestion fonctionnelle de GeoNature est sous la responsabilité des référents GeoNature (CGP). La gestion technique est assurée par le SI. Plus d'info sur la page [Exploitation](./exploitation.md).

## Je n'ai pas de compte GeoNature

Adressez-vous à un référent GeoNature (CGP) ou au SI pour demander l'ouverture d'un compte.

## J'ai un compte GeoNature mais mes droits d'accès sont insuffisants

Adressez-vous en priorité à un référent GeoNature qui vous donnera les droits en lien avec votre poste. Vous pouvez aussi en parler au SI.

## GeoNature ou Occtax mobile ne fonctionne pas

Adressez-vous au SI pour signaler un dysfonctionnement d'un module GeoNature.
Vous pouvez [installer Occtax mobile](#occtax-mobile) vous-mêmes ou demander l'aide du SI.

## Je ne parviens pas à modifier une observation Occtax après l'avoir saisie

En principe, les observations peuvent être modifiées après coup par la personne qui les a saisies ou par un administrateur. Il faut éditer le relevé Occtax dans l'interface web de GeoNature,
puis sélectionner et éditer le taxon enregistré. Si le bouton `modifier ce taxon` est inactif, cliquer sur `avancé` et remplir les informations requises (il arrive en effet que le déterminateur soit manquant pour les taxons saisis avec Occtax mobile). Les référents GeoNature et le SI peuvent aussi vous aider à mettre à jour l'observation.

## Occtax mobile

occtax2 (icone vert foncé) est une nouvelle version d'occtax mobile qui coexiste avec les versions de sync et d'occtax (icone vert plus clair) actuellement en service.

occtax2 est relié à un nouveau Geonature [https://geonature.mercantour.eu/geonature](https://geonature.mercantour.eu/geonature) qui remplace progressivement l'ancien serveur [https://geonature.mercantour-parcnational.fr](https://geonature.mercantour-parcnational.fr) .

Pour installer occtax2:

- Télécharger l'application depuis [https://geonature.mercantour.eu/geonature/api/media/mobile/occtax/occtax-2.6.2-generic-release.apk](https://geonature.mercantour.eu/geonature/api/media/mobile/occtax/occtax-2.6.2-generic-release.apk) par exemple en sélectionnant le lien depuis le navigateur de votre mobile et en sauvegardant le téléchargement du fichier apk.
- Installer l'application sur le mobile.
- Lancer l'application en indiquant [https://geonature.mercantour.eu/geonature](https://geonature.mercantour.eu/geonature) comme URL de Geonature dans les paramètres.
- Se connecter (avec votre identifiant et mot de passe Geonature). Si vous ne parvenez pas à vous connecter, c'est que vous n'avez pas les droits. Contacter un référent Geonature (CGP) ou le SI pour que les droits nécessaires vous soient attribués.
- Réouvrir les paramètres en indiquant le jeu de données par défaut parmi les jeux de données proposés et l'observateur par défaut (vous).

### Il manque des observateurs ou un jeu de données dans Occtax mobile

- Sélectionner **Mettre à jour les données** qui a pour effet de télécharger sur l'application mobile la liste des utilisateurs, jeux de données et taxons ouverts à la saisie.
- Si cela ne suffit pas, contacter un référent Geonature (CGP) ou le SI.

### Le taxon que j'ai observé n'est pas ouvert à la saisie dans Occtax Mobile

Adressez vous à un référent GeoNature (CGP) qui ouvrira le taxon à la saisie ou vous indiquera le taxon valide qui correspond à votre observation. Ne demandez pas au SI qui n'a pas les connaissances requises pour valider votre demande.

### Comment créer un jeu de données

Le module Métadonnées permet de créer et modifier des cadres d'acquisition et des jeux de données. L'accès à cette fonctionnalité est réservé aux [gestionnaires GeoNature](exploitation.md#gestionnaires).  
[Documentation du module Métadonnées](https://docs.geonature.fr/user-manual.html#metadonnees)

### Comment importer des observations dans GeoNature

Le module d'import permet d'importer des données dans GeoNature à partir d'un fichier csv. L'accès à cette fonctionnalité est réservé aux [gestionnaires GeoNature](exploitation.md#gestionnaires).

- Créer un jeu de données en prenant soin d'associer le module `import` au jeu de données (pour que ce jeu de données soit utilisable dans l'import qui va suivre).
- Ouvrir le module `import`, sélectionner le jeu de données à utiliser, le fichier à importer et définir la correspondance entre la structure des données à importer et celle de GeoNature (par commodité, la correspondance peut être sauvegardée pour être réutilisée ultérieurement).

[Documentation du module import](https://github.com/PnX-SI/gn_module_import/tree/master?tab=readme-ov-file#utilisation-du-module-dimports)
