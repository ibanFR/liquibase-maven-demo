# Liquibase Maven plugin demo
Playground project to experiment with Liquibase Maven Plugin capabilities.

We will use [H2 Database Engine](https://www.h2database.com/html/main.html) as relational database management system.

In order to get started with Liquibase see:
[Get Started with Liquibase](https://docs.liquibase.com/start/home.html)

To start h2 database in server mode see [Using the Server](https://www.h2database.com/html/tutorial.html#using_server)
```shell
java -cp ~/.m2/repository/com/h2database/h2/2.2.224/h2*.jar org.h2.tools.Server
```

Verify changes to be applied:
`mvn resources:resources liquibase:status`

