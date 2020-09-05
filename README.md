# THE-HUNT

## Statement Of Purpose

We would like to create a gaming application for NWMSU which works on iPhone SE, Android device, laptop and an iPad. The main motto behind this idea of creating a gaming application is to bring bearcats of diverse departments onto a common platform which helps students to interact, encourages students to unique and special parts of campus, contributes in developing an attitude towards teamwork.

## Overview

We would like to create an app that can be played on a mobile device. The app would encourage players to complete a 'quest' by encountering a specific list of locations. A player would activate one of the locations in the quest. To score that location, the user must enter the geographic area (as determined by their mobile device). Locations may be explicitly identified (easier) - or described using clues (harder). The quest may require locations to be accessed in a specific order - or in any order as specified by the quest creator.

## Hosted Page

[Hosted Page](https://dixith1196.github.io/THE-HUNT/)

## Benefits

* Improves the ability to think in logical way.
* Encourages teamwork Attitude.
* Thinking out of the box.
* Interacting with new people.
* Improves Leadership Skills.
* Builds problem Solving Ability.
* Improves Imagination.
* Exploring new locations.


## Entity Relationship Diagram
![title](https://github.com/Dixith1196/THE-HUNT/blob/master/ER%20Diagram%20(6).png?raw=true)

#### User Entity
* The User entity has 4 attributes namely:Username,Email,Password,Date last accessed.It stores the username,email,password and last accessed of the user.
* A single User may be into one team or multiple teams.User may create and manage a team or join a team and particpate in the quest.
#### Team entity
* Team entity has 7 attributes namely:Team name,creator,Date created,Date last edited,Time spent in competition,Username of the team members.
* The user serves as captain of any team they create and he provides the team name.
#### Player Entity
* This entity has 4 attributes:Player nickname,Player score,time spent,Username of the player.A single user can play with different nicknames and score accordingly.

#### TeamPlayer Entity
* TeamPlayer entity is an associative entity that maps between Team and Player.
* It contains attributes DateInvited,Date accpeted Invite,date rejectedInvite and Dateleft team.
* The captain provides a list of emails of invited members.A user can accept the team invite and become a team player or reject it.
* After three days, if not accepted,it is assumed as rejection.

#### Quest Entity
* This entity has 4 attributes.Quest name,Designer of the quest,Date created and date last accessed.The user serves as designer of any quest they create and they 
provide a quest name.

#### QuestLocation mapping
* This entity consists of 2 attributes.Quest name and Location.

#### Location Entity
* This entity consists of Locations,Location clue and Location coordinates.The designer provides a list of locations for the quest.

#### Competition Entity
* This entity consists of CompetitionID,Competion name,creator,date created,start time and endtime of the competition.The user serves as the hunt master of the competion.
* The hunt master specifies the start date time and end time for the competion.

#### CompetitionTeam 
* This entity is also an associative entity that map teams and competitions.It consists of 3 attributes:Competion ID,Team Number,Team score that stores the scores of different team members.

## User Stories
* User can register in Sign-up module.
  ### Acceptance criteria:
  The RFP is yet to be reviewed by the client.Once it is approved we will work on this task.
  
* User can login in login module.
  ### Acceptance criteria:
  The RFP is yet to be reviewed by the client.Once it is approved we will work on this task.
  
* User can create a quest in create quest module.
  ### Acceptance criteria:
  The RFP is yet to be reviewed by the client.Once it is approved we will work on this task.
  
* User can send invitation to other members.
  ### Acceptance criteria:
  The RFP is yet to be reviewed by the client.Once it is approved we will work on this task.
  
* The User should be able to accept or reject the invitation.
  ### Acceptance criteria:
  The RFP is yet to be reviewed by the client.Once it is approved we will work on this task.
  
* User can manage his team in user profile module.
  ### Acceptance criteria:
  The RFP is yet to be reviewed by the client.Once it is approved we will work on this task.
  
* The User should be able to provide list of locations for the quest and and provide location number.
  ### Acceptance criteria:
  The RFP is yet to be reviewed by the client.Once it is approved we will work on this task.
  
* User can create competition.
  ### Acceptance criteria:
  The RFP is yet to be reviewed by the client.Once it is approved we will work on this task.
  
* User should be able to provide start date, time and end data, time for the competition.
  ### Acceptance criteria:
  The RFP is yet to be reviewed by the client.Once it is approved we will work on this task.
  
* In Leader-Board module, Statistics of the team will be displayed.
  ### Acceptance criteria:
  The RFP is yet to be reviewed by the client.Once it is approved we will work on this task.
  
* In map module, navigation of the team will be displayed using their GPS tracking system.
  ### Acceptance criteria:
  The RFP is yet to be reviewed by the client.Once it is approved we will work on this task.
  
## Sign-in Screen:
* User will need to enter their sign-in credentials to login to the application.
* If a user enters incorrect credentials, they should receive an error saying In-correct credentials.
* If a user enters correct credentials, they should be redirected to HOME page.

## Home Screen:
* Home Screen consists of list of quests created by students using the application, a user can join in any of the quests.
* Any quest cannot contain no more than 4 people.
* Once user joins a quest and Clicks START, they will be redirected to NAVIGATION page.

## Leaderboard Screen:
* Once a user completes their quest, they will be rewarded with points considering their TIME. Every group who completes the quest will be rewarded with points and positions       will be assigned as per the time taken to complete the quest.
* Team name with their position will be seen in Leaderboard.

## Create-Event Screen:
* This screen is used to create quests and used to invite teams to the quest
* In this module, we use random location picker to assign treasure so that the user who created Event also can play the game
* Teams need to accept the invitation to join the game

## Create-Team Screen:
* This screen is used to create team to join the game
* In this screen, user can invite friends to join the team who are already signed up for the game
* Users can also invite friends to the team while creating his own quest

## Treasure Map Screen:
* This screen is used to navigate users in the game location
* we are looking to use third party library such as google maps or map box to help user navigate in the map
* we will use user coordinates and location coordinates to match the treasure and complete quests

## Profile Tab
* In Profile page, User should be able to see their Name, Statistics, points earned, Team Name.



## Roles
| Roles            | Names                |     
| ---------------- | -------------------- | 
| Project Manager  | Ravichander Reddy    |
| DB Administrator | Harika Kulkarni      | 
| Team Lead        | Bhaskar Reddy        | 
| UI Developer     | Deekshith Maram      | 
| Backend Developer| Pruthvi Naskanti     | 
| Tester           | Sai Rohith           |

## JIRA Link to Project
[JIRA Link](https://the-hunt.atlassian.net/secure/RapidBoard.jspa?rapidView=2&projectKey=HUN)

### JIRA Sprint-1
![](https://github.com/Dixith1196/THE-HUNT/blob/master/Sprint1.PNG?raw=true)

### JIRA Sprint-2
![](https://github.com/Dixith1196/THE-HUNT/blob/master/Sprint%202.PNG?raw=true)

### JIRA Sprint Progress
![](https://github.com/Dixith1196/THE-HUNT/blob/master/Sprint1H1.PNG?raw=true)


## Application UI
![Sign up](https://github.com/Dixith1196/THE-HUNT/blob/master/Signup.PNG?raw=true)
![Login page](https://github.com/Dixith1196/THE-HUNT/blob/master/loginPage.PNG?raw=true)
![Home page](https://github.com/Dixith1196/THE-HUNT/blob/master/homePage.PNG)
![Leaderboard](https://github.com/Dixith1196/THE-HUNT/blob/master/Leader.PNG?raw=true)
![treasure_map](https://github.com/Dixith1196/THE-HUNT/blob/master/map.PNG)
![Create Event](https://github.com/Dixith1196/THE-HUNT/blob/master/createEvent.PNG)
![create_quest](https://github.com/Dixith1196/THE-HUNT/blob/master/createQuest.PNG?raw=true)
![profile](https://github.com/Dixith1196/THE-HUNT/blob/master/prof.PNG)


## Sample Data of Each Entity in Excel 
[Excel Link](Sample_Data.xlsx)

## Risks and Assumptions
### Risks
#### Risk of Application based security break
* Mobile security threats include everything from mobile forms of malware and spyware to the potential for unauthorized access to a device’s data, particularly in the case of   accidental loss or theft of the device.

#### Risk of location access
* The process of poor coding and insecure handling of location data may cause the insecurity in accessing the location.

#### Risk in the Operating System and data retrieval
* Defects in the kernel code and vendor supplied system code may cause the Iphone or android jail breaks.
* Risks in creating or managing the teams.

### Assumptions
* Although responsive design is similar to mobile app design, there is a significant difference in developing apps for any device versus stand alone.
* Symbols are attractive and can be visually attractive to convey information. The results will help to analyze clearly which symbol can be considered most effective in           communicating the action that we wish the users to accomplish. 
* The project scope will not change once the stakeholders sign off on the scope statement
* Bug fix effort for each screen will not exceed 20% of the development effort for same screen.

## Acceptance Criteria:

1. The App should work on all devices like iPhone SE, Android device, laptop, computer, iPad.
2. The User should signup in order to access the app
3. The User has to provide all the required details inorder to register.
4. The User should be able to create teams.(Captain)
5. The Caption should be able to send invites.
6. The User should be able to accept or reject the invitation.
7. The user should be able to create Quests.(Designer)
8. The designer should be able to provide list of locations for the quest and and provide location number.
9. The User should be able to launch a competition (hunt master).
10. The Hunt master should be able to provide start date, time and end data, time for the competition.
11. The Hunt master may choose the existing quest for the competition.
12. The app should provide visible and audible feedback for the player when the active location is encountered.
13. The app should provide visible and audible feedback for the player when the active quest is completed.
14. The Use should be able to accept or reject the call when the application is running.
15. The User should be able to install/uninstall the app at any point of time.
16. The App should work on all devices in various orientations 
17. The App should be secured by loading various SSH keys and by using cryptographic techniques.

## Technologies to be used:
* HTML: It is used to design webpages.
* CSS: It is used to describe how these HTML elements are displayed on the screen.
* JS: It is used to describe the behavoiur of the webpage
* Node JS: Node.Js is a server, which makes our app available to HTTP requests.
* Github: Github is a remote repository where we can store our code.
* Heroku : To host our application.

## Schedule Management:
![schedule management](https://github.com/Dixith1196/THE-HUNT/blob/master/Schedulemanagement.png)

## Cost Estimation
![hourly Billing Rates](https://github.com/Dixith1196/THE-HUNT/blob/master/hourlybillingrate.png)
![CostEstimation](https://github.com/Dixith1196/THE-HUNT/blob/master/cost%20estimation.PNG)

## DEVELOPERS
* Our project requires six designers in bulding the dynamic web App.

## Reference
* [Google](https://www.google.com/)
* [Dribble](https://dribbble.com/) - for UI design reference





