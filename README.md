# Northwest Gaming Appplication

## Project Charter

This is the project charter for the Northwest Gaming Application. This Application will be developed as a Progressive Web application.

## Project Purpose:
This is a mobile gaming application which enables the players(users of this game) to complete a quest which is finding out specific set of location based on the clues provided. This is a fun game aimed at involving the students at Northwest Missouri State University to make their respective teams and participate in the competition to score maximum points based on the level of the difficulty. As we all know due to the ongoing pandemic it is really difficult to get together a group of people but this game will provide the paltform to get along  and meeting new people while still maintaining the social distancing. This also helps the students in improving the mental and physical fitness as the clues will be tricky a person has to walk/jog/run(depends on the interest of the person) to these locations. 

## Team members

<table class="tg">
<thead>
  <tr>
    <th class="tg-0lax">Name of the team member</th>
    <th class="tg-0lax">Roles</th>
    <th class="tg-0lax">Contact Information</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0lax">Vikas Baswapuram</td>
    <td class="tg-0lax">Database Engineer</td>
    <td class="tg-0lax">s538336@nwmissouri.edu</td>
  </tr>
  <tr>
    <td class="tg-0lax">Rohith Reddy Avisakula</td>
    <td class="tg-0lax">Team Leader</td>
    <td class="tg-0lax">s538294@nwmissouri.edu</td>
  </tr>
  <tr>
    <td class="tg-0lax">Rajashekar Gande</td>
    <td class="tg-0lax">Full Stack Developer</td>
    <td class="tg-0lax">s538099@nwmissouri.edu</td>
  </tr>
  <tr>
    <td class="tg-0lax">Sumanth Reddy Naidu</td>
    <td class="tg-0lax">Back end Developer</td>
    <td class="tg-0lax">s538359@nwmissouri.edu</td>
  </tr>
  <tr>
    <td class="tg-0lax">Sumana Reddy Reddybathula</td>
    <td class="tg-0lax">Project Manager</td>
    <td class="tg-0lax">s538360@nwmissouri.edu</td>
  </tr>
  <tr>
    <td class="tg-0lax">pooja gundu</td>
    <td class="tg-0lax">UI Developer</td>
    <td class="tg-0lax">s538295@nwmissouri.edu</td>
  </tr>
</tbody>
</table>



## Mentor/ Client Description:
- Dr. Denise Case
- Assistant Professor,Northwest Missouri State University
- 44-691 Graduate Directed Project 
- Fall 2020

## Coach Consultant

- Dr. Charles Hoot
- Assistant Professor,School of Computer Science and Information Systems


## ER Diagram
<img src="Images\ERD_GDP-1.PNG">

# Game assumptions for the ERD:

## USER REGISTRATION AND TEAM CRITERIA:

- Any person with the valid email id can register for the game. They can also save a nickname of their choice for their userid. 
- The user can create a team or send an invite to join a team. The user can also accept or reject the invites they might get from the teams to join them.
- If the user creates a team then that user serves as the captain for that team and can send invites to other players to join the team he/she created.
- The hunt master will be only one person and he/she will also to register i.e the hunt master is also a user but will be given previlages to access the create quest page. 
- This is done by making sure we identify the hunt master prior to the realease of the game and store that person's id as the huntmaster which will enable them to access the create quest page.

## QUESTS, LOCATIONS AND COMPETITION:

- A quest will have set of location coordinates. The first location coordinates will be displayed to the user if they crack the clue given to them initially. Once that person reaches the location after unlocking the coordinates he will get next clue for the next location.
- This goes on till all the locations have been identified and claimed.
- The series of quests/quest created are grouped together and is added to competition where each competition will have a unique name, start date and end date.
- Once the start date is confirmed and entered a notification is sent to all the users about this.

## SCORING:

