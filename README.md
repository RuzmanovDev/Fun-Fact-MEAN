# "Fun Fact"* - Teamwork project for TelerikAcademy season 2016, course Angular 2

## Web application for sharing interesting facts
  [Hosted on heroku -->click](https://fun-fact.herokuapp.com/)

  [Video demo](https://www.youtube.com/watch?v=i5u_U2N4Q64)

### Functionality
- All users can view the facts and its details(rating, comments)
- Search and filter
- "Did you know..?" pool
- Registered users can add facts, rate and/or comment them
- Each registered user has a list of his favorite facts
- Each registered user can change its email and/or password
- Each registered  user can upload avatar picture
- Admins can make regular users admins 
- Admins can delete facts
- Admins can block users
- Admins can restore deleted facts
- Blocked users do not have right to login into the application

## Used tecnhologies
- Angular 2 for the front-end
- NodeJs(Express) for the back-end
- MongoDb

## Developed by AbstractionJunkies
## Team members
| Name | [Student system](https://telerikacademy.com) username | [Github](https://github.com) username|
|:----|:-----------------------|:-----------------------------|
| Kiril Velichkov | Kiril_Velichkov | KirilVelichkov |
| Stoyan Ruzmanov | stoyan.ruzmanov | RuzmanovDev |
| Kiril Peyanski  | kikopeyanski    | Ayyavazhi   |

# *This is merged repo from [FunFactApi](https://github.com/AbstractionJunkies/FunFactAPI) and [FunFact](https://github.com/AbstractionJunkies/FunFact) in order to deploy it in heroku :)


# Course Project Requirements
_Single-page Applications with Angular 2_

This document describes the **course project assignment** for the [Single-page Applications with Angular 2](telerikacademy.com/courses/courses/Details/391) at Telerik Academy.

## Project Description

Design and implement a **Single-page application** using [Angular 2](https://angular.io/)

It can be a discussion forum, blog system, e-commerce site, online gaming site, social network, or any other web application by your choice.

The application should have a:

- **public part** (accessible without authentication)
- **private part** (available for registered users)

### Public Part

The **public part** of your projects should be **visible without authentication**.
This public part could be the application start page, application statistics, the user login and user registration forms, as well as the public data of the users, e.g. the blog posts in a blog system, the public offers in a bid system, the products in an e-commerce system, etc.

### Private Part (Registered users area)

**Registered users** should have personal area in the web application accessible after **successful login**.
This area could hold for example the user's profiles management functionality, the user's offers in a bid system, the user's posts in a blog system, the user's photos in a photo sharing system, the user's contacts in a social network, etc.

## Technical Requirements

Your Web application should use the following technologies, frameworks and development techniques:

- At least **8 different public dynamic web pages**
- At least **7 different private (authenticated) dynamic web pages**
- At least **10 different** partial components
  - Partial, as not a whole page
- Responsive UI with good UX
- Most of the data should be loaded from a web server
  - You can use Firebase, parse.com, Telerik Back-end Services, or any other
  - You can use your own server written on Node.js, ASP.NET, or any other framework
- Load all data using services
- Use animations
- Create at least **3 different pipes**
- Create at least **3 different directives**
- Setup and use tslint
- Use **TypeScript**
- Use the **best practices** for software development and Object-oriented design
- Use Dependency Injection

##  General Requirements

- Use Git
  - Github, Gitlab, Bitbucket, or other
- Brief **documentation** of the project and the project architecture
  - As `README.md` file at the root of the github repository

### Deliverables

- Record a short video showcasing your application
  - ~1-2 minutes, just show the interesting features
  - Do not record register/login functionality, this is not interesting...
- Upload your application in the cloud
  - MS Azure, HerokuCloud, Amazon, all are fine
- Register your application at [Our Showcase System](http://best.telerikacademy.com)
  - Link to the live application
  - Link to the video
  - Link to the github repository

### Public Project Defense

Each team will have to make a **public defense** of its work in front of a trainer (for about 30 minutes), in which each of the team members will answer to the trainer's questions individually.

The public defense includes:

- Live **demonstration** of the developed web application (prepare sample data).
- Explain application structure and its back-end and front-end **source code**
- Show the **commit logs** in the source control repository to prove a contribution from all team members.
- May include a simple task for each team member
  - The task must be implemented immediately

### Give Feedback about Your Teammates

You will be invited to **provide feedback** about all your teammates, their attitude to this project, their technical skills, their team working skills, their contribution to the project, etc.
The feedback is important part of the project evaluation so **take it seriously** and be honest.
