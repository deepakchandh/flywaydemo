# Purpose of repository

The purpose of this repository is to test Flyway database migration tool.

# How to run

To start local PostgreSQL container run `docker-compose up -d`.

There are two ways to run Flyway migration:

## Migration at startup

Run `Main` class.

SpringBoot is configured to run database migration automatically at startup.

## Use Gradle Flyway plugin
```
./gradlew flywayMigrate
```