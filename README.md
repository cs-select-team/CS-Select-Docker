# CS-Select-Docker
this is the docker-compose file for CS-Select

to start the CS-Select server
1. Go into this dir
2. execute ``sudo docker-compose up``
3. go into the CS-Select repository and execute ``mvn tomcat7:redeploy``


you can see the database on localhost:3306 with tools like MySQL Workbench. Unless changed the root password is ``root``
only the root user can be used to access the database from the host, or any other machine for that matter.

this repository uses git submodules, so you might need to run git submodules to download the ml-server
