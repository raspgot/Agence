# Agency 

Une Agence Immobilière en ligne

## Démo

[Voir la démo](https://perso.raspgot.fr/Agence/public/index.php) *Hebergement à domicile*


## Installation

Se placer dans le répertoire **htdocs** (WAMPP) ou **/var/www/html** (LINUX)
```
git clone https://github.com/raspgot/Agence
composer install
```
**.env** à modifier
```
php bin/console doctrine:database:create
php bin/console doctrine:schema:update --force
php bin/console cache:clear
php bin/console server:run
```
Se rendre a l'adresse:  **http://127.0.0.1:8000/**

## API Reference

* [Symfony 4.1.7](https://github.com/symfony/symfony) - A PHP framework for web applications and a set of reusable PHP components.
* [Swiftmailer](https://github.com/swiftmailer/swiftmailer) - A component based mailing solution for PHP 7.
* [Bootstrap 4.1.3](https://github.com/twbs/bootstrap) - Sleek, intuitive, and powerful front-end framework for faster and easier web development.
* [Jquery 3.3.1](https://github.com/jquery/jquery) - The Write Less, Do More, JavaScript Library.
* [Mdbootstrap](https://github.com/mdbootstrap/bootstrap-material-design) - Material Design for Bootstrap 4.
* [Sass](https://github.com/sass/sass) - Sass makes CSS fun again.
* [Git](https://github.com/git/git) - --distributed-even-if-your-workflow-isnt

## Auteur

[Raspgot](https://raspgot.fr)
