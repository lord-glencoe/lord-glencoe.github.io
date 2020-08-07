---
title:  "Mon curriculum vitæ"
date:   2020-08-07 19:40:23
categories: [jekyll]
permalink: /cv-fra/
layout: post
---
Je suis un administrateur système et un développeur Full Stack, passionné par Ruby on Rails, l'optimisation de performance et les pratiques DevOps. J'ai un baccalauréat en informatique et plus de 15 ans d'expérience dans ce domaine.

#### **Résumé des compétences en TI**
---
**Gestion de l'infrastructure :** Terraform, Ansible, Capistrano  
**Conteneurs & Orchestration :** Docker, Packer, Helm, Kubernetes  
**Infonuagique :** AWS, Scaleway  
**Intégration continue/Livraison continue :** GitHub Actions, CircleCI, Gitlab CI, Codeship  
**Surveillance :** DataDog, Prometheus, Grafana  
**Serveurs Application & Web :** Passenger, Puma, Unicorn, Nginx, Apache  
**Bases des données :** MySQL, PostgreSQL, Redis, ElasticSearch, Kafka, Microsoft SQL Server, Sphinx  
**Langages de programmation :** Ruby, JavaScript, Go, C#, Python  
**Backend :** Ruby on Rails. ActionCable, ActiveStorage, ActiveJob. GraphQL API, Rest API. Sidekiq, Devise, OAuth,
RubySAML, Pundit, CanCanCan, Doorkeeper, Geocoder, Ransack, Paperclip, Carrierwave  
**Frontend :** React.js. Redux, Router, Server Side Rendering. Bootstrap, Zurb Foundation, Semantic UI  
**Testing :** TDD/BDD with RSpec/Capybara. Rspec-performance, Minitest  

#### **Expérience professionnelle**  
---
**Site Reliability Engineer (remote). Smile Inc**,  
Kitchener, Canada  
01/2020 - present

##### Responsabilités :
* Développer de nouveaux modules Terraform pour l'infrastructure AWS de Smile.io
* Migrer les applications Heroku existantes vers la nouvelle infrastructure
* Améliorer la fiabilité du système
* Participer à un horaire de garde hebdomadaire

##### Réalisations :
* Migration d'un microservice business intelligence de Heroku vers Kubernetes (EKS):
  * dockerisation de l'application
  * création d'un Helm chart avec les hooks de migration de base de données
  * création de plusieurs modules Terraform pour générer et publier le Helm chart, et pour gérer les autorisations de la base de données (PostgreSQL)
  * automatisation du déploiement de l'application dans les environnements staging et production en utilisant CircleCI et Terraform
* Migration de zone DNS de DNSimple à AWS Route53
* Création d'une Action GitHub CI/CD afin de tester et publier les gems internes sur GitHub Packages


**Développeur Full Stack. Pyx4 Inc**,  
Montréal, Canada  
04/2018 - present

##### Réalisations :

* Construction d'une équipe de développeurs qualifiés
* Amélioration significative du processus de développement par la création d'un pipeline de CI/CD avec
  la construction d'une image docker de l'application, les tests et le déploiement automatisés, ainsi que
  l'introduction de révisions de codes et l'ajout de lignes directrices en matière de documentation
* Développement d'une API GraphQL pour le projet Dashboard, dockerisation et installation du
  application sur l'environnement isolé pour le client
* Développement d'un module de connexion permettant d'importer et d'authentifier les utilisateurs à partir des annuaires compatibles LDAP, tels qu'Active Directory
* Développement d'un moteur de formulaire générique permettant aux clients de personnaliser les différents formulaires en fonction de leurs besoins
* Correction de plusieurs failles de sécurité, ce qui a permis à l'entreprise de passer un audit de sécurité et de signer un contrat important
* Géstion d'infrastructure pour différents environnements : production, production on-premise, staging, AQ, test
* Participation à l'horaire de garde


**Développeur Ruby on Rails, Mentel Inc.**  
Montréal, Canada  
07/2017 - 04/2018

