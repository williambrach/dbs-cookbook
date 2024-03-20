# Zadanie 2

* pokračovanie zadania 1
* import "Stack Exchange Data Dump Superuser" datasetu do vašej lokálnej databázy
* vytvorenie nových http endpointov podľa zadania
* http -> sql -> json
* **IBA SQL, ŽIADNE ORM** 
* Pri odpovediach je potrebné vrátiť časy vo formáte ISO8601 v UTC
* **PROTOKOL** (pdf alebo markdown)
    * SQL dopyty s ich opisom
    * príklady volania HTTP endpointov (pre každý endpoint)

### Bodovanie

![db scheme](./assets/bodovanie.png)


### HTTP endpointy

#### [GET] /v1/posts/:post id/users

#### [GET] /v1/users/:user id/friends

#### [GET] /v1/tags/:tagname/posts-load

#### [GET] /v1/tags/:tagname/posts-load

#### [GET] /v1/posts/?duration=:duration in minutes&limit=:limit