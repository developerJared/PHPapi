# PHP API

This will be a simple API built in **PHP** that will be used for various things. The main one being Authentication for some applications for the portfolio.

## Considerations

This API uses autoloader to auto load classes found in the src folder.
I will be using this for authentication so I will bring in JWT and create my own
Authenticator class.
I am also utilizing DotEnv which allows the use of an **.env** file and **composer** which is PHP's version of a package manager (like **NPM**).
A bit later I will be browsing packagist to see what I can bring in.
I may later implement a view in HTML / PHP to display metrics for the API like logging, endpoints hit, users authenticated and that sort of thing.

## TODO::
- Change **Person** Model to **User** model as it is truer to what the model represents.
- Introduce JWT for authentication.
- Create Authenticator class
- Clean up person and Namespaces
- When creating authenticator, plan multiple API Keys for one user with registration endpoints.
- Add error handler
- Bring in winston? or some other logger.
- Heaps more!!!!