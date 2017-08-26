# README #

This README would normally document whatever steps are necessary to get your application up and running.

### What is this repository for? ###

* Quick summary
- This repository contains sample PageObject Selenium tests for Confluence wiki page. 
* Version
1.0

### How do I get set up? ###

### Prerequisites to run the tests ###
# 1st setup project in IntelliJ IDEA: # 
1. Setup geckodriver needed for Selenium:
 -download bin from: https://github.com/mozilla/geckodriver/releases
 - unzip file
 - add path to geckodriver.exe to system environment path variable, e.g. C:\Users\<user>\Drivers\
2. Download and unzip locally Selenium 3.5.2 for Java: http://www.seleniumhq.org/download/ 
3. Install Java SDK (1.8):
 - can be downloaded from: http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html
3.Download and install IntelliJ IDEA, e.g. from: https://www.jetbrains.com/idea/download/#section=windows
4.Open project in IntelliJ:
 - setup project SDK, e.g. Java jdk 1.8.X.
 - download maven dependencies (Ctrl+Shift+A and type rebuilt-all-maven-project) - TestNG dependencies will be downloaded. 
 - go to File-> Project Structure -> Libraries -> add all libraries from ..\selenium-java-3.5.2\lib and client-combined-3.5.2-nodeps.jar and client-combined-3.5.2-nodeps-sources.zip from <pathtoselenium>\selenium-java-3.5.2\

# Second option by executing jar file. # 
1. CMD to directory containing jar file and execute command (required jdk 1.8 and geckodriver):
- 'java -cp "SpartezQA.jar" org.testng.TestNG testng.xml'

* Configuration
* Dependencies
TestNG
Selenium
* How to run tests

### Assumptions, issues, 


### Contribution guidelines ###

* Writing tests
* Code review
* Other guidelines

### Who do I talk to? ###

* Repo owner or admin
marcinjzalewski@gmail.com
* Other community or team contact
https://www.linkedin.com/in/zalewskimarcin/
