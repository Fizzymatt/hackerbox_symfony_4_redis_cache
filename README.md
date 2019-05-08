# A simple example of in-memory and Redis caching in Symfony 4 #

## Purpose ##

I made this project as part of a tutorial that describes how to implement caching in Symfony 4, both in-memory and with a Redis database.

**NOTE: this project has only been tested on OSX.**

## Instructions ##

### Prerequisites ###

A local installation of the [Composer](https://getcomposer.org/) dependency manager.

### Install dependencies ###

Navigate to the project root and run the following command:

```bash
composer install
```

### Run the project using in-memory caching ###

Ensure that the **cache** section in the **config/packages/framework.yaml** file is commented out.

```bash
php bin/console server:run
```

### Run the project using Redis caching ###

Uncomment the **cache** section in the **config/packages/framework.yaml** file.

Navigate to the project root and run the following command:

```bash
php bin/console server:run
```
