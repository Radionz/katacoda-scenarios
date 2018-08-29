# Lancer l'application packagée

Lancer le .jar précedement crée `java -jar ./target/swagger-spring-1.0.0.jar`{{execute}}

Afficher la documentation graphique [Swagger UI](https://[[HOST_SUBDOMAIN]]-8080-[[KATACODA_HOST]].environments.katacoda.com/api)

Tester un appel sur /api/pets `curl -X GET https://[[HOST_SUBDOMAIN]]-8080-[[KATACODA_HOST]].environments.katacoda.com/api/pets -H 'accept: application/json' -H 'content-type: application/json'`{{execute}}