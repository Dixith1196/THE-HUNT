# THE-HUNT

## Statement Of Pupose

We would like to create a gaming application for NWMSU which works on iPhone SE, Android device, laptop and an iPad. The main motto behind this idea of creating a gaming application is to bring bearcats of diverse departments onto a common platform which helps students to interact, encourages students to unique and special parts of campus, contributes in developing an attitude towards teamwork.

## Overview

We would like to create an app that can be played on a mobile device. The app would encourage players to complete a 'quest' by encountering a specific list of locations. A player would activate one of the locations in the quest. To score that location, the user must enter the geographic area (as determined by their mobile device). Locations may be explicitly identified (easier) - or described using clues (harder). The quest may require locations to be accessed in a specific order - or in any order as specified by the quest creator.

## Hosted Page

[Hosted Page](https://dixith1196.github.io/THE-HUNT/)

## Benefits

* Improves the ability to think in logical way.
* Encourages teamwork Attitude.
* Thinking out of the box.
* Interacting new people.
* Improves Leadership Skills.
* Builds problem Solving Ability.
* Improves Imagination.
* Exploring new locations.


## Entity Relationship Diagram
![title](https://github.com/Dixith1196/THE-HUNT/blob/master/ER%20Diagram%20(4).png?raw=true)

### User Entity
* The User entity has 4 attributes namely:Username,Email,Password,Date last accessed.It stores the username,email,password and last accessed of the user.
* A single User may be into one team or multiple teams.User may create and manage a team or join a team and particpate in the quest.

### Team entity
* Team entity has 7 attributes namely:Team number,Team name,creator,Date created,Date last edited,Time spent in competition,Username of the team members.
* The user serves as captain of any team they create and he provides the team name.

### Player Entity
* This entity has 4 attributes:Player nickname,Player score,time spent,Username of the player.A single user can play with different nicknames and score accordingly.

### TeamPlayer Entity
* TeamPlayer entity is an associative entity that maps between Team and Player.
* It contains attributes DateInvited,Date accpeted Invite,date rejectedInvite and Dateleft team.
* The captain provides a list of emails of invited members.A user can accept the team invite and become a team player or reject it.
* After three days, if not accepted,it is assumed as rejection.

### Quest Entity
* This entity has 4 attributes.Quest name,Designer of the quest,Date created and date last accessed.The user serves as designer of any quest they create and they 
provide a quest name.

### QuestLocation mapping
* This entity consists of 2 attributes.Quest name and Locations.

### Location Entity
* This entity consists of Locations,Location clue and Location coordinates.The designer provides a list of locations for the quest.

### Competition Entity
* This entity consists of CompetitionID,Competion name,creator,date created,start time and endtime of the competition.The user serves as the hunt master of the competion.
* The hunt master specifies the start date time and end time for the competion.

### CompetitionTeam 
* This entity is also an associative entity that map teams and competitions.It consists of 3 attributes:Competion ID,Team Number,Team score that stores the scores of different team members.

## User Stories

* User can create a quest in create quest module.
* User can manage his team in user profile module.
* In Leader-Board module, Statistics of the team will be displayed.
* In map module, navigation of the team will be displayed using their GPS tracking system.
* User can register in Sign-up module.
* User can login in login module.

### JIRA Link to Project
[JIRA Link](https://the-hunt.atlassian.net/secure/RapidBoard.jspa?rapidView=2&projectKey=HUN)

### JIRA Sprint 1

![](https://github.com/Dixith1196/THE-HUNT/blob/master/Sprint1.PNG?raw=true)

### JIRA Sprint 2
![](https://github.com/Dixith1196/THE-HUNT/blob/master/Sprint2.PNG?raw=true)

### Application UI
![Sign up](https://github.com/Dixith1196/THE-HUNT/blob/master/Signup.PNG?raw=true)
![Login page](https://github.com/Dixith1196/THE-HUNT/blob/master/loginPage.PNG?raw=true)
![Leaderboard](https://github.com/Dixith1196/THE-HUNT/blob/master/Leader.PNG?raw=true)
![treasure_map](https://github.com/Dixith1196/THE-HUNT/blob/master/map.PNG)
![create_quest](https://github.com/Dixith1196/THE-HUNT/blob/master/createQuest.PNG?raw=true)
![profile](https://github.com/Dixith1196/THE-HUNT/blob/master/prof.PNG)


# Sample Data of Each Entity in Excel 
[Excel Link](Sample_Data.xlsx)

# Risks and Assumptions

# Risks
## Risk of Application based security break
* Mobile security threats include everything from mobile forms of malware and spyware to the potential for unauthorized access to a device’s data, particularly in the case of   accidental loss or theft of the device.

## Risk of location access
* The process of poor coding and insecure handling of location data may cause the insecurity in accessing the location.

## Risk in the Operating System and data retrieval
* Defects in the kernel code and vendor supplied system code may cause the Iphone or android jail breaks.

## Risk of poor authorization and authentication
* Weak authentication and authorization allows an dispute to access the mobile device, or it is anonymous backend.


# Assumptions
## Users must create an account
* As a developer, locking out users is much simpler until an entry in the user database has been solidified. But that's almost skillful from the consumer view point.

## Application design must be same as the responsive web design
* Although responsive design is similar to mobile app design, there is a significant difference in developing apps for any device versus stand alone.
* For mobile devices, consumers anticipate certain interaction patterns and elements of the graphical user interface.

## Symbols can be easily understand by the users
* Symbols are attractive and can be visually attractive to convey information. The results will help to analyze clearly which symbol can be considered most effective in communicating the action that we wish the users to accomplish. 

## Acceptance Criteria:

1. The App should work on all devices like iPhone SE, Android device, laptop, computer, iPad.
2. The App should work on all devices in various orientations 
3. The App should be user friendly.
4. The App should be secured by loading various SSH keys and by using cryptographic techniques.
5. The User private or any sensitive data should be fully encrypted 
6. The User should signup in order to access the app
7. The User has to provide all the required details inorder to register.
8. The User should be able to create teams.(Captain)
9. The Caption should be able to send invites.
10. The User should be able to accept or reject the invitation.
11. The user should be able to create Quests.(Designer)
12. The designer should be able to provide list of locations for the quest and and provide location number.
13. The User should be able to launch a competition (hunt master).
14. The Hunt master should be able to provide start date, time and end data, time for the competition.
15. The Hunt master may choose the existing quest for the competition.
16. The app should provide visible and audible feedback for the player when the active location is encountered.
17. The app should provide visible and audible feedback for the player when the active quest is completed.
18. The Use should be able to accept or reject the call when the application is running.
19. The app should not consume battery excessively.
20. The User should be able to install/uninstall the app at any point of time.







## Schedule Management:

The process of poor coding and insecure handling of location data may cause the insecurity in accessing the location.
| Names | Roles | Week-1 | Week-2 | week-3 | week-4 | week-5 | week-6 | Nunber Of hours In Class | Number Of Hours OutSide Class | Total Number Of Hours |
|-----------------------|------|-------|--------|---------|----------|--------------|---------|--------|--------|--------|
|1. Harika Kulkarni | Admin | 3.5hrs| 5.5hrs | 4hrs | 4.5hrs | 4.5hrs | 4.5hrs | 4.5hrs | 8.5hrs | 13hrs |
|2. Prudhvi Naskanti | Developer | 4.5hrs | 4.5hrs | 4hrs | 4.5hrs | 4.5hrs | 4.5hrs | 4.5hrs | 8.5hrs | 13hrs |
|3. Dixith Maram | Developer | 4hrs | 3.5hrs | 4.5hrs | 4.5hrs | 4.5hrs| 4.5hrs | 4.5hrs | 7.5hrs | 12hrs |
|4. Bhaskar Reddy Minupuri | Developer | 5hrs | 4.5hrs | 4.5hrs | 4.5hrs | 4.5hrs | 4.5hrs | 4.5hrs | 9.5hrs | 14hrs |
|5. Sai Rohith Gorla  | UI Designer | 4.5hrs | 4.5hrs | 4hrs | 4.5hrs | 4.5hrs | 4.5hrs | 4.5hrs | 8.5hrs | 13hrs |
|6. Ravi Chander Reddy Goli  | Tester | 4.5hrs | 4.5hrs | 4hrs | 4.5hrs | 4.5hrs | 4.5hrs | 4.5hrs | 8.5hrs | 13hrs |
## Cost Estimation:
| Names | Roles | Number of Hours per week | Number of weeks | Cost per unit | Total Cost |
|-----------------------|------|-------|--------|---------|----------|
|1. Harika Kulkarni | Admin | 4 | 6 | $80/hr | $1920 |
|2. Prudhvi Naskanti  | Developer | 3.5 | 6 | $70/hr | $1470 |
|3. Dixith Maram | Developer | 4 | 6 | $70/hr | $1680 |
|4. Bhaskar Reddy Minupuri |Developer| 4 | 6 | $70/hr | $1680 |
|5. Sai Rohith Gorla | UI Designer | 3.5 | 6 | $70/hr | $1470 |
|6. Ravi Chander Goli | Tester | 3.5 | 6 | $70/hr | $1470 |

Overall Cost estimation to develop this application - $9690

![Cost Estimation](https://github.com/Dixith1196/THE-HUNT/blob/master/costestimation.png)

## DEVELOPERS
* Our project requires around six developers in bulding the progressive web App.




