## Stage 1

[Home](README.md)  

***Due Friday February 10th at Midnight***

In this Stage, your team will do the first steps of the high level design of your software for the team project.  Most of the work you do for Stage 1 will depend on your returned project proposal from Stage 0. For your core design (including UML, UI mockups, etc.) you will incorporate **required features** first. You still have an opportunity to consider additional features, but these do not need to appear in your initial design for this Stage. See below for details.

Your team will create several pages for your website. Websited should be hosted using GitHub Pages from your 
team's main GitHub repository. You will also create documents for User Stories and Tasks and submit them by e-mail to your TA and Ethan.

## Required Web Pages  

Your project website will be used to introduce your team and your project to the world. You will update your website
throughout the project to reflect your progress. Part of a suitable role for a team member would be to maintain the site.  

At the deadline, your website must include:

* Home Page  
* Team Roster Page  
* Software Design Page  
* UI Design Page  
* Project Plan Page  

Each page should be titled appropriately and be clearly organized. Keep the content simple and uncluttered.

### Home Page  

Include your team name and number (e.g. InterSlice - CS 2212 Team X) and a brief description of the project you are developing.  

### Team Roster Page  

The page must include a list of all your team's members and a brief summary of each member's skills/background/hobbies/philosophy/whatever. You should also list any roles or responsibilities that have been delegated
to members (e.g. Code Champion, Repo Hero, Database Ace, Team Overseer, UX Guru, etc.) Be creative!

### Software Design Page  

This page will outline the design of your project and will consist, for now, of a UML class diagram. More details below.

### UI Design Page  

Write a brief description of the look and feel you want your program to have, or cite an existing design language (e.g. minimal, Material Design, flat design, etc.) You could also cite an existing application or website as a source of inspiration. Describe at a very high level how users will interact with your software.  

This page should also include mock-ups of screens or views you plan to include in your application. You should use, at the very least, a vector graphics based drawing tool to create examples. You could also use photos of a whiteboard drawing as long as they are *exceptionally* clear and easy to understand. Better yet, why not search for a free mock-up tool online to generate these for you? You might find something useful.

No matter the format, ensure that your UI Design Page portrays the intended interfaces for all of your application's user facing features, and how users will navigate between them.  

### Project Plan Page  

When your project proposal is returned, we may include under-specified features that we would like to see added. These will be under-specified in order to challenge your creativity. Use this page to propose any additional features your team would like to add to the project. Either in response to the returned proposal, or for something completely new, you must include:  

* A title for the new feature or component  
* A brief description  
* A detailed and itemized feasibility statement and implementation plan  
* A brief statement about the rest of the project's dependency on this feature  

---

## UML Class Diagram

Your team will create a class diagram to represent the intended design of your software.

Your diagram must have sensible classes, attributes, methods, associations, and hierarchies (where applicable). These should attempt to capture the requirements as completely as possible. At this stage, however, we do not expect deeper details such as types or access modifiers. Also, you do *not need to model user interface classes* in your UML diagram.  

For now, it is most important for us to see that you are adhering to a high-level design pattern, MVC in particular. If you are using Grails, show us how it is helping you adhere to the design pattern. No matter your choice of programming framework, try to follow a basic MVC-based approach.

To summarize MVC:  

> In MVC, we do not write code in UI classes to call the various APIs, perform computations, or access the database directly. This would result in too-heavily-coupled, redundant code. Instead, Views are implemented to give a presentation of data accessed or computed at the Model level. This enables the implementation of multiple Views for the same data.

> For example, the Model may contain classes that retrieve stock information such as names, ratings, prices, etc., and aggregate them into a single object. Multiple views may be implemented to display this information in different ways, or in different places.

> Controller classes are responsible for responding to user actions. When a user interacts with the UI, a Controller class will typically respond to the user action and update the Model level accordingly. For example, suppose a user has purchased multiple stocks and wants to track their price changes over a period of 30 days. A Controller class will receive this information from UI components and use corresponding Model classes to store the new information in the database.

Again, at this Stage of your project you do not need to model classes for your UI. You should, however, model classes that will *respond* to your UI, as well as the classes that will perform computations, call APIs, and interact with your database.

To generate your diagrams, you can find an abundance of software online to help such as [UML Designer for Eclipse](https://marketplace.eclipse.org/content/uml-designer). You can use any software you like as long as the diagram is clean and easy to follow. [Here is an example](/CS2212B-2017/resources/UML.png) of an acceptable-looking diagram from 2 years ago.

## User Stories and Tasks

Your team must then create all user stories that you think will be needed for the project including additional components (including proposed components). If you are using GitHub for project management, you can use a combination of Issues (with Milestones) and Projects to list user stories and assign them to a team member. Details about these can always be revised later - but it's important to get a sense of how GitHub's (basic) project management features work.  

Each user story should include:  

* The story itself  
* Any acceptance criteria  
* Assigned team member(s)  
* Associated Milestone with Due Date (if applicable)  

Find an example of a (very) simple user story [here](/CS2212B-2017/resources/Story.png). User stories should be simple and focus on the user's interaction with the software. They are meant to be high level rather than technical. The user doesn't care what database service you're using, they only care whether they can access the feature (reliably).
