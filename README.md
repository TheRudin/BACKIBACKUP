# API_EXAMPLE

Schritt 1:

Neues NodeJS (Express) Projekt anlegen:

npm init -y

Das package.json wurde erstellt

npm i --save express

Dsa Express Framework wurde installiert

file app.js erstellen -> wird das Hauptdokument für die gesamte Appliketion

npm i -g nodemon

die nodmeon applikaion ist nun global installiert, nodemon sorgt für eine Entwicklungsumgebung, welche von alleine wieder Startet im Fehlerfall

npm i --save swagger-jsdoc swagger-ui-express

Die 2 Pakete sorgen für die API Dokumentation, es müssen lediglich die Swagger Notationen bei den einzelnen Aufrufen verwendet werden.

npm i --save arangojs@5

Der ArangoDB Client auf Version 5 wird geladen


docker run -p 8529:8529 -e ARANGO_ROOT_PASSWORD=openSesame arangodb/arangodb:3.6.4

Der ArangoDB Server wird mit Docker gestartet.

DIVERSE ANLEITUNGEN UND HILFEN:

https://petstore.swagger.io/#/

Beispiel API von SWAGGER

https://www.arangodb.com/tutorials/tutorial-node-js/

Anleitung für ArangoDB für NodeJS

https://www.arangodb.com/tutorials/arangodb-crud/


Doku async await

https://www.heise.de/developer/artikel/async-und-await-fuer-Node-js-3633105.html

CRUD für ArangoDB


docker startup:

The above compose configuration could be used to start a master node and 4 workers using the following command:

docker-compose up --scale worker=4

xxx