- The scoring is given to individuals once they have reached the location. The first individual to reach there will get the maximum points. The next individual to get to the location cannot get the maximum points but will be awarded with a decrement of 10% of the max points and this goes on till the 50% and if there are still players left they will also be warded 50% of the points.
- The team score is total sum of all the individual player scores. The team who finishes finding all the locations fisrt will be awarded bonus points. Only one will get the bonus and no other team can get it.
- The No of persons per team will be limited to a maximum of 4 players and a minimum of 1 player thus giving a chance to form more teams and making the competition and the leaderboard interesting.

## GENERAL RULES:

- The user can join any team only upon approval from the team captain. But if they wish to leave approval is not required.
- Once a team enters a competition with full capacity then no player from that team can leave the team until the competition ends. 
- If the team is not full then they can add a player till the team reaches its maximum capacity. 
- The team with maximum score at the end of the competition will win the competition.
- If there are multiple competitions going on at the same then teams can participate all the competitions that are open if they wish to.


## User Entity
- Any person with a valid email and wishes to register for the game is defined as user.
- An entity is a general type for objects relevant to our game. Entities can represent objects that are crucial to gameplay, such as player and enemy characters, or objects that merely exist in the game world without interacting with the player, such as animated decorations in a level.

## Player Entity
- A Player is a user who is already registered.
- Nick name is also inluded.

## Team Entity
- A team is defined by the group of players and one of the palyer acts as the captain/teamleader.

## Quest Entity
- The quest is decided by the hunt master and is limited by time constraint.

## Location Entity
- This entity is comprised of location coordinates and is given by the huntmaster for the players to locate.

## Competition Entity
- This is conducted by the huntmaster and the team with maximum points wins the competition.

## Sample Data/Demo chart of Application

<img src="Images\Updated_flowchart.png">

## Schedule Management

