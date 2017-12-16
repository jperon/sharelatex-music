# sharelatex-music

Dockerfile pour ShareLaTeX, avec Gregorio (pour les partitions grégoriennes) et LilyPond (pour les partitions classiques).

## Installation

Une fois Docker installé (cf. la documentation de [Docker](https://www.docker.com/) pour votre système), vous pouvez lancer ShareLaTeX grâce à la commande :

```
docker-compose -f docker-compose.yml up
```

Auparavant, vous pouvez modifier ce fichier pour l'adapter à vos besoins, notamment pour ce qui concerne le port d'écoute et les dossiers de stockage.

## Première étape

Si vous avez laissé le port à sa valeur par défaut, rendez-vous à l'adresse http://localhost:5000/launchpad.

Pour le reste, voyez [la documentation de ShareLaTeX](https://github.com/sharelatex/sharelatex/wiki)

# English

Dockerfile for sharelatex with Gregorio and LilyPond, which uses `docker-compose` to get things up.
Please refer to documentation of [Docker](https://www.docker.com/) and [ShareLaTeX](https://github.com/sharelatex/sharelatex/wiki) to start.
