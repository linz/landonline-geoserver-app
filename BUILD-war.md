To build the WAR file, run this:


```
cd src
mvn install -DskipTests -T 2C
mvn package -DskipTests -T 2C
```

war will then be found in `.\src\web\app\target` as geoserver.war


