Fichier application.properties : Il contient des configurations globales, communes à tous les environnements. C'est là que vous définissez des propriétés générales comme le nom de l'application, le port du serveur, etc.

Fichier application-dev.properties et application-prod.properties : Ces fichiers contiennent des configurations spécifiques aux environnements respectifs (développement et production). Par exemple, vous pouvez spécifier une base de données différente en développement et en production, ou ajuster le niveau des logs.

Fichier application-commandes.properties : C'est un fichier spécifique pour le microservice "commandes", où vous pouvez définir des paramètres qui sont propres à ce service. Vous pouvez y mettre des URLs, des clés API ou d'autres configurations qui concernent uniquement ce microservice.


resume : 
application.properties : Configurations globales.
application-commandes.properties : Configurations spécifiques au microservice "commandes".
application-dev.properties : Configurations pour l'environnement de développement.
application-prod.properties : Configurations pour l'environnement de production.
