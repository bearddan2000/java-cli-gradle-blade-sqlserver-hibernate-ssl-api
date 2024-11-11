# java-cli-gradle-blade-postgres-hibernate-simple

## Description
Creates a small database table
called `dog` and populates with
hql.

## Tech stack
- java
- gradle
  - hibernate
  - hql
  - blade
  - postgres driver

## Docker stack
- gradle:7.6.4-jdk11-alpine
- postgres:alpine

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [HQL code based on](https://www.journaldev.com/2954/hibernate-query-language-hql-example-tutorial)
- [Hibernate config based on](https://www.theserverside.com/blog/Coffee-Talk-Java-News-Stories-and-Opinions/An-example-hibernatecfgxml-for-MySQL-8-and-Hibernate-5)
- [Hibernate code based on](https://github.com/lokeshgupta1981/hibernate/tree/master/hibernate-hello-world)
