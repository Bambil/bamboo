# BamboO

![bamboo](https://img.shields.io/badge/bambil-bamboo-orange.svg?style=flat-square)

## Introduction

This is an IoT platform created with three goals in mind:

* Performance
* Scalability
* Modularity

## Do we lie?

We don't lie! For all of the above goals we have done something.

* For *performance*:
We have used MQTT for fast and reliable delivery of messages, and we have
also used the Nodejs for the sake of it's asynchrounos innate, that improves
the performance of the application.

* For *Scalability*:
We are using containers and balance loaders so that our platform never discourage you :)

* For *Modularity*:
Nodejs is inherently extremely modular, and to make our application more
modular, we intend to use **docker** containers for different services of our
application.

From the benefits of this architecture we can point out following reasons:

1. This makes balance loading easier. (By creating multiple instance of a certain
docker image.)
2. Easier development.
3. Greater maintainability

## Getting started with Bamboo

First of all you need to set up bamboo platform, you have two choice for that:

1. Using [docker-compose](https://docs.docker.com/compose/):

```sh
git clone https://github.com/bambil/bamboo
cd bamboo
docker-compose up
```

After running bamboo platform you must run your favorite gateway (hub) in order to communicate with platform.
For more technical information about Bamboo platform please refer to [bamboo-doc](https://bambil.github.io/bamboo-doc/).
