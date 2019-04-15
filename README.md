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

## Why we wrote it?

At 2017 when we decided to re-write [mia](https://github.com/I1820/mia) to handle more load and making it a commercial project
Iman suggested that we can use NodeJS for this and Bamboo was born. At the same time I was writing
my thesis for B.Sc., so I decided to change its subject to having NodeJS-based IoT Platform.

At the end this project presented as my thesis and then deprecated in favor of [I1820](https://github.com/I1820/I1820).
