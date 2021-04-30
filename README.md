# Anne's Galery


### Situation du projet | partie I

Anne est une personnalité de renom réconnue pour son talent photographique. Elle est sollicitée par plusieurs compagnies qui, parfois, utilisent ses oeuvres dans le but de faire des campagnes publicitaires.

Toutefois, elle est de plus en plus attaquée en matière de droits d'auteurs; ses oeuvres sont utilisées `sans son consentement`. Elle a eu plusieurs fois eu recours aux services juridiques de son pays La Côte d'Ivoire mais rien n'a pu réduire le risque d'attaque à ses droits d'auteurs.

Et un jour, une de ses amies lui a parlé d'un groupe de développeurs de l'établissement Ivoire Geek School. Ces jeunes développeurs aux compétences multiples ont été conviés à une réunion avec Anne afin de détecter et trouver une solution à son problème.

Après une longue causerie de 2h, les jeunes développeurs ont été convaincus de `la création d'une plateforme web qui devra permettre à Anne de stocker ses photos en un lieu sûr`. 
Les points suivants ont été notés comme importants:
- **Donner la possibilité de télécharger ses oeuvres uniquement aux personnes authentifiées**
- **Permettre la recherche de ses oeuvres à tout le monde**
- **Permettre aux utilisateurs authentifiés de pouvoir ajouter une photo à leurs favoris**
- **Permettre à tout le monde de pouvoir effectuer une recherche par catégorie**
- **Les utilisateurs s'inscrivent uniquement avec leurs noms, prénoms, email, nom d'utilisateur, mot de passe**
- **Les utilisateurs se connectent uniquement par nom d'utilisateur et mot de passe**
- **Anne voudrait avoir un espace où elle et son modérateur pourront ajouter, modifier, (supprimer) ses oeuvres, SEULE ANNE EST ABILITE A SUPPRIMER TOUT/PARTIE DE SES OEUVRES**
- **Les oeuvres téléchargées doivent être limitées à 3 auquel cas, un message d'alerte doit s'afficher**

### Situation du projet | partie II

Anne demande aux jeunes développeurs de mettre son projet en ligne.
Votre solution -> heroku

## Design
Vous etes free dans le choix de vos designs

## Contraintes techniques annexes du projet
Tailwindcss, JQuery/Ajax


## Ressources
L'authentification est déjà installée avec des informations pas trop nécessaires

## Conseils
- **Prendre son temps pour comprendre le sujet de traiter**
- **Faire des recherches sur chaque module/fonctionnalité à intégrer**

## COMMENT DEMARRER LE PROJET ?
- `git clone https://github.com/PROMO-IGS-2020-2021/anne-galery`
- `cd anne-galery`
- `composer install`
- `creer une base de données et donner lui le nom anne_galery`
- `php artisan migrate`

- Ouvrir deux terminaux:
 1   - `npm run watch`
 2   - `php artisan serve`


## License

Ce projet est purement à titre éducatif sous [MIT licence](https://opensource.org/licenses/MIT) de [Ivoire Geek School](https://ivoiregeekschool.com).
