
   H E L L O F E N I X

   Application exemple for Software Engeneering project

   1) create database:

      $ mysql -p -u root

      Enter password: rootroot

      mysql> CREATE DATABASE hello;

      mysql> \q

   2) clone and build:

      $ git clone https://github.com/tecnico-softeng/hellofenix.git

      $ cd hellofenix

      $ mvn package

   3) execute: 
   
      $ mvn clean package exec:java
