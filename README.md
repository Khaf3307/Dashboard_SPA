# Dashboard_SPA
## About The Project


`laravel-vue-dashboard` is a Single Page Application (SPA) dashboard
built with [Laravel 8](https://laravel.com), [Vue.js](https://vuejs.org/) and [Bootstrap 4](https://getbootstrap.com) ([SB Admin Template](https://github.com/StartBootstrap/startbootstrap-sb-admin-2)). Thanks to the combination of the power of Laravel and the speed of Vue.js it is an excellent full-stack starter kit for enterprise applications.
 
 
It's a kit to start from scratch, not a Laravel package. It can help you to cut down your time by having an SPA dashboard with authentication system ready to use, taking advantage of [Laravel Passport](https://laravel.com/docs/8.x/passport) that uses the oauth2 authentication protocol.
 
The project provides sample pages, uses the routing system of Vue.js and Vuex for maintaining the application state.<br>
The code is structured in such a way to make it easy to modify and add new pages, components and APIs.


<!-- FEATURES -->
## FEATURES

* Sigle page application (SPA)
* Laravel 8
* [Vue.js](https://vuejs.org/) + VueRouter (configured with auth restricted pages) + Vuex 
* Login, register, email verification (optional) and resend, recovery password systems
* Ui with Bootstrap 4 and [SB Admin Template](https://github.com/StartBootstrap/startbootstrap-sb-admin-2)
* Sample views to get started
* Easy to add new pages and routes 
* Notification system
  
## Commencer

### Conditions préalables

<ul>
    <li>Votre machine doit être prête pour les dernières versions Laravel et Node.js.</li>
</ul>

## Mise en place


   ```sh
    # Cloner le projet
    git clone https://github.com/ramoncrisante/laravel-vue-dashboard.git

    # Entrer dans le répertoire du projet
    cd laravel-vue-tableau de bord

    # Copiez le fichier env et ajoutez votre propre base de données et vos identifiants de messagerie
    cp .env.exemple .env

    # Installer la dépendance
    installation du compositeur

    # Générer une clé d'application
    clé artisan php:générer
    
    # Migrer la base de données
    migration artisanale php

    # Créer des clés de chiffrement
    passeport artisan php:installer

    # Installer la dépendance avec NPM
    installation npm

    # Développer
    npm run dev # ou npm run watch

    # Construire sur la production
    production d'exécution npm
    
    # Application de service
    service artisanal php

   ```

## Configuration

* La vérification des e-mails est facultative et est désactivée par défaut.
  Pour l'activer, modifiez le paramètre suivant dans le fichier `.env`
  
  `MUST_VERIFY_EMAIL=true`

* Pour utiliser la fonctionnalité de vérification des e-mails et de réinitialisation du mot de passe, il est nécessaire de configurer le service de messagerie.
  Afin d'envoyer des e-mails avec succès, nous devons fournir `MAIL_DRIVER`, `MAIL_HOST`, `MAIL_PORT`, `MAIL_USERNAME`, `MAIL_PASSWORD` dans le fichier `.env`.


## Construit avec

* [Laravel 8] (https://laravel.com)
* [Vue.js](https://vuejs.org/)
* [Vuex](https://vuex.vuejs.org/)
* [Bootstrap 4] (https://getbootstrap.com)
* [Modèle d'administrateur SB] (https://github.com/StartBootstrap/startbootstrap-sb-admin-2)
* [JQuery](https://jquery.com)
* [Axios](https://github.com/axios/axios)
* [Passeport Laravel] (https://laravel.com/docs/8.x/passport)
* [Font Awesome 5] (https://fontawesome.com/)
