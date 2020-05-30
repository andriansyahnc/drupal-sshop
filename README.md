#Drupal Boilerplate.

How to install for new user:
- clone the project using `git clone git@github.com:andriansyahnc/drupal-boilerplate.git`
- go to the directory`cd drupal-boilerplate`
- install dependency using `composer install`
- copy the default settings using `cp web/sites/default/default.settings.php web/sites/settings.php`
- install the project using `vendor/bin/drush si --existing-config`
- start the server using `vendor/bin/drush runserver`
