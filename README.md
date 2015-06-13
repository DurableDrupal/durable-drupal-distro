## Drupal Lean starter set

Upon installation after cloning, a Drupal 7 instance with a fresh adaptive theme sub-theme "drupallean" will be enabled together with a choice set of site building contributed modules.

Typical drush site installation command after creating Apache virtual host and MySql database user rights (here root with no password, not recommended):

````
$ drush si drupallean -y --site-name=myleansite --account-name=admin --account-pass=admin --account-mail=myleansite@example.com --db-url=mysql://root@localhost/myleansite
You are about to CREATE the 'myleansite' database. Do you want to continue? (y/n): y
Installation complete.  User name: admin  User password: admin                                    [ok]
````
