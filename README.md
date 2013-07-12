#Development workflow

All new code, etc. should be developed locally, tested on www-test.civicrm.org, and the deployed on production.

New configurations (i.e. configuration changes made via the UI etc. can/should be made on www-test.civicrm.org first before being deployed on production.

#Local development environments

You can develop locally as long as you are not storing any unencrypted personal data in your local development environment.

Drupal and CiviCRM databases can be encrypted on www-test.civicrm.org before being transferred to local development environments.

#Upgrades

Upgrades (especially CiviCRM upgrades) should be tested locally and on the test infrastructure before being carried out on the production server.

Put the site into maintanence mode before upgrading

#CiviCRM customisations

Any CiviCRM customisations should be places in the php and templates directory rather than being directly overwritted in order to make it easy to keep track of customisations through upgrades.
