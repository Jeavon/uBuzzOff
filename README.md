# uBuzzOff #

![uBuzzOff](images/uBuzzOff50.png?raw=true)

uBuzzOff is a Umbraco package made up of HTTP Module and a dashboard control. Its purpose is to monitor inbound links to a Umbraco website and provide an backoffice interface for users to be able to blacklist domains. When a domain is blacklisted any links containing a referrer header with that domain will be returned a 403 not authorised error. uBuzzOff was developed to aid in the removal of "unnatural" inbound link profiles where the inbound links cannot be removed at source.