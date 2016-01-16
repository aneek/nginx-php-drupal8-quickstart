# Drupal 8 Quick Start package on Nginx & PHP-FPM

### CONTENTS OF THIS FILE
---------------------
* Introduction
* Features
* Requirements
* Installation
* Future Improvements
* Maintainer(s)
* Change Log

##### Introduction
------------------
This is a *Drupal 8* quick start package for Redhat OpenShift PaaS. Depending on the system requirements [mentioned here](https://www.drupal.org/requirements), this package needs PHP 5.5+ setup.

##### Features
--------------
* This quickstart installs the latest stable version of Drupal 8.
* This also installs some 3rd party PHP extensions that helps to run Drupal 8 like `opcache`, `twig c extension`, `pecl uploadprogress`.
* Uses Drush to perform a fresh install on the first build. Later on the existing `settings.php` & `services.yml` is used. For more insight refer to the Wiki pages.
* On each build links the `modules`, `profiles` & `themes` directories to the document root. For more insight refer to the Wiki pages.
* This quickstart uses a `deploy.config.yml` file to store the site configurations. This is used while the deploy process. For more insight refer to the Wiki pages.

##### Requirements
------------------
Currently RedhatOpenShift doesn't provide that so this quick start is dependent
on two other packages
* [Openshift Nginx Cartridge](https://github.com/boekkooi/openshift-cartridge-nginx)
* [Openshift PHP Plugin Cartridge](https://github.com/boekkooi/openshift-cartridge-php)

##### Installation
------------------
Please refer to the Wiki Pages for the detailed installation steps.


##### Future Improvements
-------------------------
* Drush alias support.
* Issue fixes.

##### Maintainer(s)
-------------------
* [Aneek Mukhopadhyay](https://www.drupal.org/u/aneek)

##### Change Log
----------------
1. Initial version branch 1.0 created.
