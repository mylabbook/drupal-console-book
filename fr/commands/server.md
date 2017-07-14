# server
Lance le serveur web PHP interne

**application.gitbook.messages.usage:**
```
drupal server [arguments]
```

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
address | Les valeurs adresse:port

## application.gitbook.messages.examples
* Lancer en utilisant en argument la valeur d'adresse par défaut 127.0.0.1:8088
```
serveur drupal
```
* Passer en argument une adresse pour utiliser un numéro de port différent
```
serveur drupal 127.0.0.1:8089
```
* Lancement avec en argument les valeurs d'adresse par défaut, en utilisant l'option --root pour définir la racine Drupal
```
drupal --root=/var/www/drupal8.dev server
```