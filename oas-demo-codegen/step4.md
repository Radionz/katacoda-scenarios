# Lancer l'application packagée

Lancer le .jar précedement crée `java -jar ./target/swagger-spring-1.0.0.jar`{{execute}}

TEST [Swagger UI](https://[[HOST_SUBDOMAIN]]-8080-[[KATACODA_HOST]].environments.katacoda.com/api)
 
 https://[[HOST_SUBDOMAIN]]-8080-[[KATACODA_HOST]].environments.katacoda.com/api

Afficher la documentation graphique (SwaggerUI) `https://[[HOST_SUBDOMAIN]]-8080-[[KATACODA_HOST]].environments.katacoda.com/api`{{execute}}

Tester un appel sur /api/pets `curl -X GET https://[[HOST_SUBDOMAIN]]-8080-[[KATACODA_HOST]].environments.katacoda.com/api/pets -H 'accept: application/json' -H 'content-type: application/json'`{{execute}}