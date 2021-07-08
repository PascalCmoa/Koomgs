# Koomgs

Koomgs est un site de présentation des oeuvres de l'artiste numérique freelance connu sous le pseudo Koomgs.

## Environnement de développement

### Pré-requis

* PHP 7.4
* Composer
* Symfony CLI
* Docker
* Docker-compose

Vous pouvez vérifier les pré-requis (sauf Docker et Docker-compose) avec la commande suivante (de CLI Symfony) :
'''bash
symfony check:requirements
'''

### Lancer l'environnement de développement
'''bash
docker-compose up -d
symfony serve -d
'''
