# Cinema-app
### A service to navigate user through a cinema-shop application. 
### Using the site you will be able to create cinema halls, movies, movie sessions etc. and save it to your shopping cart.

## Usage:
You need to be authorized for using this application, so start with creds of an already registered user
(use login: Admin@i.ua and password: 1234). Now you are able to use site functionality,
here are some endpoints for it:
- POST, "/register")
- GET, "/cinema-halls", "/movies", "/movie-sessions/**") ***User, Admin***
- PUT, "/shopping-carts/movie-sessions") ***User***
- POST, "/orders/complete") ***User***
- GET, "/shopping-carts/by-user", "/orders") ***User***
- POST, "/cinema-halls", "/movies", "/movie-sessions") ***Admin only***
- PUT, "/movie-sessions/**") ***Admin only***
- GET, "/users/by-email") ***Admin only***
- DELETE, "/movie-sessions/**" ***Admin only***

## Structure
A project is created according to REST principles.
The internal structure is separated between 3 layers: Data access layer, Application layer (Service) and Presentation layer (Controllers).

## Technologies used:
***Apache Tomcat (v9.0.50)***, ***MySQL***, ***Spring (Core, Security, Web)***, ***HQL***, ***Hibernate***, ***Maven***;

## Requirements:

1. Install MySQL and create database schema;
2. Link database to your IDE (fill the required information in provided /resources/db.properties file);
3. Configure Apache Tomcat (v9.0.50) in your IDE;
4. You may want to use Postman or similar API for your ***POST*** requests;
5. Run the code and enjoy!

### Enjoy!


