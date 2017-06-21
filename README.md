<img align="right" src="https://raw.githubusercontent.com/theodorosploumis/awesome-drupal/master/drupal.png" alt="Drupal 8 logo">

# Awesome Drupal 
[Edit](https://github.com/theodorosploumis/awesome-drupal/edit/master/README.md)

> A collection of awesome(\*) resources, tools, books, examples etc for Drupal CMS. Mainly focused on 8.x version.

This list aims to offer several resources that are, mostly, **not hosted on Drupal.org**. Unless other software and frameworks Drupal.org (D.O.) is a totally completed platform and has so much content on it, most of the times well organized and structured.

So, this guide is not a replacement for D.O. Consider this as a mini guide focused on advanced Drupal developers that already know how to use D.O. Resources are hand picked by me but any contribution will be appreciated.

**Contents**
------------

  - [Books](#books)
  - [Chatting channels](#chatting-channels)
  - [Cheatsheets](#cheatsheets)
  - [CI template examples](#ci-template-examples)
  - [Community](#community)
  - [Drupal.org](#drupalorg)
  - [Events](#events)
  - [Decoupled examples](#decoupled-examples)
  - [Hosting - PaaS](#hosting---paas)
  - [Hosting - Aegir](#hosting---aegir)
  - [News](#news)
  - [Podcasts](#podcasts)
  - [Provision](#provision)
  - [Scaffolding Tools](#scaffolding-tools)
  - [Tools](#tools)
  - [Tutorials](#tutorials)
  - [Videos](#videos)
  - [Social media](#social-media)

---

## Books
- [Enterprise Drupal 8 Development](http://www.apress.com/gp/book/9781484202548)
- [Drupal 8 Development Cookbook](https://www.packtpub.com/web-development/drupal-8-development-cookbook)
- [Programmer"s Guide to Drupal, 2nd Edition](http://shop.oreilly.com/product/0636920034612.do)
- [High Performance Drupal](http://shop.oreilly.com/product/0636920012269.do)
- [Drupal Watchdog magazine](https://drupalwatchdog.com/)

<p align="right">Go to <a href="#contents">TOC</a></p>

## Chatting channels
- [IRC](https://www.drupal.org/irc)

<p align="right">Go to <a href="#contents">TOC</a></p>

## Cheatsheets
- [Drupal 8 entity API](http://wizzlern.nl/sites/wizzlern.nl/files/artikel/drupal-content-entity-8.0.pdf)
- [Drupal 7 to 8](http://nuvole.org/sites/default/files/Drupal-7-to-Drupal-8-Cheatsheet.pdf)
- [Drupal 8 Configuration schema](http://hojtsy.hu/files/ConfigSchemaCheatSheet1.5.pdf)

<p align="right">Go to <a href="#contents">TOC</a></p>

## CI template examples
- [drush - .travis.yml](https://github.com/drush-ops/drush/blob/master/.travis.yml)
- [drush - circle.yml](https://github.com/drush-ops/drush/blob/master/circle.yml)
- [drupal-scaffold-docker - .travis.yml](https://github.com/drupal-composer-ext/drupal-scaffold-docker/blob/8.x/template/.travis.yml)
- [drupal-scaffold-docker - .gitlab-ci.yml](https://github.com/drupal-composer-ext/drupal-scaffold-docker/blob/8.x/template/.gitlab-ci.yml)
- [drupal core - phpcs.xml.dist](https://github.com/drupal/core/blob/8.4.x/phpcs.xml.dist)
- [DrupalCI: Drupal.org Testing Infrastructure](https://www.drupal.org/project/drupalci)
- [drupalcommerce/commerce - .travis.yml](https://github.com/drupalcommerce/commerce/blob/8.x-2.x/.travis.yml)
- [drupalcommerce/commerce - phpcs.xml](https://github.com/drupalcommerce/commerce/blob/8.x-2.x/phpcs.xml)
- [acquia/blt/- RoboFile.php](https://github.com/acquia/blt/blob/8.x/RoboFile.php)
- [Jenkins and SonarQube Drupal CI and Static Code Analysis](https://github.com/geerlingguy/drupalci-sonar-jenkins)
- [drupal_ti - Travis Integration for Drupal modules](https://github.com/LionsAd/drupal_ti)

<p align="right">Go to <a href="#contents">TOC</a></p>

## Community
- [Drupal.org Groups](https://groups.drupal.org)
- [Drupal Answers](https://drupal.stackexchange.com)
- [StackOverflow - Drupal topics](http://stackoverflow.com/documentation/drupal/topics)
- [Reddit Drupal](https://www.reddit.com/r/drupal)
- [Drupal on Meetup.com](https://www.meetup.com/topics/drupal)

<p align="right">Go to <a href="#contents">TOC</a></p>

## Drupal.org
- [Core](https://www.drupal.org/project/drupal)
- [Modules](https://www.drupal.org/project/project_module?f%5B0%5D=&f%5B1%5D=&f%5B2%5D=&f%5B3%5D=drupal_core%3A7234&f%5B4%5D=sm_field_project_type%3Afull&text=&solrsort=iss_project_release_usage+desc&op=Search)
- [Themes](https://www.drupal.org/project/project_theme?f%5B0%5D=&f%5B1%5D=&f%5B2%5D=drupal_core%3A7234&f%5B3%5D=sm_field_project_type%3Afull&text=&solrsort=iss_project_release_usage+desc&op=Search)
- [Distributions](https://www.drupal.org/project/project_distribution?f%5B0%5D=&f%5B1%5D=&f%5B2%5D=drupal_core%3A7234&f%5B3%5D=sm_field_project_type%3Afull&text=&solrsort=iss_project_release_usage+desc&op=Search)
- [Security advisories](https://www.drupal.org/security)
- [Core API](https://api.drupal.org/api/drupal)
- [Documentation](https://www.drupal.org/documentation)

<p align="right">Go to <a href="#contents">TOC</a></p>

## Events
- [Drupal Events](https://groups.drupal.org/events)
- [Drupical.com](http://www.drupical.com)

<p align="right">Go to <a href="#contents">TOC</a></p>

## Decoupled examples
- [Decoupled Drupal with GraphQL and React](https://github.com/fubhy/drupal-decoupled-app)
- [Elm web app with Headless Drupal backend](https://github.com/Gizra/elm-hedley)
- [Headless Drupal 8.x with Vue.js](https://github.com/isramv/headless-vue-drupal-8)
- [Decoupled Blocks - 8.x](https://www.drupal.org/project/pdb)
- [React-Pouch App - Drupal 8.x](https://github.com/emarchak/drupal-in-the-dark)
- [Decoupled Offline Drupal 8 using PouchDB and React](https://github.com/emarchak/agent008)
- [Drupal 8 multi-site factory with Integration of Angular2 and Ionic 2](https://github.com/fauconv/dcf)
- [Drupal Elm Starter](https://github.com/Gizra/drupal-elm-starter)
- [Drupal8 cordova app](https://github.com/CityWebConsultants/Drupal8-cordova-app)
- [Headless - Drupal 8 user operations as routes that support the JSON exchange format](https://github.com/nuxy/headless)
- [Ember-atha-cliath, Decoupled Drupal and Ember](https://github.com/prestonso/ember-atha-cliath)
- [Angular.js-based events calendar application, based on the headless/decoupled Drupal](https://github.com/idfive/UniCal)
- [drupalionic - Headless Drupal cordova app using Drupal 7 services for angular and ionic](http://www.drupalionic.org/)
- [AngularJS frontend for decoupled Drupal 7.x experiment](https://github.com/j-hannah/decoupled-drupal-angular)
- [Dangular - A progressively decoupled Angular 2 application proof of concept within Drupal 8](https://github.com/prestonso/dangular)
- [Drupal 7.x distribution for creating decoupled content management user experiences](https://github.com/riouxtherefore/editr)
- [Headless drupal 7.x, angular, ionic, cordova application](https://github.com/drogers98/HeadlessDrupalDemo)
- [Ionic application to connect with Drupal8 using REST](https://github.com/rteijeiro/ionic-headless-drupal8)
- [Ionic app to consume Drupal 7.x Services REST API](https://github.com/kevinblanco/drupal-ionic)
- [Starting point for an Ionic project using Drupal 7.x as the backend](https://github.com/marthinal/Drupionic)
- [Headless Drupal Framework](https://github.com/fourkitchens/headless-framework)
- [Headless Drupal using blessed](https://github.com/amitaibu/restful-blessed)

<p align="right">Go to <a href="#contents">TOC</a></p>

## Hosting - PaaS
- [Pantheon.io](https://pantheon.io/)
- [Acquia.com](https://www.acquia.com/)
- [Platform.sh](https://platform.sh/)
- [Amazee.io](https://www.amazee.io/)

<p align="right">Go to <a href="#contents">TOC</a></p>

## Hosting - Aegir
- [Omega8.cc](https://omega8.cc/)
- [Koumbit.org](https://www.koumbit.org/en/services/AegirVPS)
- [Praxis.coop](https://praxis.coop/en/aegirvps-pricing-and-options)

<p align="right">Go to <a href="#contents">TOC</a></p>

## News
- [Drupal Planet](https://www.drupal.org/planet)
- [Theweeklydrop.com](http://www.theweeklydrop.com)

<p align="right">Go to <a href="#contents">TOC</a></p>

## Podcasts
- [Talking Drupal](http://www.talkingdrupal.com)
- [Lullabot Podcast](https://www.lullabot.com/podcasts)
- [Acquia Podcasts](https://dev.acquia.com/learn?type_1=podcast)
- [DrupalEasy Podcast](https://www.drupaleasy.com/podcast)

<p align="right">Go to <a href="#contents">TOC</a></p>

## Provision

### Ansible
- [Ansible Drupal roles](https://galaxy.ansible.com/list#/roles?autocomplete=drupal)

### Chef
- [Chef Cookbooks - Drupal](https://supermarket.chef.io/cookbooks?q=drupal)

### Puppet
- [Puppet Drupal](https://forge.puppet.com/tags/drupal)

### SaltStack
- [SaltStack Drupal formula](https://github.com/saltstack-formulas/drupal-formula)

### Terraform
- [Terraform - HAProxy, Drupal and Mysql](https://github.com/enxebre/atlas-terraform-HAProxy-drupal)
- [neilmillard/terraform-drupal](https://github.com/neilmillard/terraform-drupal)
- [Terraform setup for drupal nginx , mysql php on AWS](https://github.com/iahmad-khan/terraform-aws-lemp-cvicrm)

### Vagrant
- [Vagrant Boxes - Drupal](https://atlas.hashicorp.com/boxes/search?q=drupal)

### Other/Several
- [Provision of drupal lamp stack](https://github.com/ec-europa/infra)
- [Provisioning a simple PHP/Drupal dev environment](https://gist.github.com/dickolsson/45f06e85f8a8e57eaf23)

<p align="right">Go to <a href="#contents">TOC</a></p>

## Scaffolding Tools
 - [Composer Plugin for updating the Drupal scaffold files when using drupal/core](https://github.com/drupal-composer/drupal-scaffold)
 - [A Drupal 7/8 websites scaffolder built on composer](https://github.com/kgaut/drupal-site-scaffolder)
 - [Yeoman MarionetteJS + Drupal generator](https://github.com/enzolutions/generator-marionette-drupal)
 - [Scaffold a headless Drupal backend, Angular app client and Behat tests](https://github.com/Gizra/generator-hedley)
 - [Scaffold a AngularJS app, to make headless with Drupal Backend](https://github.com/omero/generator-angular-drupal)
 - [LCM Drupal 8 Scaffolding](https://github.com/LastCallMedia/Drupal-Scaffold)
 - [A springboard project for new Drupal 8 projects](https://github.com/reallifedigital/drupal-scaffold)
 - [Yeoman generator for Drupal 8 Themes](https://github.com/mediacurrent/theme_generator_8)
 - [Yeoman generator web starter drupal8](https://github.com/forumone/generator-web-starter-drupal8)
 - [Minimalist approach to scaffolding a Drupal site](https://github.com/kalamuna/kalascaffold)
 - [Yeoman generator for a Drupal theme](https://github.com/pixelmord/generator-drupaltheme)
 - [A yeoman generator to start the foundation of any Drupal theme](https://github.com/frontend-united/generator-drupal-theme)
 - [Yeoman generator for generating a Drupal 7 entity boilerplate code](https://github.com/badri/generator-drupalentities)
 - [Yeoman Generator: Drupal 7 Gulp Starter Theme](https://github.com/supermoos/generator-drupal-gulp)
 - [Yeoman generator for drupal modules](https://github.com/davidmaneuver/generator-drupalmodule)
 - [A Yeoman generator for generating a Drupal VM stack](https://github.com/kevinquillen/generator-drupalvm)
 - [Yeoman generator for the Prototype Drupal theme](https://github.com/AtenDesignGroup/generator-center-subtheme)
 - [drupal-scaffold-docker](https://github.com/drupal-composer-ext/drupal-scaffold-docker)

<p align="right">Go to <a href="#contents">TOC</a></p>

## Tools
- [Drupal related Tools](https://drupaltools.github.io/)
- [Drupal Integrations](https://drupalintegration.com/)
- [D.O. - Development tools overview](https://www.drupal.org/docs/develop/development-tools/development-tools-overview)
- [Dreditor](https://dreditor.org/)

<p align="right">Go to <a href="#contents">TOC</a></p>

## Tutorials
- [Drupalize.me](https://drupalize.me)
- [BuildAModule](https://buildamodule.com)
- [KNP University](https://knpuniversity.com/tracks/drupal)
- [WDTutorials](http://www.wdtutorials.com/drupal)
- [OSTraining](https://www.ostraining.com/drupal-training)

<p align="right">Go to <a href="#contents">TOC</a></p>

## Videos
- [DrupalCon sessions](https://www.youtube.com/user/DrupalAssociation/videos)

<p align="right">Go to <a href="#contents">TOC</a></p>

## Social media
- [Twitter](https://twitter.com/drupal)
- [Facebook](https://www.facebook.com/Drupal-8427738891)

<p align="right">Go to <a href="#contents">TOC</a></p>

---

## License
![cc0 logo](https://raw.githubusercontent.com/theodorosploumis/awesome-drupal/master/cc0logo.png)

_(Logo used on top is a Drupal trademark and so it's not under CC0 license)_

Drupal is a [registered trademark](http://drupal.com/trademark) of [Dries Buytaert](http://buytaert.net/).

## Similar projects
- [mrsinguyen/awesome-drupal](https://github.com/mrsinguyen/awesome-drupal)
- [nirgn975/awesome-drupal](https://github.com/nirgn975/awesome-drupal)
- [Lullabot/awesome-d8](https://github.com/Lullabot/awesome-d8)

<p align="right">Go to <a href="#contents">TOC</a></p>
