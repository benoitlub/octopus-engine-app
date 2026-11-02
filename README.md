# Octopus Engine App — variante historique

Le moteur maintenu et son workflow de déploiement se trouvent dans
[benoitlub/octopus-engine](https://github.com/benoitlub/octopus-engine).

Ce dépôt est une variante historique : il conserve du code et des documents
communs au moteur, avec quelques différences. Il n'est pas une seconde référence
à modifier en parallèle pour les corrections courantes.

Le nom de service Cloudflare `octopus-engine-app` est distinct du nom du dépôt.
Le workflow du dépôt `octopus-engine` peut déployer ce service. Avant toute
modification de la source ou du nom de service, vérifier ce workflow et
`wrangler.toml`, ainsi que les bindings Publisher.

Aucun code historique n'est supprimé ici. Une éventuelle consolidation doit
préserver les différences utiles et les références des consommateurs.
