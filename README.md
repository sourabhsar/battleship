## Battleship

Classic Battleship Game hosted by Heroku

https://battlesh1p.herokuapp.com/main.html

<img src="github/demo0.jpg" alt="Battleship" style="text-align:center; width: 100%"/>

## Technology Detail

Java Spring Boot application using the Java Persistence API (JPA) and object-relational mapping implemented with Hibernate ORM. Multi-user access with Authentication and Authorization provided by Spring Security. Persistent data storage using PostgreSQL and hosted by Heroku with database services also provided by Heroku through Amazon Web Services (AWS).

<img src="github/demo1.PNG" alt="Welcome" style="text-align:left; width: 40%"/>

## Access

When server is started. Data Loader Service deletes all non-persistent sample entities and reloads them for
user access.

The following is Access information for 5 Sample Users <br>
User Email Address: Password

j.bauer@ctu.gov: j <br>
c.obrian@ctu.gov: c <br>
kim@alwaysHostage.org: k <br>
president@allstate.com: d <br>
m.dessler@ctu.gov: m

Data Loader Service creates sample games to generate records table and ongoing games tables

<img src="github/demo2.PNG" alt="Welcome" style="text-align:center; width: 80%"/>

## Gameplay

Sample Games can be watched or played or new users and games may be created and joined. Instructions are provided during gameplay.

<img src="github/demo3.PNG" alt="Welcome" style="text-align:center; width: 80%"/>

## Future Development

- Front-end UI Styling adding mobile responsivity
- Migrate remaining Rest Controller functions to call Service functions following MVC architecture
- Aggregate request and response JSON objects to decrease number of requests
- Add Finished Games table (perhaps only for users to see their own past games)

## Necessary Bug fixes

- Reset data function will not load on bootrun
