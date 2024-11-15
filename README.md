# java-cli-gradle-blade-sqlserver-hibernate-ssl-api

## Description
Creates a small database table
called `dog` and populates with
hql. Provides end-to-end self signed ssl certs.

## Tech stack
- java
- gradle
  - hibernate
  - hql
  - blade
  - mssql driver

## Docker stack
- alpine:edge
- gradle:7.6.4-jdk11-alpine
- mcr.microsoft.com/mssql/server:2017-latest-ubuntu
- traefik:v2.4

## To run
`sudo ./install.sh -u`
Available at https://myapi.docker.localhost/basic-route-example

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [HQL code based on](https://www.journaldev.com/2954/hibernate-query-language-hql-example-tutorial)
- [Hibernate config based on](https://www.theserverside.com/blog/Coffee-Talk-Java-News-Stories-and-Opinions/An-example-hibernatecfgxml-for-MySQL-8-and-Hibernate-5)
- [Hibernate code based on](https://github.com/lokeshgupta1981/hibernate/tree/master/hibernate-hello-world)
