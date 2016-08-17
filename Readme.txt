***************************************************************
***                                                         ***
***                           ANT                           ***
***                                                         ***
***************************************************************

Run 'ant war' (all commands should be executed in the directory 
"ant_maven_gradle").
Tests are included.
_________________________________________________________

1) To deploy project to Tomcat uncomment and edit two last 
properties: 
a - edit 'deploy.dir' value (path to directory webapps of Tomcat).
b - edit 'home.dir' value (absolute path to the project
(includes ant_maven_gradle directory)).

2) Uncomment tag target with name "deploy".

3) Run 'ant deploy' (don't forget put on your headphones)

***************************************************************
***                                                         ***
***                          GRADLE                         ***
***                                                         ***
***************************************************************

Run 'gradle clean build' (without quotes).
Tests are included.

***************************************************************
***                                                         ***
***                          MAVEN                          ***
***                                                         ***
***************************************************************

Run 'mvn clean install' (without quotes).
Tests are included.


      2016 Solovyov Systems. All rights reserved. For all issues contact Sergiy_Solovyov@epam.com