|                                    PROJECT   PLAN TEMPLATE 	|  	|  	|  	|  	|
|-	|-	|-	|-	|-	|
|   	| PROJECT TITLE 	|   	|   	|  	|
|   	| Northwest Gaming   Application  	|   	|  	|  	|
|   	|   	|   	|   	|  	|
| WBS NO. 	| TASK NAME 	| STATUS 	| DURATION in hours 	|  	|
| 1 	| Sprint   0 	|   	| 180 	|  	|
| 1.1 	| – User stories   prioritization 	| Done 	| 20 	|  	|
| 1.2 	| – ER-Diagram   development 	| Done 	| 25 	|  	|
| 1.3 	| – Sample data 	| Done 	| 20 	|  	|
| 1.4 	| – Schedule   management plan 	| In-progress 	| 25 	|  	|
| 1.5 	| – Cost   estimation 	| Done 	| 20 	|  	|
| 1.6 	| – Proposed UI   screens development 	| In-progress 	| 30 	|  	|
| 1.7 	| – Jira setups 	| Done 	| 20 	|  	|
| 1.8 	| – User   authorization 	| Done 	| 20 	|  	|
| 2 	| Sprint 1 	|   	| 180 	|  	|
| 2.1 	| Planning the   User stories 	| To-Do 	| 50 	|  	|
| 2.1.1 	| As a User I   want to login/Signup for the game. 	| To-Do 	|   	|  	|
| 2.1.2 	| As a user I   want to create a team. 	| To-Do 	|   	|  	|
| 2.1.3 	| As a User I   want to Join a Team. 	| To-Do 	|   	|  	|
| 2.1.4 	| As a   User(captain) I want to accept/decline an invite of a player. 	| To-Do 	|   	|  	|
| 2.1.5 	| As a user I   want to act as the huntmaster and create quest. 	| To-Do 	|   	|  	|
| 2.1.6 	| As a   User(huntmaster) I want to add multiple locations in a single quest. 	| To-Do 	|   	|  	|
| 2.1.7 	| As a User I   want to join a competition. 	| To-Do 	|   	|  	|
| 2.2 	| – Sprint 1   Implementation of all the user stories planned 	| To-Do 	| 100 	|  	|
| 2.3 	| – Sprint 1 Demo   and client Acceptance 	| To-Do 	| 30 	|  	|
| 2.5 	| – MVP 1 release 	| To-Do 	|   	|  	|
| 3 	| Sprint 2  	|   	| 200 	|  	|
| 3.1 	| – Sprint 2   Planning Of  User stories 	| To-Do 	| 50 	|  	|
| 3.1.1 	| As a User I   want to join a competition when it starts. 	| To-Do 	|   	|  	|
| 3.1.2 	| As a User I   want to know about the scoring details of the competition. 	| To-Do 	|   	|  	|
| 3.1.3 	| As a User I   want to look at the points scored by the team. 	| To-Do 	|   	|  	|
| 3.1.4 	| As a user I   want to know how the team points are calculated. 	| To-Do 	|   	|  	|
| 3.1.5 	| As User I want   to know the limit of the players per team. 	| To-Do 	|   	|  	|
| 3.1.6 	| As a user I   want to leave the team and join other team. 	| To-Do 	|   	|  	|
| 3.1.7 	| As a User I   want to change my nick name. 	| To-Do 	|   	|  	|
| 3.1.8 	| As a User  I want to create multiple accounts under   one user id. 	| To-Do 	|   	|  	|
| 3.1.9 	| As a user I   want to know how many more locations are left to be found out. 	| To-Do 	|   	|  	|
| 3.1.10 	| As a user I   want hints if I am unable to crack the clue. 	| To-Do 	|   	|  	|
| 3.4 	| – Sprint 2   Implementation of all the User stories 	| To-Do 	| 120 	|  	|
| 3.3 	| – Sprint 2   Demo  	| To-Do 	| 30 	|  	|
| 3.5 	| – MVP 2 release 	| To-Do 	|   	|  	|
| 4 	| Sprint 3 	| To-Do 	| 180 	|  	|
| 4.1 	| – Sprint 3   Planning of user stories 	| To-Do 	| 50 	|  	|
| 4.1.1 	| As a user I   want to know if there are any points reduced if I use the hints field. 	| To-Do 	|   	|  	|
| 4.1.2 	| As a User I   want assistance in finding a location. 	| To-Do 	|   	|  	|
| 4.1.3 	| As a user I   want to hear instructions while going to that location. 	| To-Do 	|   	|  	|
| 4.1.4 	| As a user I   wish to mute the instructions. 	| To-Do 	|   	|  	|
| 4.1.5 	| As a user I   wish to mute the instructions. 	| To-Do 	|   	|  	|
| 4.1.6 	| As a user I   want to look at all the settings available for the game. 	| To-Do 	|   	|  	|
| 4.1.7 	| As a User I   want to  know if I can create a quest   for the competition. 	| To-Do 	|   	|  	|
| 4.2 	| – Sprint 3   Implementation of all the User stories 	| To-Do 	| 100 	|  	|
| 4.3 	| – Sprint 3 Demo   and Client Acceptance 	| To-Do 	| 30 	|  	|
| 4.5 	| – MVP 3 release 	| To-Do 	|   	|  	|
| 5 	| Sprint 4   (GDP-2) all sprints 	|   	| 540 	|  	|
| 5.1 	| – Sprint 4   Planning of User stories 	| To-Do 	|   	|  	|
| 5.2 	| – Iteration of   all the tasks 	| To-Do 	|   	|  	|
| 5.3 	| – Testing the   application and client approval 	| To-Do 	|   	|  	|
| 5.5 	| – MVP 4 release 	| To-Do 	|   	|  	|


