---
name: Mobile Monopoly Project
tools: [Java, Maven, JUnit, SQL]
image: # TODO Add image
description: Creating the board game Monopoly using Maven, java, and Android Studio for COM S 309 - Software Development Practices.
external_url: # TODO Add link
---

# About
For Iowa States' COM S 309 course, we were expected to create an App using maven, and SQL for the backend and Android Studio for the frontend.
My group decided to create the board game Monopoly. I was one of the second members in charge of the backend, and the database.
# Backend
## Users
I was in charge of creating the user class and user controller, the user controller connected to the the database and allowed for the user to be created, updated, and deleted. The user class was used as the interface between the Front-end and Backend.

## Chat
I was also in charge of creating a Chat feature. This was setup similar to the user with the chat controller and the chat class. What differed was that chat was using websockets to allow for real time chat. This was my first time using websockets, and I found it very interesting. I also had to create a chat service to allow for the chat to be sent to the database.

## Database
I personally had pervious experience with SQL, so I was in charge of the initial database setup and connecting the database to our backend.