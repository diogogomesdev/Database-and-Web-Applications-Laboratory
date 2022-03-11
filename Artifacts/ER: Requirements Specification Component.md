# ER: Requirements Specification Component

## A1: Project Presentation

> This artefact introduces the context and motivation of the project and brifly describes the information system to be developed

ManageME project is an Web Application for managing college projects. This is a tool that can be very useful to all college students who have to carry out complex group projects in which each member is responsible for certain tasks. We believe that this application is of great benefit to all university students especially in the current times we are living due to the COVID-19 pandemic.

This application allows a student to create an account and start creating their projects (as a project manager) or accepting invitations for projects already created by other students. A project must always have a member with special permissions - project manager - who, in addition to doing tasks like the rest of the members, has the additional task of guiding the project and guiding the group, being able to eliminate a member who is not fulfilling theirs tasks and therefore not contributing to the project, such as adding a new member who is interested in taking part, simulating the development of projects in a business environment where it is essential to have a leader to organize members work. A extra part of this project is the description of the weight of the project evaluation in the college class so that all members of a project can consult and realize the importance of the project and thus motivate themselves to give the best they can. A user can access a Forum for each project, beeing this one an  essential piece because members need to talk and discuss ideas.

As a motivation driven application- where project members are driven to work as a team and do their part - it is essential that the design and organization of tasks allow project member to conclude which ones have already worked more and what state the project is in.

Given the large-scale use of smartphones, especially in the age group of people attending college (18-25), it is essential that the user has a good experience both on the computer, on a tablet or on a smartphone. It is also essential that the application is simple to use and the design clear, with only key information so that it is really a help to the students projects development and not a burden.

---


## A2: Actors and User stories

> This artefact contains the specification of the actors and their users stories, serving as agile documentation of the project's requirements


### 1. Actors

![actor_map](uploads/882e545891c67ce8659a0f6a93bf1d8e/actor_map.png)
> 
| Identifier | Description |
| ------ | ------ |
| User | An actor with access to public information. |
| Visitor | Unauthenticated user that can login to his account or register an account. |
| Authenticated Member | User that has login. He can accept invitations check is profile, create projects and view them and mark a project has is favourite. |
| Project Member | Authenticated user that can create and manage tasks, adding other users to the task, view teams and the members profiles, comment on a task, complete a task, search tasks, and can leave the group. |
| Project Coordinator | Project Member that can add and remove users from the project, assign a new coordinator, edit project details, assign a task to a member and archive the project |
| Administrator | User that can browse and view the details of projects, block an unblock users and delete projects. |



### 2. User Stories

> User stories organized by actor.  
> For each actor, a table containing a line for each user story, and for each user story: an identifier, a name, a priority, and a description (following the recommended pattern).

#### 2.1. User

| Identifier | Name | Priority | Description |
| ----- | ----- | ----- | ----- |
| US01 | Home | high | As aa *User* I want access to the home page so that I can obtain information on the site. |
| US02 | Search | medium | As a *User* I want to search for keywords so that I can look for certain projects. |  

#### 2.2. Visitor

| Identifier | Name | Priority | Description |
| ----- | ----- | ----- | ----- |
| US11 | Signin | high | As a *Visitor* I want to signin so that I can access restricted information. |
| US12 | Register | high | As a *Visitor* I want to register an account so that I can access restricted information. |
 
#### 2.3. Authenticated User

| Identifier | Name | Priority | Description |
| ----- | ----- | ----- | ----- |
| US21 | Accept invitation | high | As an *AUser* I want to accept invitations so that I can work on a project.
| US22 | Create a project | high | As an *AUser* I want create a project so that i can work on a project. |
| US23 | View a project | high | As an *AUser* I want to view a project so that i can know the details of said project. |
| US24 | Favourite | medium | As an *AUser* I wanto to mark a project as a favorite so that i can more easily access it. |
| US25 | Profile | high | As an *AUser* i want to change my profile so that i can keep it updated. |

#### 2.4. Project Member

| Identifier | Name | Priority | Description |
| ----- | ----- | ----- | ----- |
| US31 | Create task | high | As a *Member* I want to create a task so that I can work on a specific part of the project. |
| US32 | Manage task | high | As a *Member* I want to manage tasks so that I can change the details of a task. |
| US33 | View task | high | As a *Member* I want to view a task's details so that I know what has to be done. |
| US34 | Assign | high | As a *Member* I want to assign members of a project to a task so the task can be completed. |
| US35 | Complete task | high | As a *Member* I want to make a task complete so that members stop working on it. |
| US36 | Comment | high | As a *Member* I want to comment on a task so that I can express my opinnion. |
| US37 | View a member's profile | high | As a *Member* I want to view a member's profile so that I can obtain information about them. |
| US38 | Leave | high | As a *Member* I want to leave a project so that I don't have to work on it anymore. |
| US39 | Search task | high | As a *Member* I want to search for tasks so that I know what is being worked on. |

