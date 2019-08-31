# sample-readme
A sample readme project for a service that needs support.
This would normally be a private repository.

This is a template for a productive README.md
It has been optimised for support. Keep important info at the top.

*Italics are notes for this template, not real usage.*

## Team Home Page

*General cross project details would live here:*

https://codurance.com/company/

## Logs

*Immediate access to the logs (presumably authenticated)*

|Env|
|-|
|[live](https://a.fake-logging-service)|
|[aslive](https://a.fake-logging-service)|

## Architecture Diagram

*Simple who uses what diagram.*
 
![architecture](./docs/architecture.png)
 
### Key
 
![key](./docs/key.png)

### Services

*Links to the services pages (normally would be equivalent to this)*

|Service|
|-|
|[Contentful](https://contentful.com)|
|[Neo4j](https://neo4j.com/)|

## Deployed Service

*If this is a website the root of the various environments*

|Env|Url|
|-|-|
|live|https://somewhere|
|aslive|https://aslive.somewhere|

## Endpoints

*Useful endpoints to hit*

|Usage|endpoint|Usages|
|-|-|-|
|Something|/something|someone who calls this|
|Another|/api/another|someone who calls this|

## Rabbit MQ

*Some details of message queues used.*

## Database

*Some details of the databases used (tables, columns or collections)*

## How to start the app

`./gradlew run`

`yarn serve`

`docker-compose up`
