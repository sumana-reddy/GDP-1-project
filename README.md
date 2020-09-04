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

<table class="tg">
<thead>
  <tr>
    <th class="tg-0lax">WBS NO.</th>
    <th class="tg-0lax">TASK NAME</th>
    <th class="tg-0lax">STATUS</th>
    <th class="tg-0lax">DURATION in hrs</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0lax"><b>1</b></td>
    <td class="tg-0lax"><b>Sprint 0<b></td>
    <td class="tg-0lax"><b>-</b></td>
    <td class="tg-0lax"><b>200</b></td>
  </tr>
  <tr>
    <td class="tg-0lax">1.1</td>
    <td class="tg-0lax">User stories prioritization</td>
    <td class="tg-0lax">Done</td>
    <td class="tg-0lax">25</td>
  </tr>
  <tr>
    <td class="tg-0lax">1.2</td>
    <td class="tg-0lax">ER-Diagram development</td>
    <td class="tg-0lax">Done</td>
    <td class="tg-0lax">25</td>
  </tr>
  <tr>
    <td class="tg-0lax">1.3</td>
    <td class="tg-0lax">Sample data</td>
    <td class="tg-0lax">Done</td>
    <td class="tg-0lax">25</td>
  </tr>
  <tr>
    <td class="tg-0lax">1.4</td>
    <td class="tg-0lax">Schedule management plan</td>
    <td class="tg-0lax">In-progress</td>
    <td class="tg-0lax">25</td>
  </tr>
  <tr>
    <td class="tg-0lax">1.5</td>
    <td class="tg-0lax">Cost estimation</td>
    <td class="tg-0lax">Done</td>
    <td class="tg-0lax">20</td>
  </tr>
  <tr>
    <td class="tg-0lax">1.6</td>
    <td class="tg-0lax">Proposed UI screens development</td>
    <td class="tg-0lax">In-progress</td>
    <td class="tg-0lax">30</td>
  </tr>
  <tr>
    <td class="tg-0lax">1.7</td>
    <td class="tg-0lax">Jira setups</td>
    <td class="tg-0lax">Done</td>
    <td class="tg-0lax">24</td>
  </tr>
  <tr>
    <td class="tg-0lax">1.8</td>
    <td class="tg-0lax">User authorization</td>
    <td class="tg-0lax">Done</td>
    <td class="tg-0lax">26</td>
  </tr>
  <tr>
    <td class="tg-0lax"><b>2</b></td>
    <td class="tg-0lax"><b>Sprint 1</b></td>
    <td class="tg-0lax"><b>-</b></td>
    <td class="tg-0lax"><b>200</b></td>
  </tr>
  <tr>
    <td class="tg-0lax">2.1</td>
    <td class="tg-0lax">Sprint 1 planning</td>
    <td class="tg-0lax">To-Do</td>
    <td class="tg-0lax">35</td>
  </tr>
  <tr>
    <td class="tg-0lax">2.2</td>
    <td class="tg-0lax">Sprint 1 execution</td>
    <td class="tg-0lax">To-Do</td>
    <td class="tg-0lax">35</td>
  </tr>
  <tr>
    <td class="tg-0lax">2.3</td>
    <td class="tg-0lax">Sprint 1 Demo and User authorization</td>
    <td class="tg-0lax">To-Do</td>
    <td class="tg-0lax">35</td>
  </tr>
  <tr>
    <td class="tg-0lax">2.4</td>
    <td class="tg-0lax">Sprint 1 implementation</td>
    <td class="tg-0lax">To-Do</td>
    <td class="tg-0lax">45</td>
  </tr>
  <tr>
    <td class="tg-0lax">2.5</td>
    <td class="tg-0lax">MVP 1 release</td>
    <td class="tg-0lax">To-Do</td>
    <td class="tg-0lax">50</td>
  </tr>
  <tr>
    <td class="tg-0lax"><b>3</b></td>
    <td class="tg-0lax"><b>Sprint 2</b></td>
    <td class="tg-0lax"><b>-</b></td>
    <td class="tg-0lax"><b>200</b></td>
  </tr>
  <tr>
    <td class="tg-0lax">3.1</td>
    <td class="tg-0lax">Sprint 2 planning</td>
    <td class="tg-0lax">To-Do</td>
    <td class="tg-0lax">35</td>
  </tr>
  <tr>
    <td class="tg-0lax">3.2</td>
    <td class="tg-0lax">Sprint 2 execution</td>
    <td class="tg-0lax">To-Do</td>
    <td class="tg-0lax">35</td>
  </tr>
  <tr>
    <td class="tg-0lax">3.3</td>
    <td class="tg-0lax">Sprint 2 Demo and User authorization</td>
    <td class="tg-0lax">To-Do</td>
    <td class="tg-0lax">35</td>
  </tr>
  <tr>
    <td class="tg-0lax">3.4</td>
    <td class="tg-0lax">Sprint 2 implementation</td>
    <td class="tg-0lax">To-Do</td>
    <td class="tg-0lax">45</td>
  </tr>
  <tr>
    <td class="tg-0lax">3.5</td>
    <td class="tg-0lax">MVP 2 release</td>
    <td class="tg-0lax">To-Do</td>
    <td class="tg-0lax">50</td>
  </tr>
  <tr>
    <td class="tg-0lax"><b>4</b></td>
    <td class="tg-0lax"><b>Sprint 3</b></td>
    <td class="tg-0lax"><b>-</b></td>
    <td class="tg-0lax"><b>200</b></td>
  </tr>
  <tr>
    <td class="tg-0lax">4.1</td>
    <td class="tg-0lax">Sprint 3 planning</td>
    <td class="tg-0lax">To-Do</td>
    <td class="tg-0lax">35</td>
  </tr>
  <tr>
    <td class="tg-0lax">4.2</td>
    <td class="tg-0lax">Sprint 3 execution</td>
    <td class="tg-0lax">To-Do</td>
    <td class="tg-0lax">35</td>
  </tr>
  <tr>
    <td class="tg-0lax">4.3</td>
    <td class="tg-0lax">Sprint 3 Demo and User authorization</td>
    <td class="tg-0lax">To-Do</td>
    <td class="tg-0lax">35</td>
  </tr>
  <tr>
    <td class="tg-0lax">4.4</td>
    <td class="tg-0lax">Sprint 3 implementation</td>
    <td class="tg-0lax">To-Do</td>
    <td class="tg-0lax">45</td>
  </tr>
  <tr>
    <td class="tg-0lax">4.5</td>
    <td class="tg-0lax">MVP 3 release</td>
    <td class="tg-0lax">To-Do</td>
    <td class="tg-0lax">50</td>
  </tr>
  <tr>
    <td class="tg-0lax"><b>5</b></td>
    <td class="tg-0lax"><b>Sprint 4 (GDP 2) all sprints</b></td>
    <td class="tg-0lax"><b>-</b></td>
    <td class="tg-0lax"><b>600</b></td>
  </tr>
  <tr>
    <td class="tg-0lax">5.1</td>
    <td class="tg-0lax">Sprint 4 planning</td>
    <td class="tg-0lax">To-Do</td>
    <td class="tg-0lax">100</td>
  </tr>
  <tr>
    <td class="tg-0lax">5.2</td>
    <td class="tg-0lax">Sprint 4 execution</td>
    <td class="tg-0lax">To-Do</td>
    <td class="tg-0lax">140</td>
  </tr>
  <tr>
    <td class="tg-0lax">5.3</td>
    <td class="tg-0lax">Sprint 4 Demo and User authorization</td>
    <td class="tg-0lax">To-Do</td>
    <td class="tg-0lax">140</td>
  </tr>
  <tr>
    <td class="tg-0lax">5.4</td>
    <td class="tg-0lax">Sprint 4 implementation</td>
    <td class="tg-0lax">To-Do</td>
    <td class="tg-0lax">115</td>
  </tr>
  <tr>
    <td class="tg-0lax">5.5</td>
    <td class="tg-0lax">MVP 4 release</td>
    <td class="tg-0lax">To-Do</td>
    <td class="tg-0lax">105</td>
  </tr>

