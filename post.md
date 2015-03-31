## What is Symfony?

Symfony is a set of PHP Components, a Web Application framework, a Philosophy, and a Community — all working together in harmony.
Symfony is a PHP web application framework for MVC applications.
Symfony is free software and released under the MIT license.

The first version of symfony was released in October 2005 by project founder Fabien Potencier, coauthor of this book. Fabien is the CEO of Sensio (http://www.sensio.com/), a French web agency well known for its innovative views on web development.

## Why Use Symfony?

Reputation

Quickly accepted by professionals, Symfony is now a stable environment that is both well-known and recognized internationally. The number of its references testifies to this, as they have increased significantly since its launch. ​​Symfony also has an active community – developers, integrators, users and other stakeholders involved in the enrichment of this tool.

Immutability

Symfony is a product of the work of the SensioLabs company. Founded more than 12 years ago, the company is a web agency that has a lot of references. Symfony Framework is today still a key tool used by its own teams to develop projects for clients. Consistency is the also something, which is associated with long-term support. Today, this support is provided by SensioLabs.

References

Intranet, basic public sites, social networks, community sites, management of workflow and applications, etc., examples are not missing: a lot of websites and applications of all sizes and types rely on Symfony.

This is notably the case with Yahoo!, Dailymotion, Exercise.com, Opensky.com and also applications such as PHPBB or Drupal.

Innovation

Symfony is all that can be expected from a framework: high speed, flexibility, components that can be reused, etc. Then we have a structure that was developed using best practices.

But that’s not all. Since SensioLabs has developed a habit of shaking the established order, and always strive for perfection, Symfony (and its entire community) has developed a sense of curiosity that goes far beyond the PHP. It does not hesitate to innovate from the search of ideas elsewhere and then to adapt them to the world of PHP.

Resources

When using Symfony, you can be sure that you are never “alone with your screen display.” Whether with a request to the public support (mailing lists, IRC, etc.) or support from the company (consulting, training, etc.), you will always find the answers to your questions.

Based on the principle that “an undocumented line is a line that does not exist”, you will also find many works dedicated to Symfony, which will help you in developing your sites and applications.

Interoperability

Symfony respects the existing standards of PHP: PHPUnit, naming conventions for classes, etc. Moreover, it also allows you to use some pieces of its software for the building blocks without necessarily using the framework as a whole.

It is so interoperable that in its core it uses external software for building blocks (ORM, Swiftmailer etc.)

## Symfony Directory Structures:

By default Symfony consists of following directories,

    app/: The application configuration
    src/: The project’s PHP code
    vendor/: The third-party dependencies
    web/: The web root directory

app/

‘app’ directory in Symfony 2 holds the application configuration. You can find all configuration related stuff in ‘app/config’ folder. If you need to configure your database or Swiftmailer then you will need to change parameters/settings from here. Apart from that this directory holds the ‘cache’. While writing code in Symfony 2 you will be working with lots of files ranging from xml, yml to php, twig, html etc. Controllers will be written in some file, routes will be defined in some another files, views will be written in some other file and so on. So while serving request Symfony has to read all these necessary files. Since the count of files is too high, to achieve great performance Symfony 2 has inbuilt caching. And this cached data will be stored in ‘cache’ directory. Again there is a ‘log’ directory which has debugging related data, especially useful in development.

Apart from all these directories, the ‘app’ directory also holds, ‘AppKernel.php’. This is nothing but heart of Symfony 2 in other words this file is the entry point for any Symfony 2 project.

bin/

By default this folder has some security check functions. We can use this directory same as ‘vendor’ directory.

 
src/

Again the most important directory in the Symfony 2. This directory will be holding source code of your app. You have to create controllers, views, routes in this directory only. All of your PHP and template related files will be residing in this directory. Symfony 2 follows ‘bundle system’. There is good explanation of this bundling system in Symfony 2 docs, you can read it here.

vendor/

‘vendor’ directory holds all third-party dependencies. To install and manage dependencies you will need ‘Composer’. Most commonly you will be using ‘doctrine’ for database related things and ‘twig’ for template/views related things.

web/

‘web’ directory is web root of your Symfony 2 project and will be used to store static data like images, css of your app. This directory has two important files ‘app.php’ and ‘app_dev.php’. ‘app.php’ will be used in production environment while ‘app_dev.php’ will be used in development environment. In Symfony 2 you have to pass all requests to these files to boot up Symfony and get your work done. This files will internally load whole Symfony for you, will look up for routes, will execute associated controllers, will generate view and will display your results. Apart from that the ‘web’ directory has some general purpose files like robots.txt, favicon and apple icon.

In root directory, you will find a file named ‘composer.json’. This file used to hold the composer configuration. You have to edit this file to add, modify or remove third-party dependencies.

Apart from that there are some read me files in root directory. If you want, you can read them else just forget about them.

## Symfony Features

 Symfony was built in order to fulfill the following requirements:

*    Easy to install and configure on most platforms (and guaranteed to work on standard *nix and Windows platforms)
*    Database engine-independent
*    Simple to use, in most cases, but still flexible enough to adapt to complex cases
*    Based on the premise of convention over configuration–the developer needs to configure only the unconventional
*    Compliant with most web best practices and design patterns
*    Enterprise-ready–adaptable to existing information technology (IT) policies and architectures, and stable enough for long-term projects
*    Very readable code, with phpDocumentor comments, for easy maintenance
*    Easy to extend, allowing for integration with other vendor libraries


