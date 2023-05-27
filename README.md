# NUS Orbital: We-Love-CS2030
Repository for Orbital Project - rc4nnect


# Motivation
In RC4, there are many (40+) Interest Groups (IG) that residents can choose to attend. Currently, each IG communicates the timings and venues to members through their own Telegram groups, where interested residents can poll for their attendence. With this large number of IGs, it becomes a hassle to check through every group one-by-one to poll for one's attendance, and these polls and other announcements can get lost among other Telegram chats. The sheer volume of notifications also clogs up one's Telegram application, which is counterproductive as many people choose to mute their notifications as a result. 

Additionally, the large number of IGs means there are Interest Groups that may struggle to gain exposure to new members as their only means of communication and exposure currently is through these Telegram groups, and not every residents may choose to join so many groups.


# User stories
We plan to create a web application where RC4 residents can sign up for IGs sessions, manage their weekly IGs schedule, and view information about other IGs they are interested in. With rc4nnect, we hope to eliminate the need to have multiple Telegram groups for every IG, and make the process of following and signing up for IGs less complicated for everyone.


# Use cases
1. As a resident of RC4, I want to be able to manage and view everything IGs-related in one place.
2. As a frequent member of an Interest Group, I want to be able to quickly check the venue and timing for my IG’s sessions that week.
3. As someone looking to try out new Interest Groups, I want to be able to quickly look at the list of IGs and the timings of their sessions to know which IG session I want to and can attend.
4. As someone who goes to sessions of many different IGs, I want to be able to quickly view my personal IG schedule for the week. 
5. (Pipeline) As a member of the IG Exco, I want to publicize my Interest Group to more people and welcome more new members to the IG. I also want to reduce miscommunication during dissemination of information (eg. people not informed of a change in session timing/venue).


# Tech Stack
## Frontend
* React
* Tailwind CSS

## Meta Framework
* Next.js

## Backend
* Django
* Django Rest Framework (to create API consumed by React frontend)

## Database 
* SQLite (temporary, will migrate to PostgreSQL later)
* PostgreSQL 

## Tools
* Typescript
* Firebase? (Authentication)
* Vercel
* PythonAnywhere (to host Django backend API, may migrate to Render later)


# Features
## Authentication
### Description
Currently, we are using Firebase Authentication to do user registration. The user's information and their IG preferences are linked to their account. 

### Considerations
Going forward, we will be moving our user database to our own database hosted on our backend

## Weekly IG Schedule
### Description
On the home page, users can see a weekly view of all the IG slots that they have polled for (or are on the waiting list)

### Considerations


# Pipeline features
## IG Catalouge
## Notification 
## My IG
## Dark mode/Color schemes

# Wireframe
Usage flow (created using Excalidraw)

![image](https://github.com/Jovan131/We-Love-CS2030/assets/122341707/b73af328-9627-451d-bc49-ae3a8b1acdcd)

# Database Design
Blue: By Milestone 1
Everything else: By Milestone 2, possibly also including an "Admin" role

![ER diagram for database v1 drawio](https://github.com/Jovan131/We-Love-CS2030/assets/122272142/315c98a5-afbf-46a7-ac7d-ddfc26d48cda)


