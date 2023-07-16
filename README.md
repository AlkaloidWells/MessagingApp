# MessagingApp
Implimentation of a messaging application using java and sql no sockets used

# THE ANALYSIS, DESIGN AND IMPLEMENTATION OF< @AKA> MESSAGING SYSTEM



GENERAL OVERVIEW OF PROJECT
As the world becomes a global village, the need for platforms of interactions and communications among people has been on the rise and this need in a University System is much more emphasised .It is in this regard, that The project titled” the ANALYSIS, DESIGN AND IMPLEMENTATION OF A MESSAGING SYSTEM” will enable students of this community to interact and communicate in all privacy and security.
This System however is far from being a messaging app but it summaries the objective of a messaging app. Our projects was subdivided into different phases as required in software development. They include;
THE ANALYSIS PHASE
IDEATION
This consisted of understanding the problem statement and the system requirements, the model etc.
PROBLEM STATEMENT
Develop a simple messaging system for UB, which has the following functionalities: students can sign up freely for an account; students can send and receive messages from other friend. For simplicity messages should not have attachments, and a message can be sent to only one person at a time, and only one person can be copied. Read messages are marked as ‘Read’ and unread as ‘Unread’. You may add other interesting features on your database.


                                PROPOSED SOLUTION
In consideration of the above problem statement, we propose a messaging system which we are going to be called , @aka.
@aka is a simple messaging system, that can permit students to send and receive messages reliably, securely and effectively. The students in this system are to be called users who would, be able to register with their personal and confidential information (being able to create an account) and after which they will be able to login ( get admitted by @aka) so as to be able to benefit from it’s functionalities (sending and receiving messages , display of sent and received messages, report of the message status(read and un read) and finally indicate sent and received dates of the messages.
The system will be able to store input data from the account creation and login page directly into its data base and can query out this information where necessary. The system will look below.

THE DESIGN PHASE
In Order to build this System, the following considerations were made.
MODELLING LANGUAGE
There are different modelling languages which could be used but for this project, the modelling language used was the MERISE MODELLING LANGUAGE.
MERISE (Method of Studies and Realizations for Computer Systems for Companies) is an information system design and development methodology. It is a general-purpose, developmental, modelling language in the field of software engineering that is intended to provide a standard way to visualise the design of a system.
The Reasons for the choice of this modelling Language is that;
 It is easy and straight forward.
 It is widely used for better data base design.
MODELLING DIAGRAMS
These are representations of a real – world application. Models provide an abstract view of the system, while different diagrams provide concrete representations of the system.
For the modelling of our messaging system, the following modelling diagrams were used

Entity Relationship Diagram (ER) is a design or blueprint of a database that can be later implemented as a database. The main components of ER Model are;
Entity Sets and Relationship Sets. In the case of @aka, the following entities were identified and the attributes explained. It is however CONCEPTUAL.
1. USER
This is any student who wishes to use the messaging system .He or she has the following attributes and can be the Sender or the Receiver.
User _id: This is the number the system gives to any registered student so as to enable easy querying of the credentials.
User_first name: This is the first name of the student that wants to register in the system
User_last name: This is the last name of the student registering into @aka.
Create_date: This is date that the user created his or her account
Is_active: This indicates if the individual already has an account into the system
2. MESSAGE: This is the written text sent or received through the system. It has as attribute;
Message _id: This is the number the system assigns to any new message sent or received.
3.GROUP: This is the section which permits multiple users to have a conversation through the group chat. It has the following attributes;
Group_id: This is the number the the system assigns to any new group created.
Group_creator:This is the Id of the person who created the group and can add other members.
Group_name:This is name of the group to be created by any user.

The screenshot below shows the ER diagram .
![image](https://github.com/AlkaloidWells/MessagingApp/assets/55930366/c9700e07-5837-4bb7-a230-dd748933b0a3)

DATA BASE SCHEMA
This is a set of formulas called integrity constraints imposed on a data base. There are three types; Logical schema, physical schema and view schema.
The messaging system has as DBS as shown below.

![image](https://github.com/AlkaloidWells/MessagingApp/assets/55930366/42913b9e-b24c-44b5-b55d-60e9d8109e7c)

IMPLEMENTATION PHASE
PROGRAMMING LANGUAGE:
The coding of @aka was done using the JAVA programming language .The choice of java is because it is object oriented, class-based and designed to have as few implementation dependencies as possible.
 It is portable due to the presence of the JAVA VIRTUAL MACHINE
 It is flexible
 It has built in frameworks for example JavaFx.
 It has good built in libraries such as the SWING BUILDER

The Login button enables a user to be logged into his or her account.
The Help button provides guidelines on how the user can proceed with the utilisation of the messaging system.
The About US button provides information on the development team of @aka .
![image](https://github.com/AlkaloidWells/MessagingApp/assets/55930366/b201bc76-4c20-4f37-ae0e-8bd3f832ef33)

REGISTRATION PAGE
This is the page that the user is able to input his or her confidential information.
a) Username: This is the field of the user’s name into @aka.
b) Email: This is the field of the email into @aka.
c) Password: This is the field of the password.
d) Confirm Password: @aka is able to confirm the user’s password.

