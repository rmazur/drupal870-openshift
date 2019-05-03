# drupal870-openshift

## Reference:
https://tobru.ch/drupal8-on-openshift/
## OC command:
oc new-app php~https://github.com/tobru/drupal-openshift.git#openshift mysql --group=php+mysql -e MYSQL_USER=drupal -e MYSQL_PASSWORD=drupalPW -e MYSQL_DATABASE=drupal
