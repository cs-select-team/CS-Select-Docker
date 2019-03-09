# CS-Select-Docker
This is the docker-compose file for [CS-Select](https://www.github.com/bendixsonnenberg/CS-Select).

To start the CS-Select server
1. Install [Maven](https://maven.apache.org/)
1. Install [Docker](https://www.docker.com/). Under Linux you may need to install [Docker Compose](https://www.docker.com/) seperatly.
1. Go into this directory
2. Execute ``git submodule init``
3. Execute ``git submodule update``
4. Execute ``sudo docker-compose up``
5. Go into the CS-Select repository and execute ``mvn tomcat7:redeploy``

If you want to use your own ML-Server, edit `tomcat/config.properties` to fit your needs.

You can see the database on localhost:3306 by using tools like MySQL Workbench. Unless changed, the root password is ``root``.
Only the root user can be used to access the database from the host, or any other machine for that matter.
You can access the application at [localhost:8080](http://localhost:8080).

This repository uses git submodules, so you might need to run git submodules to download the ML-Server.