## Updated Cost Estimate 
|  	|  	|  	|  	|   	|  	|
|-	|-	|-	|-	|-	|-	|
|   	| PROJECT COST ESTIMATE 	|   	|   	|   	|  	|
|   	| Northwest Gaming   Application  	|   	|   	|  	|  	|
|   	|   	|   	|   	|  	|  	|
| WBS NO. 	| TASK NAME 	| STATUS 	| DURATION  	| TOTAL TEAM COST 	| TOTAL COST FOR   THE TEAM 	|
| 1 	| Sprint   0 	|   	| 180 	|   	|   	|
| 1.1 	| – User stories   prioritization 	| Done 	| 20 	| $350  	| $7,000  	|
| 1.2 	| – ER-Diagram   development 	| Done 	| 25 	| $350  	| $8,750  	|
| 1.3 	| – Sample data 	| Done 	| 20 	| $350  	| $7,000  	|
| 1.4 	| – Schedule   management plan 	| In-progress 	| 25 	| $350  	| $8,750  	|
| 1.5 	| – Cost   estimation 	| Done 	| 20 	| $350  	| $7,000  	|
| 1.6 	| – Proposed UI   screens development 	| In-progress 	| 30 	| $350  	| $10,500  	|
| 1.7 	| – Jira setups 	| Done 	| 20 	| $350  	| $7,000  	|
| 1.8 	| – User   authorization 	| Done 	| 20 	| $350  	| $7,000  	|
| 2 	| Sprint 1 	|   	| 180 	|   	|   	|
| 2.1 	| Planning the   User stories 	| To-Do 	| 50 	| $350  	| $17,500  	|
| 2.1.1 	| As a User I   want to login/Signup for the game. 	| To-Do 	|   	|   	|   	|
| 2.1.2 	| As a user I   want to create a team. 	| To-Do 	|   	|   	|   	|
| 2.1.3 	| As a User I   want to Join a Team. 	| To-Do 	|   	|   	|   	|
| 2.1.4 	| As a   User(captain) I want to accept/decline an invite of a player. 	| To-Do 	|   	|   	|   	|
| 2.1.5 	| As a user I   want to act as the huntmaster and create quest. 	| To-Do 	|   	|   	|   	|
| 2.1.6 	| As a   User(huntmaster) I want to add multiple locations in a single quest. 	| To-Do 	|   	|   	|   	|
| 2.1.7 	| As a User I   want to join a competition. 	| To-Do 	|   	|   	|   	|
| 2.2 	| – Sprint 1   Implementation of all the user stories planned 	| To-Do 	| 100 	| $350  	| $35,000  	|
| 2.3 	| – Sprint 1 Demo   and client Acceptance 	| To-Do 	| 30 	| $350  	| $10,500  	|
| 2.5 	| – MVP 1 release 	| To-Do 	|   	|   	|   	|
| 3 	| Sprint 2  	|   	| 200 	|   	|   	|
| 3.1 	| – Sprint 2   Planning Of  User stories 	| To-Do 	| 50 	| $350  	| $17,500  	|
| 3.1.1 	| As a User I   want to join a competition when it starts. 	| To-Do 	|   	|   	|   	|
| 3.1.2 	| As a User I   want to know about the scoring details of the competition. 	| To-Do 	|   	|   	|   	|
| 3.1.3 	| As a User I   want to look at the points scored by the team. 	| To-Do 	|   	|   	|   	|
| 3.1.4 	| As a user I   want to know how the team points are calculated. 	| To-Do 	|   	|   	|   	|
| 3.1.5 	| As User I want   to know the limit of the players per team. 	| To-Do 	|   	|   	|   	|
| 3.1.6 	| As a user I   want to leave the team and join other team. 	| To-Do 	|   	|   	|   	|
| 3.1.7 	| As a User I   want to change my nick name. 	| To-Do 	|   	|   	|   	|
| 3.1.8 	| As a User  I want to create multiple accounts under   one user id. 	| To-Do 	|   	|   	|   	|
| 3.1.9 	| As a user I   want to know how many more locations are left to be found out. 	| To-Do 	|   	|   	|   	|
| 3.1.10 	| As a user I   want hints if I am unable to crack the clue. 	| To-Do 	|   	|   	|   	|
| 3.4 	| – Sprint 2   Implementation of all the User stories 	| To-Do 	| 120 	| $350  	| $42,000  	|
| 3.3 	| – Sprint 2   Demo  	| To-Do 	| 30 	| $350  	| $10,500  	|
| 3.5 	| – MVP 2 release 	| To-Do 	|   	|   	|  	|
| 4 	| Sprint 3 	| To-Do 	| 180 	|   	|  	|
| 4.1 	| – Sprint 3   Planning of user stories 	| To-Do 	| 50 	| $350  	| $17,500  	|
| 4.1.1 	| As a user I   want to know if there are any points reduced if I use the hints field. 	| To-Do 	|   	|   	|  	|
| 4.1.2 	| As a User I   want assistance in finding a location. 	| To-Do 	|   	|   	|  	|
| 4.1.3 	| As a user I   want to hear instructions while going to that location. 	| To-Do 	|   	|   	|  	|
| 4.1.4 	| As a user I   wish to mute the instructions. 	| To-Do 	|   	|   	|  	|
| 4.1.5 	| As a user I   wish to mute the instructions. 	| To-Do 	|   	|   	|  	|
| 4.1.6 	| As a user I   want to look at all the settings available for the game. 	| To-Do 	|   	|   	|  	|
| 4.1.7 	| As a User I   want to  know if I can create a quest   for the competition. 	| To-Do 	|   	|   	|  	|
| 4.2 	| – Sprint 3   Implementation of all the User stories 	| To-Do 	| 100 	| $350  	| $35,000  	|
| 4.3 	| – Sprint 3 Demo   and Client Acceptance 	| To-Do 	| 30 	| $350  	| $10,500  	|
| 4.5 	| – MVP 3 release 	| To-Do 	|   	|   	|  	|
| 5 	| Sprint 4   (GDP-2) all sprints 	|   	| 540 	| $350  	| $189,000  	|
| 5.1 	| – Sprint 4   Planning of User stories 	| To-Do 	|   	|   	|  	|
| 5.2 	| – Iteration of   all the tasks 	| To-Do 	|   	|   	|  	|
| 5.3 	| – Testing the   application and client approval 	| To-Do 	|   	|   	|  	|
| 5.5 	| – MVP 4 release 	| To-Do 	|   	|   	|  	|
|   	| TOTAL 	|   	|   	|   	| $448,000  	|


