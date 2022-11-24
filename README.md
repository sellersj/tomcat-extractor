# tomcat-extractor - archived

Used for setting up tomcat in a generic way for dev work.

By default this will use tomcat 7 and put the postgresql and h2 drivers into the lib directory.

## Usage

```
mvn clean 
mvn process-resources -P tc7
mvn process-resources -P tc8,!tc7
mvn process-resources -P tc9
```
