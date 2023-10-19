---
name: Mobile Monopoly Project
tools: [Java, Maven, JUnit, SQL]
image: # TODO Add image
description: Creating the board game Monopoly using Maven, java, and Android Studio for COM S 309 - Software Development Practices.
external_url: # TODO Add link
---

# About
For Iowa States' COM S 309 course, we were expected to create an mobile app using java, maven, and SQL. My group decided to create the board game Monopoly where the properties were based on building on Iowa State University's campus. We also added a chat feature to allow for the players to communicate with each other within the game itself and individually.

## Role
I was part of the backend team, and was in charge of managing the database and creating the APIs for the user and chat for the front-end to use.
### Users
For the user and the associated data, I was in charge of creating the user class and user controller, the user controller connected to our database and allowed for the user to be created, updated, and deleted. The user class was used as the interface between the Front-end and Backend and allowed the front-end to access the user data.

### Chat
I was in charge of creating a Chat feature. This was setup similar to the user with the chat controller and the chat class. What differed was that chat was done using websockets, to allow for real time chat.

---

# Skills/ Knowledge Gained
- Maven
- SQL management
- Unit testing with JUnit

# Supporting Documents
- Docs created by professor