- The team cost per hour is $350.
- The developers required for this application is 6.
- The estimated total cost for this application is $448,000 as mentioned in the cost estimation table.



## Risks and Challenges:
- The app is based on the locations and to find the location accurately GPS is to be used which could a challenging and tricky task.
- This game is based on finding the locations which are outdoor and given the present scenario social distancing must be followed to play this game.
- The specification of the location coordinates in the game is also a challenging part.
- Handling data will be a issue here as any player can leave and join a new team whenever he desires to. This will make the desiging the database a difficult task.


## Advantages:
- This game helps the players in physical activity as the players have to walk around to find the locations.
- This also helps the players to build the healthy competition thereby bringing the people together.

## Technology Stack:
- THis is going to be a Progressive Web Application.
- HTML.
- CSS/Bootstrap.
- JavaScript.

## Acceptance Criteria:

- Each player must have a smart phone or a PC.
- Should be able to plan the route using location.
- One must have some knowledge to accumulate the clues and reach the treasure.

# User Stories:

## Sprint - 1
## User Story - 1
- As a User I want to login/Signup for the game.
## Acceptance criteria:
- The User should have a valid email Id to Signup for the game.
- Upon signing up for the game the user will be prompted to enter a username/nickname of his choice.
- If the entered username/nickname is alraedy taken then he/she will prompted the same and after this point he/she will be identified as a player.
- If the user has already signed up for the game he/she can login with the username and password.
- The user Id should be persisted in the database along with the user's info when completing the registration.

## User Story - 2
As a user I want to create a team.
## Acceptance Criteria:
- The User can create a team upon signing up and he/she will prompted to enter a team name.
- The user who creates a team will serve as the captain.
- The user Id of this person  and the info the team should be added into the database as the captain and should be retrievable whenever required. 

