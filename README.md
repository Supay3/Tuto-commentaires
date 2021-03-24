Symfony Demo Application
========================

The "Symfony Demo Application" is a reference application created to show how
to develop applications following the [Symfony Best Practices][1].

Requirements
------------

  * PHP 7.2.9 or higher;
  * PDO-SQLite PHP extension enabled;
  * and the [usual Symfony application requirements][2].

Installation
------------

[Download Symfony][4] to install the `symfony` binary on your computer and run
this command:

```bash
$ symfony new --demo my_project
```

Alternatively, you can use Composer:

```bash
$ composer create-project symfony/symfony-demo my_project
```

Usage
-----

There's no need to configure anything to run the application. If you have
[installed Symfony][4] binary, run this command:

```bash
$ cd my_project/
$ symfony serve
```

Then access the application in your browser at the given URL (<https://localhost:8000> by default).

If you don't have the Symfony binary installed, run `php -S localhost:8000 -t public/`
to use the built-in PHP web server or [configure a web server][3] like Nginx or
Apache to run the application.

Tests
-----

Execute this command to run tests:

```bash
$ cd my_project/
$ ./bin/phpunit
```

[1]: https://symfony.com/doc/current/best_practices.html
[2]: https://symfony.com/doc/current/reference/requirements.html
[3]: https://symfony.com/doc/current/cookbook/configuration/web_server_configuration.html
[4]: https://symfony.com/download

# Tuto
Fait grâce aux tutos de <a href="https://grafikart.fr/">Grafikart</a>
Ce tuto a été fait dans le but de comprendre le fonctionnement d'ApiPlatform et de React dans une situation concrète en mettant en place un CRUD
sur les commentaires, je laisse le README de Symfony pour comprendre d'où provient le projet de base, la très large majorité de ce projet ne vient pas de moi
mais de tous les contributeurs du projet de base de Symfony que vous pouvez retrouver sur <a href="https://github.com/symfony/demo">ce repos</a>.

Je ne cherche en aucun cas à m'approprier le travail de Grafikart qui est fabuleux mais bien à mettre en lumière le cheminement de projets que j'ai pu faire
en suivant ses cours et qui m'a permis, dans le cadre de ce tuto, de mettre en place ApiPlatform et React sur mon portfolio.
