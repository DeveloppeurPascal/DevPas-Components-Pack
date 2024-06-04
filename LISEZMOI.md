# Librairies et packs de composants de DeveloppeurPascal en un seul dépôt

[This page in english.](README.md)

Regroupement des dépôts permettant d'ajouter des fonctionnalités sous forme de librairies ou de composants à Delphi.

A utiliser si vous désirez installer tous mes packs de composants en une seule fois au lieu de les faire un par un.

Il contient des projets développés en langage Pascal Objet sous Delphi. Vous ne savez pas ce qu'est Dephi ni où le télécharger ? Vous en saurez plus [sur ce site web](https://delphi-resources.developpeur-pascal.fr/).

## Installation

Si vous téléchargez un fichier ZIP depuis GitHub il sera vide. Vous devez utiliser la commande "git" ou une interface utilisateur dédiée pour cloner ou dupliquer ce dépôt et ses sous-modules.

Après avoir cloné le dépôt n'oubliez pas de mettre à jour les projets liés avec cette commande :

```bash
git submodule update --remote
```

Si vous n'avez pas cloné le projet avec ses sous-modules vous devrez saisir les commandes suivantes :

```bash
git submodule init
git submodule update --remote
```

[Ce dépôt de code](https://github.com/DeveloppeurPascal/DevPas-Components-Pack) et tous ses sous-projets sont disponibles sur [mon compte GitHub](https://github.com/DeveloppeurPascal).

## Licence

Ce projet est sous licence MIT. Ce n'est pas le cas de mes autres projets. Regardez leurs fichiers LICENSE et README.md (ou LISEZMOI.md) avant de faire des bêtises.

## Comment demander une nouvelle fonctionnalité, signaler un bogue ou une faille de sécurité ?

Si vous voulez une réponse du propriétaire de ce dépôt la meilleure façon de procéder pour demander une nouvelle fonctionnalité ou signaler une anomalie est d'aller sur [le dépôt de code sur GitHub](https://github.com/DeveloppeurPascal/DevPas-Components-Pack) et [d'ouvrir un ticket](https://github.com/DeveloppeurPascal/DevPas-Components-Pack/issues).

Si vous avez trouvé une faille de sécurité n'en parlez pas en public avant qu'un correctif n'ait été déployé ou soit disponible. [Contactez l'auteur du dépôt en privé](https://developpeur-pascal.fr/nous-contacter.php) pour expliquer votre trouvaille.

## Supportez ce projet et son auteur

Si vous trouvez ce dépôt de code utile et voulez le montrer, merci de faire une donation [à son auteur](https://github.com/DeveloppeurPascal). Ca aidera à maintenir le projet (codes sources et binaires).

Vous pouvez utiliser l'un de ces services :

* [GitHub Sponsors](https://github.com/sponsors/DeveloppeurPascal)
* [Liberapay](https://liberapay.com/PatrickPremartin)
* [Patreon](https://www.patreon.com/patrickpremartin)
* [Paypal](https://www.paypal.com/paypalme/patrickpremartin)

ou si vous parlez français vous pouvez [vous abonner à Zone Abo](https://zone-abo.fr/nos-abonnements.php) sur une base mensuelle ou annuelle et avoir en plus accès à de nombreuses ressources en ligne (vidéos et articles).

## Packs de projets

Afin de me simplifier les sauvegardes du compte GitHub ou l'installation locale de projets je propose plusieurs packs de dépôts thématiques. Vous pouvez les utiliser pour télécharger les projets concernés et les consulter. Il est probable qu'ils ne soient pas compilables tels quels mais ça vous donnera une idée des projets open sources disponibles sur [mon compte GitHub](https://github.com/DeveloppeurPascal) et vous pourrez toujours y accéder directement.

* [jeux vidéos](https://github.com/DeveloppeurPascal/DevPas-Games-Pack)
* [utilitaires et applications mobiles](https://github.com/DeveloppeurPascal/DevPas-WorkingPrograms-Pack)
* [librairies et composants](https://github.com/DeveloppeurPascal/DevPas-Components-Pack)
* [l'intégralité des projets publics de mon compte](https://github.com/DeveloppeurPascal/_AllProjects)

Pour préparer mon environnement de travail de développeur Delphi sur un nouvel ordinateur ou une nouvelle VM sous Windows j'ai également prévu [un script d'installation](https://github.com/DeveloppeurPascal/__MyMinimalDependenciesForWorkingWithDelphi). Vous pouvez l'utiliser tel quel ou vous en inspirer si vous utilisez mes librairies ou composants.

Si vous êtes plutôt à la recherche d'exemples et de démos pour savoir comment utiliser certaines fonctionnalités de Delphi regardez [ce dépôt de code](https://github.com/DeveloppeurPascal/Delphi-samples) et [sa liste d'autres dépôts d'exemples](https://github.com/DeveloppeurPascal/Delphi-samples/blob/main/OtherDelphiSampleRepositories.md).
