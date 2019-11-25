# [Quarkus.io/guides](https://quarkus.io/guides)
## [Quarkus.io/rest-client](https://quarkus.io/guides/rest-client)
## [Quarkus.io/hibernate-orm](https://quarkus.io/guides/hibernate-orm#hibernate-configuration-properties)
## [Rieckpil Rest-Client communication](https://rieckpil.de/howto-microprofile-rest-client-for-restful-communication/)
## [eclipse.org Rest-Client for Microprofile](https://download.eclipse.org/microprofile/microprofile-rest-client-1.3/microprofile-rest-client-1.3.html#clientexamples)
## [jboss.org Microprofile Rest-Client](https://docs.jboss.org/resteasy/docs/3.6.2.Final/userguide/html/MicroProfile_Rest_Client.html)
## [What is Quarkus-pdf](https://edufs.edu.htl-leonding.ac.at/moodle/pluginfile.php/127329/mod_resource/content/0/12525138-dzone-refcard320-quarkus.pdf)
## [Microprofile Metrics](https://quarkus.io/guides/microprofile-metrics)
## [Microprofile Health](https://quarkus.io/guides/microprofile-health)

[.](https://github.com/Maxwahl/jeopardized)
[.](https://github.com/1920-5bhif-nvs/02-microservices-individual-tasks-leonkuchinka)

#### ````docker run --name some-postgres -p 5432:5432 -e POSTGRES_PASSWORD=passme -d postgres````

```` quarkus.datasource.url=jdbc:postgresql://localhost/postgres
quarkus.datasource.driver=org.postgresql.Driver
quarkus.datasource.username=postgres
quarkus.datasource.password=passme
quarkus.datasource.min-size=3
quarkus.datasource.max-size=13
quarkus.hibernate-orm.database.generation=drop-and-create ````
