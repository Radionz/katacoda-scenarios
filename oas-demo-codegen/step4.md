# Lancer l'application packagée

1. Lancer le .jar précedement crée `java -jar ./target/swagger-spring-1.0.0.jar`{{execute}}

2. Afficher la documentation graphique [Swagger UI](https://[[HOST_SUBDOMAIN]]-8080-[[KATACODA_HOST]].environments.katacoda.com/api)

3. Ouvrez un nouveau terminal

4. Tester un appel sur /api/pets `curl -X GET https://[[HOST_SUBDOMAIN]]-8080-[[KATACODA_HOST]].environments.katacoda.com/api/pets -H 'accept: application/json' -H 'content-type: application/json'`{{execute}}