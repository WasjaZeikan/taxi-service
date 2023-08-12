# <img height="48" src="E:\Download\taxi_cab_transportation_automobile_car_vehicle_icon_128574.svg" width="48"/>Taxi service<img height="48" src="E:\Download\taxi_cab_transportation_automobile_car_vehicle_icon_128574.svg" width="48"/>
## Project description:
`A simple web-application that implement work of a taxi service and supports authentication and other CRUD operations.`
 
### Features:
+ registration like a driver;
+ authentication like a driver;
+ create/delete/update a driver;
+ create/delete/update a manufacturer;
+ create/delete/update a car;
+ display a list of all drivers;
+ display a list of all manufacturers;
+ display a list of all cars;
+ display a list of cars that the current driver has;

### Reference to deployed project:[project](http://taxiservice-env.eba-mmdd2mai.us-east-1.elasticbeanstalk.com/)
### Project structure:
+ `src/main/` - main project directory;
    + `src/main/java` - Java class files;
      + `src/main/taxi` - main Java package;
        + `src/main/java/taxi/controller` - Java package that contains Java servlets;
        + `src/main/java/taxi/dao` - Java package that contains DAO classes;
        + `src/main/java/taxi/exception` - Java package that contains custom exceptions classes;
        + `src/main/java/taxi/lib` - Java package that contains Injector class and his annotations;
        + `src/main/java/taxi/model` - Java package that contains model classes: Car, Driver, and Manufacturer;
        + `src/main/java/taxi/service` - Java package that contains different service classes;
        + `src/main/java/taxi/util` - Java package that contains ConnectionUtil class;
    + `src/main/resources` - directory that contains SQL file for DB initialization;
    + `src/main/webapp` - directory that contains webapp files;
      + `src/main/webapp/WEB-INF` - directory that contains main webapp files;
        + `src/main/webapp/WEB-INF/web.xml` - webapp configuration file;
        + `src/main/webapp/WEB-INF/views` - directory that contains JSP pages;
+ `pom.xml` - Maven configuration file;
+ `README.md` - readme file;
+ `checkstyle.xml` - configuration file for checkstyle maven plugin;
### Usage technologies:
+ [Java](https://en.wikipedia.org/wiki/Java_(software_platform))
+ [Jakarta(Java) Servlet](https://en.wikipedia.org/wiki/Jakarta_Servlet)
+ [Jakarta(Java) Server Pages](https://en.wikipedia.org/wiki/Jakarta_Server_Pages)
+ [Java Database Connectivity (JDBC)](https://en.wikipedia.org/wiki/Java_Database_Connectivity)
### Installation(For example, on IntelliJ IDEA Community Edition):
1. Install [JDK](https://www.oracle.com/java/technologies/downloads/). To check installed JDK we should run command `java --version` in terminal;
2. Install [Tomcat](https://tomcat.apache.org/download-90.cgi);
3. Open the terminal and navigate to the directory where our project will be located;
4. Clone the repository, running command:`git clone https://github.com/WasjaZeikan/taxi-service.git`; 
5. Open IntelliJ IDEA;
6. Click on `Open`, then choose the directory where the project is located; 
7. Open the `File` menu;
8. Choose `Settings...`;
9. Select `Plugins`;
10. Enter `Smart Tomcat` in the search field;
11. Install the `Smart Tomcat` plugin.
12. Select menu `Run`; 
13. Select `Edit Configurations...`;
14. Add new configuration, select `Smart Tomcat`;
15. Enter any name in field `Name:`;
16. In field `Tomcat Server` click on `Configure...`;
17. Click on `Add...` button, select folder where `Tomcat` is located;
18. Click on `Apply`, then `Ok`;
19. Select menu `Run`, then `Run 'Name of our configuration'`;
20. In the end, click on link, where `Smart Tomcat` is running;