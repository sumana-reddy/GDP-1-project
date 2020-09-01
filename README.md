# Northwest Gaming Appplication

## Project Charter

This is the project charter for the Northwest Gaming Application. This Application will be developed as a Progressive Web application.

## Project Purpose:
This is a mobile gaming application which enables the players(users of this game) to complete a quest which is finding out specific set of location based on the clues provided. This is a fun game aimed at involving the students at northwest missouri state unniversity to make their respective teams and participate in the competition to score maximum points based on the level of the difficulty. The team with maximum points wins the competition.

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
    <td class="tg-0lax">s538395@nwmissouri.edu</td>
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
<img src="proposed\Final ERD.jpeg">

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

<img src="Images\sample data.PNG">

## Schedule Management
<img src="Images\xcel.jpeg">

## Cost Estimate

|    Work   Breakdown Structure Categories    | Total Team Cost | No. of Hours   per week | Total cost per   week | Total cost for   three sprints |   |
|:-------------------------------------------:|-----------------|-------------------------|-----------------------|--------------------------------|---|
| Initiating                                  | $350            | 9                       | $3,150                | 18,900                         |   |
| Planning                                    | $350            | 12                      | $4,200                | $25,200                        |   |
| Designing                                   | $350            | 11                      | $3,850                | $23,100                        |   |
|     UI Design                               | 0               | 4                       | 0                     | 0                              |   |
|     Synthesis of Design                     | 0               | 4                       | 0                     | 0                              |   |
|     Implementation Iteration                | 0               | 3                       | 0                     | 0                              |   |
|     Early release and contract finalization | 0               | 3                       | 0                     | 0                              |   |
| Implementation                              | $350            | 12                      | $4,200                | $25,200                        |   |
|     Application Development                 | 0               | 6                       | 0                     | 0                              |   |
|     PWA Implementation                      | 0               | 3                       | 0                     | 0                              |   |
|     Android/IOS implementation              | 0               | 3                       | 0                     | 0                              |   |
| Monitoring and   controlling                | $350            | 11                      | $3,850                | $23,100                        |   |
| Closing                                     | $350            | 10                      | $3,500                | $21,000                        |   |
| Total                                       |                 |                         |                       | $136,500                       |   |
|                                             |                 |                         |                       |                                |   |

- The developers required for this application is 6.
- The estimated total cost for this application is $136500 as mentioned in the cost estimation table.

## Risks and Challenges:
- The app is based on the locations and to find the location accurately GPS is to be used which could a challenging and tricky task.
- This game is based on finding the locations which are outdoor and given the present scenario social distancing must be followed to play this game.

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
As a User any student with a valid email can sigup and play the game.
# Acceptance criteria:
Being a UI developer for this application I take up this task and make sure it works out for every valid email.

# User Story - 2
As a Team a proposal document is to be created for this Northwest Gaming Application
# Acceptance Criteria:
All the team members are discussing the essential requirements and have come up with the requirements with is yet to be presented.

# User Story - 3
As a Team Schedule for this application is to be charted down.
# Acceptance Criteria:
All the team members have met in a place and an estimate is recorded taking all the things into consideration and this is aldo due for the presentation.

# User Story - 4
As a Team Budget/Cost estimation for this application to develop is to be decided.
# Acceptance Criteria:
This is a tricky task but yet an estimate is generated which might be subject to change based on the feedback/review of the client.

# User Story - 5
As a Data developer ERD is to be developed based on the entities mentioned in the RFP
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
<img src = "proposed\Leaderboard.jpeg">

# Quest Creation Page: This is the page where the Hunt master creates a new quest. 

<img src = "proposed\quest.jpeg">

# Challenges Page:
This is the page where all the challenges are displayed for the teams to participate.
<img src = "proposed\challenge.jpeg">

# Settings Page:
This is th epage where user's profile can be edited, about, help and logout options are provided.
<img src = "proposed\setting.jpeg">

## Jira screenshot : 
<img src ="Images\updated_jira.PNG">

## Original RFP:
[RFP](https://github.com/denisecase/rfp-hunt/blob/master/rfp-hunt.md)

## References:
- [Youtube](https://www.youtube.com/watch?v=DO9ZRo2jU3w)
- [Markdown Syntax](https://www.markdownguide.org/cheat-sheet/)
- [RFP](https://clearbridgemobile.com/how-to-write-an-amazing-mobile-app-rfp/)
