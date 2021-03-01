# Tech Design Document
## Definition of a TDD
A Tech Design Document or TDD is a form that developers create when facing a new project. This document is usually written in the pre-production phase of a project and its purpose is to state all the technology related items, such as conventions, technical requirements and resources, that should be considered in the project in hand. It goes over all the software used, the coding guidelines, the milestones timeline and technical goals and risks of the game, among other technical aspects. The length of this document may vary from 1 to even 50, depending on how deep the points are going to be treated. The TDD is continuously updated throughout the development process.

## Importance of a TDD
It is important to create a TDD at the beginning of the development process so that if, in the future, a complication arises the team knows what steps to follow to solve it. Also, when new members join the team, they have a guide of how the project is being developed. Having this set of “rules” for the project also helps all team members to work in a same direction instead of everyone following its own guidelines and conventions.

## TDD vs GDD
Both a Game Design Document and a Tech Design Document are documents created at the beginning of a new project and they both state information about the game, that is why they are constantly mistaken. The main difference between the two is that, while a TDD focuses on the technical aspects of the development process, the GDD focuses on the design. A GDD is less objective and it’s created to help the understanding of the game’s idea itself and not the process of creating it practically.

## Parts of a TDD
There are lots of different templates when it comes to TDD’s. Depending on the field your project is about, you can find certain core sections or others, but even in the same area of investigation there are different sections.
These are the parts of a TDD I found most interesting taking into consideration the type of games we are developing.

### Introduction
This section is to give a reader a first feel of the game. It has two sub-sections:

**Game Summary:** In less than a paragraph, developers are able to describe the game and its main features.

**Platforms Supported:** All the platforms that support/will support the game must be mentioned.

### Features from the GDD
In this section, developers can attach the features from the GDD that help the reader understanding the development and design process of the project.

**Background:** To understand where the designers’ idea comes from, in the background sub-section all the inspiration from the game (video games, board games, videos, movies, etc.) should be written.

**Key Features:** As opposed to the background, this sub-section describes all the features that differentiate this game from any other.

**Genre:** The genre should be briefly described.

**Target Audience:** The target audience should be briefly described.

**Concept Art:** For this sub-section, a mood board should be delivered, where all the main features and characters of the game are properly represented.

