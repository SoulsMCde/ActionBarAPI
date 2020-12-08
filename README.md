# ActionBarAPI
ActionBarAPI Plugin for SoulsMC.eu

How To (Server Admins)
------
ActionBarAPI is a jar file that you can download and run just like a normal jar file.

Download a copy of ActionBarAPI-1.0.3-SNAPSHOT.jar from [releases](https://github.com/SoulsMCde/ActionBarAPI/releases/download/v1.0.3/ActionBarAPI-1.0.3-SNAPSHOT.jar).

Paste the jar directly to your plugins folder. Just like old times

## How To (Plugin Developers)
------
 * Maven Repo:
```xml
<repository>
    <id>arrow-systems</id>
    <url>https://mvn.arrow-systems.de/</url>
</repository>
```
 * Artifact Information (For >1.0.3-SNAPSHOT):
```xml
<dependency>
    <groupId>eu.soulsmc</groupId>
    <artifactId>actionbarapi</artifactId>
    <version>1.0.3-SNAPSHOT</version>
    <type>jar</type>
    <scope>provided</scope>
</dependency>
 ```
 * Artifact Information (For <1.0.3-SNAPSHOT):
```xml
<dependency>
    <groupId>de.soulsmc</groupId>
    <artifactId>actionbarapi</artifactId>
    <version>1.0.2-SNAPSHOT</version>
    <type>jar</type>
    <scope>provided</scope>
</dependency>
 ```
How To (Compiling Jar From Source)
------
To compile ActionBarAPI, you need JDK 8, maven, and an internet connection.

Clone this repo, run `mvn clean install`
