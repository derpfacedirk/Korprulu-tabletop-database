# Korprulu-tabletop-database
The korprulu tabletop database is meant as a central database and api for data involving the Starcraft Tabletop Miniatures game by Archon Studios

This project will consist of two parts, a database and an API to give developers access to the database. This project will not include any frontend or user facing parts. It is intened as a way to give developers a central, high-quality data source to develop their own applications or frontends on.

**Current plan**
Currently the plan for this project is to run the API as a flask application. The domain name is to be determined later.

The database will be run as a JSON-based database. The flexibility this allows will allow for quickly adding data developers need and means little processing will be required when data is sent to the API in a JSON format.

An Oauth system that would allow users to make a list on one app and load it on another is currently not in scope for this project. When baseline functionallity is set up this might change.

**Gathered data**
Currenlty planned data:
1. The game rules, with tags to make finding all rules relevant to certain parts of the game more easy
2. Game results. Including: Result, victory points, mission played, deployment played and lists used
3. Tournaments. Including: games played, location, date. (a ranking list might be added later once player tracking is added to the database)


**API documentation**
The KTD API will run on a flask based webserver. Exact documentation of the calls that are going to be implemented is in progress and high priority.

**Contributing**
Suggestions, contributions and dissenting opinions on current ideas are all welcomed, this should be a central data source by and for the community :D