![image](https://user-images.githubusercontent.com/59050152/109432623-59d10980-7a0c-11eb-9612-6dd364780aeb.png)

**Win-Lose Conditions:** The goals and risks of the gameplay have to be explained, with an answer on how to win and how to lose.

### Technical Goals
At this point, developers should have an idea on what are the goals of the game. If there are any innovative technical aspect that has never been done before or if there is an experimental mechanic, they should be explained at this section.

### Technical Risks and Alternatives
The technical risks of a game are all the difficulties and complications that the team may encounter while developing it. Most of this risks should be followed by a solution or alternative. This gives a feeling of control to the team, especially if one of the stated risks with solution arises.

### Estimated Schedule
All big project has to follow a schedule. For the team to have a general idea on what to expect, the game should be divided in milestones which need to be placed in a timeline according to importance.

![image](https://user-images.githubusercontent.com/59050152/109432635-635a7180-7a0c-11eb-9e5d-e40df5fc68c4.png)

### External Tools to Develop
Usually, when developing a project, there are external resources needed. In the following sub-sections, they have to be stated so that the team gets an overview of the material needed.

**Used Programs:** If there is any external program, it needs to be stated here.

**External Libraries:** if there is any external library, it needs to be stated here.

### Code Style Guidelines
For different developers to work in a same project, they have to adapt. This section gives kind of a “rulebook” that developers must follow in order to work faster and more efficiently.

**File Formats:** All files must follow a convention regarding its format. For example, a 2D object won’t have the same format as a sound effect.

**Naming Conventions:** All the naming conventions that the team needs to follow have to be stated in this sub-section.

**Code Preferences:** The code preferences need to go over conditionals, variables, loops, classes and structs, and XML files.

### Code Organization overview (UML)
An UML is a diagram that overviews the internal structure of the code, portcasing the relationship between all the different variables, classes and functions.

![image](https://user-images.githubusercontent.com/59050152/109432647-6ce3d980-7a0c-11eb-9ffd-a7c94c36d698.png)
![image](https://user-images.githubusercontent.com/59050152/109432652-740ae780-7a0c-11eb-8d9d-96ec1fad7457.png)

### Branch Workflow
The branch workflow needs to state what kind of branching policy the team is going to use, when they will need to create a new branch, when to merge, etc. 

![image](https://user-images.githubusercontent.com/59050152/109432661-7bca8c00-7a0c-11eb-9003-f36e000d1cb7.png)

### Code Reviews
The main goal of code reviews is that the quality of the code is improving over time. When reviewing a code, while it assures that everything is correct, it also helps to understand the code better. In this section, the team must describe the conventions (or programs) that the team uses to review code.

### Performance Budgets
As with money, a game also has performance limitations. These can go from hardware limitation to software. This performance budget is not perfect, since it can change as the game progresses. Its purpose is to give the developers a general idea of how the game may look/be like at the end of the production. It also helps to get a realistic expectation of the final result. 

### Level Layout
In the level layout, a scheme of all the levels should be delivered. It should be done from a coding point of view, to explain how to navigate the map.

![image](https://user-images.githubusercontent.com/59050152/109432610-445bdf80-7a0c-11eb-8a5b-2404b006c50d.png)

### User Interface
The user interface has to be approached from a technical perspective.

**Game Menus:** All the menus have to be listed, with the options they provide, and the GUI method needs to be stated.

**In-game Controls:** In this sub-section, all the controls and shortcuts need to be mentioned.

### Collision Detection, Physics & Interaction
This section is more centred on the mechanics.

**Collision Manager:** This describes how will the team manage the collisions between objects/entities.

**Collision Map Manager:** This describes how will the team manage the collisions between objects/entities and the map.

**Use of Physics Engine:** This describes how will the physics of the game work and what type of engine it will use.

### Assets list
In this section, all the assets of the game must be listed, including a picture if possible.

### Hardware and Software Requirements
When developing a game, not all platforms may be able to run it, that is why, in this section, all the requirements need to be stated, both hardware-related and software-related.

### Data Sharing
This asks for a description of the system used to share data, including a list of the programs needed. Also, a description of the delivery method.

### Version list
This section has to be a prediction of all the versions that the game will initially have (based on the estimated schedule), and a summary of what will each version include.

## Common mistakes
These are some of the most common mistakes:
-	The proposal fails to anticipate common-sense issues and concerns.
-	The goals are not realistic.
-	The document is too subjective.
-	The important aspects of the document are overlooked or explained superficially.
-	The document is too long and readers get bored.
-	The feedback is received as a personal matter or it is underestimated. 

## Examples
-	[Example 1](https://www.slideshare.net/obasogie/java-technical-design-document)
-	[Example 2](https://computergamesmmu.files.wordpress.com/2012/10/technical-design-document-final.pdf)
-	[Example 3](https://github.com/DevCrumbs/Warcraft-II/wiki/7.-Tech-Design-Document#branching)
-	[Example 4](http://www.nuclearmonkeysoftware.com/documents/narbacular_drop_technical_design_document.pdf)

## References
-	[The Anatomy of a Design Document](https://www.gamasutra.com/view/feature/3384/the_anatomy_of_a_design_document_.php?print=1)
-	[Zero's Technical Design Document](https://github.com/GameDesign/Zero/wiki/Technical-Design-Document)
-	[Why Writing Software Design Documents Matters](https://www.toptal.com/freelance/why-design-documents-matter)
-	[What is a GDD?](https://medium.com/@cbrown0510/what-is-a-gdd-ca43e2094995)
-	[How to do a Code Review](https://google.github.io/eng-practices/review/reviewer/)
-	[Writing Technical Design Docs](https://medium.com/machine-words/writing-technical-design-docs-71f446e42f2e)

