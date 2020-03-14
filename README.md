# Hackthon

# MD File Documentation Guide

Please refer this link for MD File document guidelines.
https://help.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax


# Java 
1. Download JDK (File Name: jdk-13.0.2_windows-x64_bin.zip) from https://www.oracle.com/java/technologies/javase-jdk13-downloads.html
2. Unzip the file 
3. Setup **JAVA_HOME**
    Eg: JAVA_HOME=C:\Program Files\Java\jdk-13.0.1
4. Setup ** PATH** or Add to **PATH** with **;**
    Eg: PATH=C:\Program Files\Java\jdk-13.0.1\bin

# Maven
1. Download Maven (File Name: 	apache-maven-3.6.3-bin.zip) from https://maven.apache.org/download.cgi?Preferred=ftp://ftp.osuosl.org/pub/apache/
2. Unzip the apache-maven-3.6.3-bin.zip
3. Setup M2_HOME
    Eg: **M2_HOME**=C:\Users\joyfu\apache-maven-3.6.3-bin\apache-maven-3.6.3
4. Setup PATH.
    **PATH**=C:\Users\joyfu\apache-maven-3.6.3-bin\apache-maven-3.6.3
5.Open new command prompt and check the "mvn -version" command

**Output:**
C:\Users\joyfu>mvn -version
Apache Maven 3.6.3 (cecedd343002696d0abb50b32b541b8a6ba2883f)
Maven home: C:\Users\joyfu\apache-maven-3.6.3-bin\apache-maven-3.6.3\bin\..
Java version: 13.0.1, vendor: Oracle Corporation, runtime: C:\Program Files\Java\jdk-13.0.1
Default locale: en_GB, platform encoding: Cp1252
OS name: "windows 10", version: "10.0", arch: "amd64", family: "windows"

To build maven project **mvn clean compile install**  or for offline build **mvn clean compile install -o**


# Eclipse
1. Download Eclipse  from https://www.eclipse.org/downloads/
2. Install eclipse-inst-win64.exe
3. Choose workspace location
4. Create new maven project

# Apache Kafka

'''Work in progress'''

# Git 
1. Download git.exe 32 or 64 bits from https://git-scm.com/download/win
2. Install git.exe
3. To config git account in your machine.\
    Set your username:
        ```git config --global user.name "FIRST_NAME LAST_NAME"```.\
    Set your email address:
        ```git config --global user.email "MY_NAME@cognizant.com"```.
4. Please validate the global parameter. Use  this command "git config  --global --list".
5. Git clone the repo code.

# Git commands

1. Git Clone - Using to download the code from Remote to local location.
    git clone https://github.com/Gnanasakthivel/Hackathon.git (First we need to enter the username and password details for authentication) 
2. Git Pull - Used to update or sync the code from remote to our local repository. 

    ```git pull```
 
3. Git Add -Used to add file which are need to commit.
 
    To add file(s) to commit. \
    ```git add FILE_NAME``` \
 
    To add files to commit.
    ```git add .```
 4. Git commit - used to commit the changes in our local repository.
 
    ```git commit -m "message"```
   
 5. Git Push - used to push the chnages from local to remote repository.
    
    ```git push```
 
 
 
