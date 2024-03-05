# Software_project

1. INTRODUCTION
 1.1.
 1.2.
 1.3.
 Definitions and abbreviations
 Abbreviation
 DBMS
 JSON
 SSL
 Definition
 Database Management System
 JavaScript Object Notation
 Secure Socket Layer
 HTTPS
 AWS
 Document Purpose
 HyperText Transfer Protocol Secure
 Amazon Web Services
 This document describes the software requirements of the study project “Social
 Media Platform” which is similar to X.com (formerly known as Twitter).
 This document is intended for the development group of the project, professors
 checking the project, and the customers interested in this project.
 Scope
 Social Media Platform will allow users to connect with other users, share
 information, and post media (images, video, and text) for others to see, like, and
 comment.
 This document provides a description of the software which allows you:
 ● Creating and deleting posts
 ● Makinggroups
 ● Private messaging
 ● Addingfriends
 ● Liking and commenting other posts
 
1.4.
 Related documents
 [Example] Requirements specification
 1.5.
 Document structure
 This document consists of 4 main parts:- Section 1- Introduction, definitions, and purpose of the project.- Section 2- Process description, interaction, and the system model.- Section 3- Description of the specific requirements that this software follows.- Section 4- Description of the technologies used for implementing the software.

In this social media platform users can sign up which they give their information to the system
 and the system checks if there is any similar user with that information, in case it can not find a
 similar one it lets users to sign up in the platform.
 After the sign up each time a user wants to see his/her account and content should sign in and
 send information to the platform and if there is any same information the platform lets the user in
 and show relevant content to the specific user.
 When the user is inside the platform, scroll and see some contents which he/she is allowed to see
 and also can make some posts. He or she sends the post to the platform and the platform saves
 the information in the database and shows that post to people who are allowed to see it.
 
3. SPECIFICREQUIREMENTS
 3.1. Userrequirements:
 3.1.1. Accesstouseraccount
 Identifier PART-1
 Description
 Onlyuserwiththelogininformationcanaccessandrighttochangedatafor
 useraccount
 3.1.2. Userlogininformation
 Identifier PART-2
 Description
 Eachusercanuseplatformloginpagetoshowhe/shehastheownershipofthe
 accountwithfollowinginformation:
 1. Email
 2. Password
 3.1.3. Usersignupinformation
 Identifier PART-3
 Description
 Userscanhaveonly1accountintheplatformforsharingtheirideasorvisiting
 otherpeople'sposts.Theinformationeachusermustprovideduringsignup
 are:
 1. Nameandsurname
 2. Username
 3. Email
 4. Password
 3.2. Postingrequirements:
 3.2.1. Limitationonpost’scontent
 Identifier PART-4
 Description
 Contentoftextmustnotexceed250characters,imagesizemustnotexceed4
 MB,andvideosizemustnotexceed10MB.Thepostmustconsistofatleast4
 
characters,animage,oravideo.
 3.2.2. Postcontentsrequirements
 Identifier PART-5
 Description
 Postcontentsmustfollowthetermsandconditionsandguidelines.Anycontent
 thatgoesagainstguidelineswillberemoved,andtheposterwillbenotified
 withawarningofpotentialban.
 3.2.3. Messagesafety
 Identifier PART-6
 Description
 Themessagesbetweenusersmustbeencryptedbeforeexchangingtosecure
 privacy.Themessagesshouldbestoredinthedatabaseinanencryptedformat.
 3.3. Platformrequirements:
 3.3.1. Securitymeasurements
 Identifier PART-7
 Description
 InformationmustbesecurelyexchangedusingtheHTTPSandSSLprotocols.
 3.3.2. Availability
 Identifier PART-8
 Description
 Thewebapplicationmustbehighlyavailabletonotdisturbusers’experiences
 
4. GENERALLIMITATIONS
 The following technologies will be used in developing the software:
 1. Python language for backend
 2. Streamlit for interface
 3. SQLite for database
 4. AWSashost server
 The user need one of following web browsers to use the platform:
 1. Mozilla Firefox
 2. Google Chrome
 3. Brave
 4. Microsoft Edge
 5. Safari