![image](https://github.com/AlkaloidWells/MessagingApp/assets/55930366/873c5de4-8794-431d-8fdc-c8d3bdf709bd)


LOGIN
This is the page that enables a user with an already existing account to login in into the system. The Login can only be possible after the verification of the existence of the account has been done and authentified by @aka .This is querying from the data base all the user correct credentials.
1) The username: the user inputs the name as earlier registered .
2) Password: The user inputs his or her password.
3) Register Button: Permits the user to register incase he or she didn’t register initially before logging in.
4) Login: Finalises the Authentication process and gives access to the user into his message chat options.

![image](https://github.com/AlkaloidWells/MessagingApp/assets/55930366/0e638447-d709-47dc-9095-3b076daeec1f)

CHAT OPTIONS: This could be either a simple chat or a group chat
![image](https://github.com/AlkaloidWells/MessagingApp/assets/55930366/0ed8cf85-c0ec-4250-aaf6-f2c7c5cee4a3)


CHAT: This enable the user to enter the private chat page
![image](https://github.com/AlkaloidWells/MessagingApp/assets/55930366/aa2317a6-23ef-4a7d-ba20-b0d275ef95b4)

GROUP CHAT:
Here, the system permits the admin to create the group and able to add other members who have valid user accounts in @aka.

![image](https://github.com/AlkaloidWells/MessagingApp/assets/55930366/1013fea7-953f-4799-9728-cc7a76e25ab4)

USER PROFILE: This is the page where the user can update the profile in case of new identification credentials from the user
![image](https://github.com/AlkaloidWells/MessagingApp/assets/55930366/563f6a58-4794-4869-8512-d38f1dd901fa)

SYSTEM SPECIFICATIONS
@aka messaging system is able to ;
 Permit, accept and store User Registration Credentials
 Enables the user to send and receive messages
 Enable multiple users in a group to send messages and other material
 Communicate and retrieve data from the data base where necessary.
 The user with a single registered account can have multiple user names enabling certain considerations for the type of messages sent
 The user can only receive messages from another user registered in the system
 The user can only send messages to someone with his or her correct user name
 IMPORTANCES OF @AKA TO THE UB COMMUNITY
As the name indicates, it is a small but a very important system as it permits a certain degree of interconnection among students hence enhancing the community objectives of UB.


 Students are able to communicate among themselves for the sharing of information and ideas which are indispensable for their success.
 It creates a framework of in which interconnection among students from different institutions under UB enabling a good community life among them as engineering students, law students , social sciences students etc. could interact without any forms of discrimination.
 It also enables the users as individuals to stay in touch observing some privacy on what they talk about which could be business,family,studies etc. avoiding important lost of some confidential information to the general public
CHALLENGES ENCOUNTERED
 Easy Identification of the systems requirements and the installation of the required soft wares.
 Writing and Retrieving data from the data base.
 Transfer of foreign keys from the primary table to the foreign table
RECOMMENDATIONS AND SOLUTIONS
i. Understanding of the course , patience and determination.
ii. Individual and collective research
iii. Team work and ideas sharing
Analysis Design and implementation of a messaging system Page 20
iv. Good Programming skills
v. Good writing skills and Research

              CONCLUSION
The Messaging System we have just designed and implemented was as a result of the great supervision of our Supervisor ,courage and confidence demonstrated through the desire of the different team members .Our sincere appreciations to the Microsoft community for this amazing software(ms word) and the Google community for the search engine .
This Messaging System has so many applications as earlier indicated but it is still far from being a messaging app. With more resources and knowledge, we would want to see this as a reality, for @aka will revolutionised conversations in the UB community .
The entire system is far from being perfect and hence criticisms and suggestions will be welcomed
We apologise for all grammatical errors in this report and suggestions and appreciations will be welcomed.