## User Story - 3
As a User I want to Join a Team.
## Acceptance Criteria:
- The User can join any team he/she wishes to and will have to search for the team name he/she wants to join.
- Once he/she decides a team to join he/she will have to send a request to join their team.
- The user should be able to access all the teams available for him/her to join.


## User Story - 4
As a User(captain) I want to accept/decline an invite of a player.
## Acceptance Criteria:
- The user can accept/decline an invite of another player after looking up his/her invitation.
- The request should be visible in the notifications to the team/team captain.

## User Story - 5
As a user I want to act as the huntmaster and create quest.
## Acceptance Criteria:
- The user who is hunt master will be able to create quests.
- The huntmaster is assigned to only one person and the userid and other info is stored in the database such that only he can access the page of the create quest.

## User story - 6
As a User(huntmaster) I want to add multiple locations in a single quest.
## Acceptance Criteria:
- The user can add multiple locations in creating a quest page.
- The locations added can be only be accessed after decoding the clue and only one location has to be released and once that person reaches that location then the clue for the next location is to be displayed from the database and so on until all the locations are finished.

## User Story - 7
As a User, I want to join a competition.
## Acceptance Criteria:
- The user can join a competition when the competition starts.
- Once the competition is open, teams which are stored in the database should be able to join the competition. 
- If a new team is formed after the start date of the competition they should still be able to join the competition until and unless the competition is closed.

# Sprint - 2
## User Story - 8
As a User, I want to join a competition when it starts.
## Acceptance Criteria:
- The user will get to know about the competition via notifications.
- A notification is to be sent to all the users who have registered ids prior to the start of the competition.

## User Story - 9
As a User I want to know about the scoring details of the competition.
## Acceptance Criteria:
- The user can look at the info about the scoring in the about page.
- An about page is to created for the users and the information regarding the competition and its scoring details are to be mentioned in it.

## User Story - 10
- As a User I want to look at the points scored by the team.
## Acceptance Criteria:
- The user can access this detail on the leaderboard page.
- A leaderboard page is to be created and the points scored by the team are to displayed in the descending order i.e the team with the highest points should be displayed with team name and their points on the top indicating that they are in the first position.

## User Story - 11
As a user I want to know how the team points are calculated.
## Acceptance Criteria:
- The user who is in a team will earn points and all the points by the team members together are counted as the team points.
- The scoring criteria determined in the competition are to be identified and implemented once the person reaches the location and these points should be stored in the database. these should be retrievable whenever the user wishes to look at the team score.
- The position of other teams and their points should be visible to all the teams in the competition.

## User story - 12
As a User I want to know the limit of the players per team.
## Acceptance Criteria :
- The user will be able to add a maximum of 3 players making it a team of 4 players.
- The user should be given a provision to add the players and once the max limit is reached the user should be notified with a message stating max limit reached.    

## User story - 13

As a user I want to leave the team and join other team.

## Acceptance criteria:

- The user can leave the team and join other by sending a request to that other team.
- However the user cannot leave the team once the competition starts. He can only leave the team after the completion of competition or before the start of the competition.
- The respective data is to be stored in the database as per the changes of the user and should be allowed to do that.

## User story - 14

As a User I want to change my nick name.

## Acceptance criteria:

- The user is allowed to change the nick name whenever he desires to.
- The user is allowed to change the nickname and the data is crosschecked with the existing the names and if they overlap the user should be prompted with the message name already taken, select another name.
- This process repeats until a unique name is entered by the user.

## User story - 15

As a User  I want to create multiple accounts under one user id.

## Acceptance criteria:

- The user cannot create the multiple accounts under a single userid.
- The data base will be created in such a way that every player will get a unique id associated with the mail provided and hence the user cannot create multiple accounts under one id.
- If the user wants to maintain multiple acconts user has to provide multiple emial id as it will be the primary key for generating the userid.

## User Story - 16

As a user I want to know how many more locations are left to be found out.

## Acceptance criteria:

