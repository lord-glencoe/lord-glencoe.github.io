---
title:  "My curriculum vitæ"
date:   2019-09-29 19:40:23
categories: [jekyll]
permalink: /cv-eng/
layout: post
---
I am a System Administrator and a Full Stack Developer, passionate about Ruby on Rails, performance optimization and DevOps. I have a Bachelor's degree in Computer Science and 15+ years of professional experience in the field.

#### **IT Skills Summary**
---
**Infrastructure Management:** Terraform, Ansible, Capistrano  
**Containers & Orchestration:** Docker, Packer, Helm, Kubernetes  
**Clouds:** AWS, Scaleway  
**CI/CD:** GitHub Actions, CircleCI, Gitlab CI, Codeship  
**Monitoring:** DataDog, Prometheus, Grafana  
**App & Web servers:** Passenger, Puma, Unicorn, Nginx, Apache  
**Databases:** MySQL, PostgreSQL, Redis, ElasticSearch, Kafka, Microsoft SQL Server, Sphinx  
**Programming Languages:** Ruby, JavaScript, Go, C#, Python  
**Backend:** Ruby on Rails. ActionCable, ActiveStorage, ActiveJob. GraphQL API, Rest API. Sidekiq, Devise, OAuth,
RubySAML, Pundit, CanCanCan, Doorkeeper, Geocoder, Ransack, Paperclip, Carrierwave  
**Frontend:** React.js. Redux, Router, Server Side Rendering. Bootstrap, Zurb Foundation, Semantic UI  
**Testing:** TDD/BDD with RSpec/Capybara. Rspec-performance, Minitest  

#### **Work experience**  
---

**Site Reliability Engineer (remote). Smile Inc**,  
Kitchener, Canada  
01/2020 - present

##### Responsibilities:
* Develop new Terraform modules for the Smile.io AWS infrastructure
* Migrate existing Heroku applications to the new infrastructure
* Improve the reliability of the system
* Participate in a weekly on-call rotation

##### Accomplishments:
* Migrated a business intelligence microservice from Heroku to Kubernetes (EKS):
  * dockerized the application
  * wrote a Helm chart with database and data migration hooks
  * wrote several Terraform modules to generate and publish the helm chart, to manage the database permissions (PostgreSQL)
  * automated the deployment of the application to staging and production environments using CircleCI and Terraform
* Migrated DNS hosted zone from DNSimple to AWS Route53
* Created a GH Action CI/CD to test and publish internal gems to GitHub Packages

**Full Stack Developer. Pyx4 Inc**,  
Montreal, Canada  
04/2018 - 01/2020

* Built a team of qualified developers
* Significantly improved the development process by creating a CI/CD pipeline with
building a docker image of the application, automated tests and deployment, also
introducing code reviews and adding documentation guidelines
* Developed a GraphQL API for the Dashboard project, dockerized and installed the
application on the isolated offline environment for the client
* Developed a connection module allowing to import and authenticate users from LDAP-compatible repositories, such as Active Directory
* Developed a generic form engine allowing clients to customize different forms in the application for their needs
* Addressed several security vulnerabilities that allowed the company to pass a security audit and sign an important contract
* Managed infrastructure for different environments: production cloud, production on-premise, staging, QA, test
* Participated in on-call schedule

**Ruby on Rails Developer, Mentel Inc.**  
Montreal, Canada  
07/2017 - 04/2018

* Created a universal module to parallelize fetching requests using Net::HTTP + Mutex
* Tested and adjusted financial calculations for SIP tables, Performance reports and FIA accounts
* Optimized and cached database queries, reducing load times of heavy-loaded pages
from 28 s to 200-300 ms
* Updated and maintained RSpec test suite, introduced integration tests (capybara)
* Provided various system administration service to clients including NGINX/Puma
configuration getting A+ on SSLabs test, Heroku application configuration, various AWS
services provisioning: RDS, EC2, ELB, S3, Route53, Cloudfront
* Under tight deadlines, debugged and fixed a lot of complex issues
* Promoted BDD/TDD and code review, mentored colleagues


**Full Stack Developer, Retrigo Inc.**  
Montreal, Canada  
07/2017 - 04/2018

_Independent Contractor (Remote)_

* Developed a website [Retrigo.com](https://retrigo.com) for a client. Some highlights:
  * Integrated Paypal AdaptivePayments API, including automated refunds processing
and multiple currencies support
  * Completely changed the frontend to meet the new custom design requirements
  * Wrote 600+ unit and integration tests for the core part of the application
  8 Provisioned a server for production: Debian 9, NGINX/Unicorn, Capistrano
* Provided code review and mentoring to client's developers


**Ruby on Rails Developer, Trendigo Inc.**  
Montreal, Canada  
12/2016 - 07/2017

* Configured and managed production server: Debian, Nginx, Passenger, Redis
* Added OAuth authentication with Facebook and Google+
* Optimized load time of several pages: from 4 s down to 100-200 ms
* Integrated application with a credit card processing API
* Integrated application with a back office API
* Developed location-based promotion gallery using Google Maps JavaScript API
* Developed a cross-platform mobile application in Xamarin.Forms


**System Administrator, Sportmaster Ltd.**  
Moscow, Russia  
2006 - 2016

* Installed, configured, upgraded and troubleshot server, networking, PBX, POS and
workstation hardware and software in 10+ retails shops as the only system
administrator in the regional branch of the company
* Worked with the equipment of the following vendors: HP, Cisco, Huawei, Panasonic, Cipher, Epson
* Provided technical support to users (150+ workstations)
* Facilitated the launching of 10+ retails shops and warehouses, providing technical support on all stages from hardware installation to software customization and educating the staff members.
* Participated in weekly on-call rotation for almost 10 years

#### **Education**

##### Certificate Proficiency in Professional Bilingual Communication
McGill University  
2019 - present

##### Ruby on Rails optimization
Online School for Developers Thinknetica.com  
2020 - present

##### Professional Ruby on Rails Web Development
Online School for Developers Thinknetica.com  
2015 - 2016

##### Cisco CCNP Route
2015

##### Cisco CCNA Exploration
Tomsk State University of Control Systems and Radioelectronics
2012

##### Bachelor's degree in Computer Science 
Kemerovo State Technical University,  
2001 - 2006

#### **Hobbies and interests**
* Computer programming
* Psychology
* Getting things done
* Learning foreign languages

If you're interested in bringing my skills to your project, please feel free to contact me. Email: [alex@kudashkin.pro](mailto:alex@kudashkin.pro), skype: [a.kudashkin](skype:a.kudashkin?call), tel: (438)403-8624.
