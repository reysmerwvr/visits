# Visits

NodeJs application to count visits. Example to demonstrate docker compose concepts

## Requirements

  - Node.js >= 10.16.0
  - npm >= 6.10.1

## Version

1.0.0

## Installation

Download zip file and extract it [latest pre-built release](https://github.com/reysmerwvr/visits). Or clone the repository and cd into it.

This project uses a number of open source projects to work properly:

* [Express] - Fast, unopinionated, minimalist web framework for Node.js
* [Redis] - Redis is an open source (BSD licensed), in-memory data structure store, used as a database, cache and message broker

## Setup

Run docker containers with docker-compose.

```bash
cd visits
docker-compose up -d
```

### Todos
  - Write tests
  - Add code comments
  - Add server validations

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does 
its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [Express]: <https://expressjs.com/>
   [Redis]: <https://redis.io>