- The user can see this in the competition page where the player will participate.
- The application should be designed such that the user can view the completed and to be completed status in the competition page.
- If all the locations are finished then the competition bar should change its color.

## User story -17

As a user I want hints if I am unable to crack the clue.

## Acceptance criteria:

- The user can ask for hints if he/she is unable to crack the clue.
- There should be provision for the hints in the database and the hint should be popped up on the screen if the user wishes for the hints in the clue page.

# Sprint - 3
## User story - 18

As a user I want to know if there are any points reduced if I use the hints field.

## Acceptance criteria:

- The user will not be awarded if he uses the hints field to find out a location.
- The program for this will coded to award less points to the player if they use the hints field even though he reaches that location first.

## User story - 19

As a User I want assistance in finding a location.

## Acceptance criteria:

- The user will be assisted after he cracks the clue and location corrdinates are provided to him.
- Third part applications will be used to giude th euser by providing a route mao to the user.

## User story - 20

As a user I want to hear instructions while going to that location.

## Acceptance criteria:

- The user can hear to the instructions while he/she is on the way to the location.
- The javascript code will be designed such that the instructions can be heard on the way to the location.
 
## User story - 21

As a user I wish to mute the instructions.

## Acceptance criteria:

- The user will be able to mute the instructions in the settings page.
- The settings page will be provided with the option of sound off so that the user who wishes to mute the instructions can mute it.

## User story - 22

As a user I want to look at my profile.

## Acceptance criteria:

- The user can access their account in the settings page.
- The settings page will be provided with the account info and will be accsseble from the database when the user clicks on the account icon/tab.

## User story - 23

As a user I want to look at all the settings available for the game.

## Acceptance criteria:

- The user will be provided with the setting icon/tab so thet he can see the settings available for the game.
- The home page will be designed with the settings icon/tab for the user to redirect him to the setting page to access it.

## User story - 24

As a User I want to  know if I can create a quest for the competition.

## Acceptance criteria:

- The user will not have access to create a quest except huntmaster.
- The data base will be designed such a way that the normal user will not be able to see the create quest option as this game is designed such a way that only huntmaster can create the quests and start compettion.

# Sprint - 4 (Scheduled for GDP-2)

- Planning of User stories
- Iteration of all the tasks
- Testing the application and client approval
- MVP 4 release

# Rapid MVP Team Links

## Jira Link :
 [jira Link](https://vikasbaswapuram.atlassian.net/secure/RapidBoard.jspa?rapidView=2&projectKey=NQHG&view=planning&selectedIssue=NQHG-8&issueLimit=100)


# Proposed screens : 

## Home page: 
This emphasises the color of our college.
<img src = "proposed\homepage.jpeg">

## Leaderboard Page:
This the page where the points earned by different teams are displayed(Highest points to lowest points)
<img src = "proposed\Leaderboard.png">

## Quest Creation Page: This is the page where the Hunt master creates a new quest. 

<img src = "proposed\quest.png">

## Challenges Page:
This is the page where all the challenges are displayed for the teams to participate.

<img src = "proposed\Competition.png">

## Settings Page:
This is the page where user's profile can be edited, about, help and logout options are provided.
<img src = "proposed\Settings.png">

## Game Page:
This is the page where the user can be able to view the map of Northwest Missouri state University and can be able to access the clues.
<img src = "proposed/Game_Screen.png">

## Jira screenshot : 
<img src ="Images\jira_screenshot1.PNG">
<img src ="Images\jira_screenshot2.PNG">
<img src ="Images\jira_screenshot3.PNG">
<img src ="Images\jira_screenshot4.PNG">

## Original RFP:
[RFP](https://github.com/denisecase/rfp-hunt/blob/master/rfp-hunt.md)

## References:
- [Youtube](https://www.youtube.com/watch?v=DO9ZRo2jU3w)
- [Markdown Syntax](https://www.markdownguide.org/cheat-sheet/)
- [RFP](https://clearbridgemobile.com/how-to-write-an-amazing-mobile-app-rfp/)
