# CS-Select-Docker
this is the docker-compose file for CS-Select

to start the CS-Select server
1. Go into this dir
2. Execute ``git submodule init``
3. Execute ``git submodule update``
4. execute ``sudo docker-compose up``
5. go into the CS-Select repository and execute ``mvn tomcat7:redeploy``

if you want to use your own ml server, just edit `tomcat/conf.properties` to fit your needs.

you can see the database on localhost:3306 with tools like MySQL Workbench. Unless changed the root password is ``root``
only the root user can be used to access the database from the host, or any other machine for that matter.

this repository uses git submodules, so you might need to run git submodules to download the ml-server