#### 2.5. Project Coordinator

| Identifier | Name | Priority | Description |
| ----- | ----- | ----- | ----- |
| US41 | Add user | high | As a *Coordinator* I want to add an user so that user can work on the project. |
| US42 | Remove user | high | As a *Coordinator* I want to remove an user so that use can no longer work on the project. |
| US43 | Assign coordinator | high | As a *Coordinator* I want to make a member of the project a coordinator so that someone else has coordinator privileges. |
| US44 | Edit details | high | As a *Coordinator* I want to edit the details of the project so that the project can keep up to date. | 
| US45 | Assign member | high | As a *Coordinator* I want to assign members to a task so that member works on that task. |
| US46 | Archive | high | As a *Coordinator* I want to archive the project so that i can mark it as completed. |

#### 2.6 Administrator

| Identifier | Name | Priority | Description |
| ----- | ----- | ----- | ----- |
| US51 | Remove User | high | As an *Administrator* I want to remove a user so that he doesn't have access to restricted content. |
| US52 | Delete Project | high | As an *Administrator* I want to delete a project so that non-approved project don't exist on the system. |
| US53 | Check details | high | As an *Administrator* I want to check a project's details so that I can check if they pass guidelines. |
| US54 | Block | high | As an *Administrator* I want to block a user so that he can't comment. |
| US55 | Unblock | high | As an *Administrator* I want to unblock a user so that he can comment. |
| US56 | Browse | high | As and *Administrator* I want to browse the project so that I can check on them. |

### 3. Supplementary Requirements

> Section including business rules, technical requirements, and restrictions.  
> For each subsection, a table containing identifiers, names, and descriptions for each requirement.

#### 3.1. Business rules

| Identifier | Name | Description |
| ----- | ----- | ----- |
| BR01 | Deleted account | When an account is deleted, comments and projects made by them are changed to anonymous. |
| BR02 | Administrator restrictions | An administrator account can't create or be part of a project. |


#### 3.2. Technical requirements

| Identifier | Name | Description |
| ----- | ----- | ----- |
| TR01 | Availability | The system must be up 99% of the time in a 24-hour cycle. |
| TR02 | Accessibility | The system must be usable on any web browse and by anyone, independent of handicaps. |
| TR03 | Usability | The system is supposed to be used by students and professionals, but it should be easy to use. |
| TR04 | Performance | There should be a response time of less than 2 seconds. |
| **TR05**| **Web application** | **The system is to be implemented as a website that doesn't need the installation of other applications or software. It uses standard web technologies. This way is easy to access the projects management everywhere, at house, at a library or at college.**|
| TR06 | Portability | The server-side should work across multiple platforms, to make it easily available to a large user base. |
| TR07 | Database | The PostgreSQL database manegement system should be used. |
| **TR08**| **Security**| **The system has authentication and verification system that will protect user's private information. Nowadays private information is essential in any given software that manages this type of data so is fundamental for our application to encrypt users information** |
| TR09 | Robustness | The system should still continue to operate through runtime errors. |
| TR10 | Scalability | The system must be prepared for the growth in the number of users and projects. |
| **TR11**| **Ethics**| **The system must respect the ethical principles in software development (like the not sharing personal information of its users). Its fundamental that an user can delete their account and this way have their data erased. In software development terms, they have the right to be forgotten** | 


#### 3.3. Restrictions

| Identifier | Name | Description |
| ----- | ----- | ----- |
| C01 | Deadline | The system must be ready to be used by the end of January. |


---


## A3: Information Architecture

> This artefact presents a brief overview of the information architecture of the system to be developed.
> This artefact includes two elements:
> 1. A sitemap, where the information is organized in pages
> 2. A set of 3 wireframes, defining the functionality and the content for each page (homepage, projects list, project details)

### 1. Sitemap

![Diagrama_em_branco__2_](uploads/1f46ce218e2cf010c2ac1ce9c21c5409/Diagrama_em_branco__2_.png)

### 2. Wireframes

#### UI01: Homepage

![wf1__1_](uploads/ae034a058bea412927a4bd9ed4369532/wf1__1_.png)

1 - Link to login

2 - Link to register new user

#### UI16: Projects List

![wf2__2_](uploads/33b8eda68bf9fdaa30066e558f1e27f5/wf2__2_.png)

1 - Button to create a new project

2 - Input box to search for projects

3 - Project highlighted where the user is the project manager

#### UI19: Project Details

![wf3__2_](uploads/7823bbe8f2b6f6db0158d236236f5833/wf3__2_.png)

1 - Button to access tasks for specific project

2 - Button to access forum for specific project

---

***
GROUP2195, 5/11/2021

* Group member 1 Alberto Cunha, up201906325
* Group member 2 Diogo Geraldes, up201907847
* Group member 3 Diogo Gomes, up201505676
* Group member 4 Helder Bessa, up201503035
