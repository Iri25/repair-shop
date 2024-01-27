# repair-shop

Java/Java Spring Boot application with a 4-layered architecture: data access layer ([model package](https://github.com/Iri25/repair-shop/tree/main/RepairShop/src/main/java/model)), persistence layer ([repository package](https://github.com/Iri25/repair-shop/tree/main/RepairShop/src/main/java/repository)), business layer ([services package](https://github.com/Iri25/repair-shop/tree/main/RepairShop/src/main/java/services)), presentation layer ([controller package](https://github.com/Iri25/repair-shop/tree/main/RepairShop/src/main/java/ctrl)). The data can be saved in memory, in txt files or in the SQLite database using Java Database Connectivity (JDBC) for accessing the relational databases from Java program. The type of repository must be changed depending on the choice of data storage. The Java library, Apache Log4j was used for messages history. The interaction with the user is done through a graphical interface (GUI), developed in JavaFX (the fxml file or the xml file for Spring Bean). The database connection configurations, the bd.config file but also the log4j2.xml file, the xml and fxml files are found in [resources package](https://github.com/Iri25/repair-shop/tree/main/RepairShop/src/main/resources).

Key concepts are encapsulation, inheritance, polymorphism, exceptions, reading from files and storing in files, reading from a database and storing from a database.

Application for a computer repair shop with a graphical interface. The application allows:
1. Add computer repair request
2. Update computer repair request
3. Delete computer repair request
4. View requests
5. Add computer repair form
6. Update computer repair form
7. Delete computer repair form
8. View forms
