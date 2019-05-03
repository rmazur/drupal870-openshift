# drupal870-openshift

## Reference:
https://tobru.ch/drupal8-on-openshift/
## OC command:
1) oc new-app php~https://github.com/rmazur/drupal870-openshift.git mysql --group=php+mysql -e MYSQL_USER=drupal -e MYSQL_PASSWORD=drupalPW -e MYSQL_DATABASE=drupal
2) oc expose svc/drupal870-openshift --port=8080
3} oc get routes
