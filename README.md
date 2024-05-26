Simple chat application to understand web sockets in Spring Boot.
Client was built with native JavaScript.

Version 0.2.0

- Change to private user chat rooms
- Uses Docker containers for MongoDB to storing chat history, user info, chatroom info

To Start

- start up mongodb and mongo express service conatainers:
 > docker-compose up
- if needed, recreate docker containers:
 > docker-compose down
- run ChatApplication.java
