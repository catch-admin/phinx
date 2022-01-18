### this package is fork from phinx version 0.9.2.

## Why Do This
The higher version of phinx depends on cakephp. If you need to use a higher version in other frameworks, you will download a lot of unnecessary dependencies, such as cakephp/core, so you need a clean version, so fork the latest version without dependencies. If there are new functions later, they can be added from this version.

## Intro

Phinx makes it ridiculously easy to manage the database migrations for your PHP app. In less than 5 minutes, you can install Phinx and create your first database migration. Phinx is just about migrations without all the bloat of a database ORM system or framework.

**Check out https://book.cakephp.org/3.0/en/phinx.html ([EN](https://book.cakephp.org/3.0/en/phinx.html), [ZH](https://tsy12321.gitbooks.io/phinx-doc/)) for the comprehensive documentation.**

![phinxterm](https://cloud.githubusercontent.com/assets/178939/3887559/e6b5e524-21f2-11e4-8256-0ba6040725fc.gif)

### Features

* Write database migrations using database agnostic PHP code.
* Migrate up and down.
* Migrate on deployment.
* Seed data after database creation.
* Get going in less than 5 minutes.
* Stop worrying about the state of your database.
* Take advantage of SCM features such as branching.
* Integrate with any app.

### Supported Adapters

Phinx natively supports the following database adapters:

* MySQL
* PostgreSQL
* SQLite
* Microsoft SQL Server

## Install & Run

### Composer

The fastest way to install Phinx is to add it to your project using Composer (http://getcomposer.org/).

1. Install Composer:

    ```
    curl -sS https://getcomposer.org/installer | php
    ```

1. Require Phinx as a dependency using Composer:

    ```
    php composer.phar require robmorgan/phinx
    ```

1. Install Phinx:

    ```
    php composer.phar install
    ```

1. Execute Phinx:

    ```
    php vendor/bin/phinx
    ```

### As a Phar

You can also use the Box application to build Phinx as a Phar archive (https://box-project.github.io/box2/).

1. Clone Phinx from GitHub

    ```
    git clone https://github.com/cakephp/phinx.git
    cd phinx
    ```

1. Install Composer

    ```
    curl -s https://getcomposer.org/installer | php
    ```

1. Install the Phinx dependencies

    ```
    php composer.phar install
    ```

1. Install Box:

    ```
    curl -LSs https://box-project.github.io/box2/installer.php | php
    ```

1. Create a Phar archive

    ```
    php box.phar build
    ```

## Documentation

 * [Chinese](https://tsy12321.gitbooks.io/phinx-doc/) (Maintained by [@tsy12321](https://github.com/tsy12321/phinx-doc))

## Contributing

Please read the [CONTRIBUTING](CONTRIBUTING.md) document.

### License

(The MIT license)

Copyright (c) 2022 CatchAdmin