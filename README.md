# openliberty-microprofile-starter
A starter JEE Microprofile starter application maven enabled


After checking out the project, please perform following steps

let your application Name $ApplicationName

Please update Application Name at the following places in pom.xml

1. <artifactId>$ApplicationName</artifactId>
2. <name>$ApplicationName</name>
3. <app.name>$ApplicationName</app.name>
4. <finalName>$ApplicationName</finalName>


Please update Application Name at following places in src/main/liberty/config/server.xml
1. Line 1: Description
2. webApplication -> <webApplication id="$ApplicationName" location="$ApplicationName.war" contextRoot="${app.context.root}" />