</tbody>
</table>


## Updated Cost Estimate 

|                                    PROJECT   COST ESTIMATE  |                                        |             |                   |                 |                       |   |
|-------------------------------------------------------------|----------------------------------------|-------------|-------------------|-----------------|-----------------------|---|
|                                                             | PROJECT TITLE                          |             |                   |                 |                       |   |
|                                                             |       Northwest Gaming Application     |             |                   |                 |                       |   |
|                                                             |                                        |             |                   |                 |                       |   |
|                           WBS NO.                           |                 TASK NAME              |    STATUS   | DURATION in hours | TOTAL TEAM COST | TOTAL COST PER   WEEK |   |
|                              1                              |                 Sprint 0               |             |        200        |                 |                
|                             1.1                             |   User stories prioritization          |     Done    |         25        |      $350       |        $8,750         |   |
|                             1.2                             |   ER-Diagram development               |     Done    |         25        |      $350       |        $8,750         |   |
|                             1.3                             |   Sample data                          |     Done    |         25        |      $350       |        $8,750         |   |
|                             1.4                             |   Schedule management plan             | In-progress |         25        |      $350       |        $8,750         |   |
|                             1.5                             |   cost estimation                      |     Done    |         20        |      $350       |        $7,000         |   |
|                             1.6                             |   proposed UI screens development      | In-progress |         30        |      $350       |        $10,500        |   |
|                             1.7                             |   Jira setups                          |     Done    |         24        |      $350       |        $8,400         |   |
|                             1.8                             |   User authorization                   |     Done    |         26        |      $350       |        $9,100         |   |
|                              2                              |                Sprint   1              |             |        200        |                 |              
|                             2.1                             |   Sprint 1 planning                    |    To-Do    |         35        |      $350       |        $12,250        |   |
|                             2.2                             |   Sprint 1 execution                   |    To-Do    |         35        |      $350       |        $12,250        |   |
|                             2.3                             |   Sprint 1 Demo and user authorization |    To-Do    |         35        |      $350       |        $12,250        |   |
|                             2.4                             |   Sprint 1 implementation              |    To-Do    |         45        |      $350       |        $15,750        |   |
|                             2.5                             |   MVP 1 release                        |    To-Do    |         50        |      $350       |        $17,500        |   |
|                              3                              |                Sprint   2              |             |        200        |                 |              
|                             3.1                             |   Sprint 2 planning                    |    To-Do    |         35        |      $350       |        $12,250        |   |
|                             3.2                             |   Sprint 2 execution                   |    To-Do    |         35        |      $350       |        $12,250        |   |
|                             3.3                             |   Sprint 2 Demo and user authorization |    To-Do    |         35        |      $350       |        $12,250        |   |
|                             3.4                             |   Sprint 2 implementation              |    To-Do    |         45        |      $350       |        $15,750        |   |
|                             3.5                             |   MVP 2 release                        |    To-Do    |         50        |      $350       |        $17,500        |   |
|                              4                              |                Sprint   3              |             |        200        |                 |               
|                             4.1                             |   Sprint 3 planning                    |    To-Do    |         35        |      $350       |        $12,250        |   |
|                             4.2                             |   Sprint 3 execution                   |    To-Do    |         35        |      $350       |        $12,250        |   |
|                             4.3                             |   Sprint 3 Demo and user authorization |    To-Do    |         35        |      $350       |        $12,250        |   |
|                             4.4                             |   Sprint 3 implementation              |    To-Do    |         45        |      $350       |        $15,750        |   |
|                             4.5                             |   MVP 3 release                        |    To-Do    |         50        |      $350       |        $17,500        |   |
|                              4                              |            Sprint   4 (GDP-2)          |             |        200        |                 |               
|                             4.1                             |   Sprint 4 planning                    |    To-Do    |         35        |      $350       |        $12,250        |   |
|                             4.2                             |   Sprint 4 execution                   |    To-Do    |         35        |      $350       |        $12,250        |   |
|                             4.3                             |   Sprint 4 Demo and user authorization |    To-Do    |         35        |      $350       |        $12,250        |   |
|                             4.4                             |   Sprint 4 implementation              |    To-Do    |         45        |      $350       |        $15,750        |   |
|                             4.5                             |   MVP 4 release                        |    To-Do    |         50        |      $350       |        $17,500        |   |
|                                                             |     TOTAL PROJECT COST                 |             |                   |                 |        $350,000        |



