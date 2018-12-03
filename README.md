# openliberty-microprofile-starter

A starter JEE Microprofile starter application maven enabled


# Instructions

After checking out the project, please perform following steps

let your application Name **$ApplicationName**

## Changes to pom.xml

	<artifactId>$ApplicationName</artifactId>
	<name>$ApplicationName</name>
	<app.name>$ApplicationName</app.name>
	<finalName>$ApplicationName</finalName>
		

## Changes to server.xml

**server.xml is locatted at src/main/liberty/config/server.xml**

- Line 1: updated description attribute with something appropriate
- Line 7: `<webApplication id="$ApplicationName" location="$ApplicationName.war" contextRoot="${app.context.root}" />`


## Changes to index.html
Edit src/webapp/index.html with content appropriate to your application
