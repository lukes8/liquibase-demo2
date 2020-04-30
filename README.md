# Liquibase-demo2

This project could be a used as

  - a tutorial for learning the basics in liquibase (mvn liquibase plugin)
  
This project is a **simple example** of a liquibase-project with maven ( http://www.liquibase.org/ ).<br>
This liquibase-project is ready to run with H2 in memory db

# How to run this project
To run the project<br>
type '**clean package -DskipTests**' in the same directory that the pom.xml-file resides

# Additional stuff
### Useful commands, tips
mvn liquibase:generateChangeLog<br>
mvn liquibase:rollback -Dliquibase.rollbackCount=1
