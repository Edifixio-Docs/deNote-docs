# deNote - User guide

In Edifixio, people uses to work on different projects managed by different tools. We thought about an application that allow people to collaborate and share project information in one unique tool, and that could be used for scrum meeting, as a virtual paper board. This application could connect to other systems like JIRA or Sales Force and we want it to be fully customizable.

## deNote - For what?
Company with n-shores teams need cloud app to share information and collaborate through the projects. DeNote has been built with the idea of a virtual paper board where sticky elements could be pinned up. Element can be a Task, image, shape, Text… The application must allow user to see live any update that occurs on an element (move, update of information, deletion…).
People can collaborate on multiple project by separating sticky elements in different boards, highly customizable.

## Concepts
### BUs, clients, projects
People who works of multiple projects must have a classification in order to organize their boards. DeNote has a 3-levels hierarchy.
First level is Business unit (BU). It represents a unit or practice in a company.
Second level is Client. It represents the final client people work for.
Third level is project. It’s the last level of the hierarchy containing the boards. Rights and accesses are managed in that level.

### Boards and stickies
Board is like a paper board sheet. It has a name, width and height.
Stickies are elements that can be pinned up on a board. It can be anything, like Text, shape, image or more complex type (see section Sticky type list). It is important to consider that all visual element on a board is a sticky.
Sticky can be moved using the mouse and you can perform some actions on it, like duplicate one or lock it. You can also put a sticky on the top of another one or put it in background (See section Use boards). 

### Live updates
Multiple users can be connected to the same boards, and that’s the aim of the application. One of the key concept in DeNote is that when an action is performed on a sticky (move, update…), other users connected to the board can see the update live, just like if they are near to a real paper board. Meaning that when you are in a scrum meeting, when a user moves a sticky or creates a new one, you see immediately the action on your screen.

### Access rights
Access rights are managed on the project level. There are 3 roles.

- *Viewer* - A viewer can only see a board and the live updates of stickies. h can’t perform any actions or updates.
- *User* - A user has the viewer’s role plus the possibility to performs actions on stickies. He can create/update and delete them.
- *Admin* - An admin has the user’s role plus the possibility to access the project administration (see section project administration).