- The developers required for this application is 6.
- The estimated total cost for this application is $115,500 as mentioned in the cost estimation table.

## Updated cost estimate as per client reviews 



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

## User Stories:

## Sprint - 1
# User Story - 1
As a User I want to login/Signup for the game.
# Acceptance criteria:
The User should have a valid email Id to Signup for the game.
Upon signing up for the game the user will be prompted to enter a username/nickname of his choice.
If the entered username/nickname is alraedy taken then he will prompted the same and after this point he will bee identified as a player.
If the user has already signed up for the game he can login with the username and password.
The user Id should be persisted in the database along with the user's info when completing the registration.

# User Story - 2
As a user I want to create a team.
# Acceptance Criteria:
The User can create a team upon signing up and he will prompted to enter a team name.
The user who creates a team will serve as the captain.
The user Id of this person  and the info the team should be added into the database as the captain and should be retrievable whenever required. 

# User Story - 3
As a User I want to Join a Team.
# Acceptance Criteria:
The User can join any team he wishes to and will have to search for the team name he wants to join.
Once he decides a team to join he will have to send a request to join their team.
The user should be able to access all the teams available for him to join.


# User Story - 4
As a User(captain) I want to accept/decline an invite of a player.
# Acceptance Criteria:
The user can accept/decline an invite of another player after looking up his invitation.
The request should be visible in the notifications to the team/team captain.

