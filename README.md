OAuth2 Demo PHP (Fork of bshaffer/oauth2-demo-php)
===============

This application is designed to demo the workflow between OAuth2.0 Clients and Servers.

Installation
------------

Use [Composer](http://getcomposer.org/) to install this application:

    $ git clone git@github.com:SaaSVenture/app-oauth2-client.git
    $ cd app-oauth2-client
    $ curl -s http://getcomposer.org/installer | php
    $ ./composer.phar install

**WebHost Configuration**

Silex requires you to [configure your web server](http://silex.sensiolabs.org/doc/web_servers.html) to run it.

**Permissions**

Run the command `$ chmod -R 777 data/` in the project root so that the web server can create the sqlite file.