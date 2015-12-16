# OAuth Consumer And Server Library For PHP #

A PHP library for OAuth 1.0a consumers and servers.   Complete with an extensible OAuth store, including a full working implementation of MySQL/MySQLi, Postgresql, PDO and Oracle stores.

The library implements methods to:

  * verify incoming requests against the library
  * sign outgoing requests, with curl support for actually doing the request
  * sign requests with a body
  * administrate consumer keys and tokens for multiple users (server and consumer side)
  * log incoming and outgoing requests handled by the library (optionally in the database)

This code is used in many sites, and in active use for the anyMeta CMS.  anyMeta is developed by [Mediamatic Lab](http://www.mediamatic.nl) in Amsterdam, The Netherlands. Currently the code is chiefly maintained by [Corollarium Technologies](http://www.corollarium.com).

## Discussion, bugs and help ##

See the [FAQ](FAQ.md) page.

Please report any bugs to the [issues](http://code.google.com/p/oauth-php/issues/list) page.

Please use the [mailing list](http://groups.google.com/group/oauth-php-discuss) for help, discussion and more.

## OAuth Consumer (client) How To ##

ConsumerHowTo describes the basic way to make an OAuth consumer. Examples for Twitter and Google are provided.

## OAuth Server (service provider) How To ##

ServerHowTo describes the basic way to make an OAuth enabled site (aka service provider).

## Files ##

In OauthPhpFiles you can see an overview of the files in this projects.