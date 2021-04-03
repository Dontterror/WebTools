#WebTools
This version of WebTools contains a better web experience, that you can use for free.

You can download faster without needing to install an app, such as internet download manager.
HTTPS can be secure, but safe? I don't think so. With WebTools, there is a scanner that scans websites, so basically you get free safety.
Note that some sites may break, we are fixing it for the next version.
======================================================================
#Build the tools
================
#Requirements
=============
* JDK 8 or later, download it here: https://adoptopenjdk.net/
* Maven, download it here: https://maven.apache.org/download.cgi
#Building
* Clone the project
* After installing JDK8+ and Maven, it is possible to create a runnable JAR using the command `mvn package`
This creates a file called web-tools.jar in a directory named target
#Running
* Obtain the file web-tools.jar (see Building)
* Create a text file called .confirmaccess and in the file, paste in the following: --access=allow --nonaccess=deny
* Run the command java -jar web-tools.jar in the directory with those files
#IDE Setup
IDE has not come out.
Do not download any other IDE not claiming to be: 88X IDE x64
