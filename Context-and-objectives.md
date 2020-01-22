# Context and objectives

In Edifixio, people uses to work on several projects managed by different tools. We wanted an application which allow people to collaborate and share project information in one unique tool, and which could be used for scrum meeting, as a virtual paper board. 

This application could connect to other systems like JIRA or Sales Force and we wanted it to be fully customizable.

## deNote - For who ?
Companies with n-shores teams need cloud app to share information and collaborate through several projects. deNote has been built with the idea of a virtual paper board where sticky elements could be pinned up. 

Elements can be Tasks, images, shapes, texts… The application must allow user to see live updates which occurs on an element (move, update of information, deletion…).

People can collaborate on multiple projects by separating sticky elements in different boards, highly customizable.

## Concepts
### BIlling Units, Clients, Projects
People working of several projects must have a classification in order to organize their boards. deNote has a 3-levels hierarchy.
First level is Business unit (BU). It represents a unit or practice in a company.
Second level is Client. It represents the final client people work for.
Third level is project. It’s the last level of the hierarchy containing the boards. Rights and accesses are managed in that level.

### Boards and stickies
Board is like a paper board sheet. It has a name, width and height.
Stickies are elements that can be pinned up on a board. It can be anything, like text, shape, image or more complex types (see [sticky type section](Sticky-Types)). 

It is important to consider all visual elements on a board as a sticky.

Sticky can be moved using the mouse and you can perform actions on it, like duplication or locking. You can also put a sticky on the top of anothers or put it in background (See section Use boards). 

### Live updates
Multiple users can be connected to the same boards, and that’s the aim of the application. One of the key concept in deNote is that when an action is performed on a sticky (move, update…), other users connected to the board can see the update live, just like if they are near to a real paper board. Meaning that when you are in a scrum meeting, when a user moves a sticky or creates a new one, you see immediately the action on your screen.

### Access rights
Access rights are managed on the project level. There are 4 main roles.

- *Billing Unit Admin*
- *Project Admin* 
- *User*
- *Viewver*

See  [Role section](Roles) for more details.


