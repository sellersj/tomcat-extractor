# tomcat-extractor

Used for setting up tomcat in a generic way for dev work.

## Usage

mvn clean 
mvn process-resources -P tc7
mvn process-resources -P tc8,!tc7