# User Story - 5
As a Data developer ERD is to be developed based on the entities mentioned in the RFP.
# Acceptance Criteria:
The given Task for the development of the ERD has been finished and yet to be reviewed. The developed ERD has been updated in the Team repository.

# User story - 6
As a developer a set of sample data is to be assumed and check for the desired possible outcome.
# Acceptance Criteria:
A set of sample data was taken and were roughly tested to look for the possible outcome and it worked and for which a flow chart is developed and mentioned above.

# User Story - 7
As a UI/FrontEnd developer proposed screens for the application are to be craeted and displayed.
# Acceptance Criteria:
A set of proposed screens were designed using online design tool(Figmaa) and are yet to be reviwed by the client. These are also subject to change after the feedback/review from the client presentation.

# User Story - 8
As a developer the requirements are to be determined for the application to be developed.
# Acceptance Criteria:
The initial requirements are identified and were mentioned in the read me file and these are subject to change based on the requirements provided by the client if any.

## Sprint - 2
# User Story - 9
As a team Project Signoff is be made with outmost care with clear details about everything
# Acceptance Criteria:
The project manager will take care of this signoff after regular meetings with the client.

# User Story - 10
Project Flyer
# Acceptance Criteria:
A roject flyer is prepared and passe on to kick start the project.

# User Story - 11
 As a Team the schedule for the MVP releases are set.
# Acceptance Criteria:
The shedule is decided and developers start working based on the requirements.

## Sprint - 3( Scheduled  for the GDP-2)
# UI development finalisation
# BackEnd development
# Testing the application
# Deployment of the application

## Rapid MVP Team Links

- Jira : [jira Link](https://vikasbaswapuram.atlassian.net/secure/RapidBoard.jspa?rapidView=1&projectKey=NGA&selectedIssue=NGA-1)


## proposed screens : 
# Home page: 
This emphasises the color of our college.
<img src = "proposed\homepage.jpeg">

# Leaderboard Page:
This the page where the points earned by different teams are displayed(Highest points to lowest points)
<img src = "proposed\Leaderboard.png">

# Quest Creation Page: This is the page where the Hunt master creates a new quest. 

<img src = "proposed\quest.png">

# Challenges Page:
This is the page where all the challenges are displayed for the teams to participate.

<img src = "proposed\Competition.png">

# Settings Page:
This is th epage where user's profile can be edited, about, help and logout options are provided.
<img src = "proposed\Settings.png">

## Jira screenshot : 
<img src ="Images\updated_jira.PNG">

## Original RFP:
[RFP](https://github.com/denisecase/rfp-hunt/blob/master/rfp-hunt.md)

## References:
- [Youtube](https://www.youtube.com/watch?v=DO9ZRo2jU3w)
- [Markdown Syntax](https://www.markdownguide.org/cheat-sheet/)
- [RFP](https://clearbridgemobile.com/how-to-write-an-amazing-mobile-app-rfp/)