* Création d'un module universel pour paralléliser les requêtes de récupération en utilisant Net::HTTP + Mutex
* Calculs financiers testés et ajustés pour tableaux SIP, rapports de performance, comptes FIA
* Optimisation et mise en cache des requêtes de base de données, réduisant les temps de chargement des pages les plus chargées de 28 s à 200-300 ms.
* Mise à jour et maintenance de la suite de tests RSpec, introduction des tests d'intégration (capybara)
* J'ai fourni le soutien nécessaire aux clients de DevOps : Configuration NGINX/Puma (A+ sur SSLabs test), Heroku, AWS : RDS, EC2, S3, équilibrage de charge
* Dans des délais serrés, débogué et corrigé un grand nombre de problèmes complexes
* Promotion du BDD/TDD et de la révision du code, mentorat de collègues

**Développeur Full Stack, Retrigo Inc.**  
Montréal, Canada  
07/2017 - 04/2018

_Prestataire Independant (Teletravail)_

* Développement d'un site Web [Retrigo.com](https://retrigo.com) pour un client. Quelques-uns des faits saillants :
  * API AdaptivePayments Paypal intégrée, incluant le traitement automatisé des remboursements et la prise en charge de plusieurs devises.
  * Complètement changé le frontend pour répondre à la nouvelle conception sur mesure
  * Création de plus de 600 tests unitaires et d'intégration pour les parties centrales de l'application
  * Serveur web provisionné pour la production : Debian 9, NGINX/Unicorn, Capistrano
* Révision du code et mentorat pour les développeurs du client

**Développeur Ruby on Rails, Trendigo Inc.**  
Montréal, Canada  
12/2016 - 07/2017

* Développement d'une galerie de promotion géolocalisée : Géocodeur, API JavaScript de Google Maps
* Intégration avec l'API de traitement des cartes de crédit
* Intégration avec l'API back-office de l'entreprise (Microsoft.NET Web API)
* Optimisation du temps de chargement des pages : de 4 s à 100-200 ms
* Ajouté l'authentification OAuth avec Facebook et Google+.
* Serveur de production géré. Debian, NGINX, Passenger, Redis.
* Développement d'une application mobile multiplateforme en Xamarin.Forms (C#). L'application partage environ 90% du code entre les deux plates-formes (iOS et Android) et a été développée en moins de trois mois, de zéro à la production.

**Administrateur de système, Sportmaster Ltd.**  
Moscou, Russie  
2006 - 2016

* Installation, configuration, mise à niveau de serveurs, réseaux, PBX, POS et
  matériel et logiciel de poste de travail dans 10+ magasins de vente au détail comme le seul système
  administrateur dans la branche régionale de la société
* Travaillé avec l'équipement des fournisseurs suivants: HP, Cisco, Huawei, Panasonic, Cipher, Epson
* Assistance technique fournie aux utilisateurs (plus de 150 postes de travail)
* Facilitation du lancement de plus de 10 magasins de détail et entrepôts, fournissant un soutien technique sur toutes les étapes de l'installation du matériel à la personnalisation des logiciels et à l'éducation des membres du personnel
* A facilité le lancement de plus de 10 magasins de détail et entrepôts, en fournissant un soutien technique à toutes les étapes, de l'installation du matériel à la personnalisation des logiciels et à la formation des membres du personnel
* Participation à l'horaire de garde pour presque 10 ans

#### **Formation**

##### Certificate Proficiency in Professional Bilingual Communication
Université McGill  
2019 - présent

##### Optimisation de Ruby on Rails
École en ligne pour développeurs Thinknetica.com
2020 - présent

##### Développement Professionnel Web en Ruby on Rails
École en ligne pour développeurs Thinknetica.com
2015 - 2016

##### Cisco CCNP Route
2015

##### Cisco CCNA Exploration
Université d'État de Tomsk des Systèmes de Contrôle et de Radioélectronique
2012

##### Baccalauréat en Informatique
Université Technique d'État de Kemerovo
2001 - 2006

#### **Loisirs**
* Programmation d'ordinateurs
* Psychologie
* Getting things done
* Apprendre des langues étrangères

Si vous êtes intéressé à apporter mon expérience à votre projet, n'hésitez pas à me contacter à [alex@kudashkin.pro](mailto:alex@kudashkin.pro), skype: [a.kudashkin](skype:a.kudashkin?call), tél.: (438)403-8624. Il me fera plaisir de vous aider à développer le succès de votre entreprise.
